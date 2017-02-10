# Access Control Lists (ACLs) - 2/10/2017
I could only find ASM documentation for ACLs so this info is based on the ASM model.

An ACL is a security feature for Azure deployments. Creating an ACL allows you to selectively allow or deny traffic to a VM endpoint.
You can filter packets to endpoints, but not for VNets or a specific subnet in a VNet.

## Configure ACLs
You'll need to use [PowerShell](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-acl-powershell) to configure these.

## Features
* Permit/deny incoming traffic on IPv4 address ranges to a VM input endpoint
* Blacklist IP addresses
* Create (up to 50) rules for each VM endpoint
* Apply rule ordering to each endpoint's list of rules

## How it works
An ACL is an object containing a list of rules. This object applies to a VM endpoint, where packet filtering occurs on the host node for your VM.
Effectively, traffic from remote IPs are filtered by the host node against rules set on your VM. This is great for you as your VM won't be expending CPU cycles to do this filtering.

**Example – Multiple rules**

| **Rule #** | **Remote Subnet** | **Endpoint** | **Permit/Deny** |
| --- | --- | --- | --- |
| 100 |65.0.0.0/8 |3389 |Permit |
| 200 |159.0.0.0/8 |3389 |Permit |

### Tips
1. By default, no ACL is placed so all is permitted to an endpoint.
2. Adding a "permit" range means you deny all other ranges.
3. Adding a "deny" range means you permit all other ranges.
