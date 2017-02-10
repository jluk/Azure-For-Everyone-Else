# File Storage
Azure File storage allows file sharing in the cloud using Server Message Block (SMB) protocol.

## Access 
By using SMB file shares, apps running in Azure can access data in shares via file system I/O APIs.
* Devs can reuse existing code/knowledge to migrate legacy apps.
* IT Pros can create, mount, and manage file storage shares with PowerShell cmdlets

## Concepts

![](../media/files-concepts.png)
* Storage account - all access to Azure storage is done through your storage account
* Share - a file storage share is an SMB file share in Azure
  * All directories/files must exist in a parent share
  * Accounts can have unlimited shares
  * Share can have unlimited files with a 5 TB total cap per share 
* Directory - optional hierarchy of directories
* File - a file in the share up to 1 TB
* URL format - https://`<storage account>`.file.core.windows.net/`<share>`/`<directory>`/`<file>`
  * Picture example - `http://samples.file.core.windows.net/logs/CustomLogs/Log1.txt`

## SMB protocol
SMB is a network file sharing protocol implemented in Windows originally.
* Dialect - set of message packets defining the version of the protocol
* CIFS - Common Internet File System is a dialect of SMB
* Acts as client-server implementation delivering set of data packets each with a request sent by client or a response sent by server
  * Session control packets - establish/discontinue connection to shared server resources
  * File access packets - access/manipulate files/directories on the remote server
  * General message packets - send data to print queues, mailslots, named pipes and provide data about status of print queues
* Batching - Sending groups of packets in one transmission to reduce latency and increase network bandwidth

SMB is most often used as an application or presentation layer protocol, relying on lower-level protocols for transport.
Frequently you find under-lying protocols use NetBIOS over TCP/IP.

## Read more
[Files marketing](https://azure.microsoft.com/en-us/services/storage/files/)
[Files pricing](https://azure.microsoft.com/en-us/pricing/details/storage/files/)
[Using Azure Files](https://docs.microsoft.com/en-us/azure/storage/storage-dotnet-how-to-use-files)