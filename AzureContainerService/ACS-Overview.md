#Azure Container Service - 02/06/2017
ACS has a single goal, make containers easy to get started on Azure. To achieve this ACS offers an IaaS-like service that sets up compute, storage, and networking on your behalf via ARM template.
The formatting currently uses Docker containers with a choice of Marathon + DC/OS, Swarm, or k8s as your orchestrator. Standard API endpoints are exposed for each orchestrator for ease of open-source tooling.

## Deploying
You can do this via the GUI Ibiza Portal or via command line with the Azure CLI 2.0.

### Portal
1. Search for 'Container Service' from a new blade
2. Select Azure Container Service
3. Define user info such as username, subscription, resource group, and keys
4. Select orchestrator
5. Define ACS settings such as master and agent nodes, agent VM size, and a DNS prefix

Just like that you have your first container service deployed and it can now be intereacted with the usual orchestrator endpoints!

### CLI 2.0

#### Deploy
The command below will deploy your cluster and generate a key on your behalf to use as authentication.
* -n passes a name for your acs
* -g references the resource group to place it in 
* -d defines the unique DNS prefix for your service
* --generate-ssh-keys will gen a public and private key for you to access your acs 

`az acs create -n myacs -g myrg -d uniquedns --generate-ssh-keys` <br>

#### List
`az acs list --output table`

#### Details of cluster
`az acs show -g myrg -n myacs --output list`

#### Scale out 
This will allocate 4 more agents into your cluster chosen by -n

`az acs scale -g myrg -n myacs --new-agent-count 4`

#### Delete
Deleting compute resources such as ACS in Azure will not remove associated storage and networking resources. As a result you should deploy a new RG per set of resources, so when you are done you can delete the entire RG to clean-up any associated resources.

`az acs delete -g myrg -n myacs`