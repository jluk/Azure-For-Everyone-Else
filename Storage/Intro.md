# [Intro to Azure Storage] (https://docs.microsoft.com/en-us/azure/storage/storage-introduction) - 01/12/2017

* One of the three core IaaS offerings by Azure, this allows applications to store hundreds of terabytes if needed in order to offer experiences that rely on pivotal concepts such as big data, simulation, analysis, or general data storage.

What is Azure storage? <br>
* Scalable: You can store trillions of unique objects or as few as you wish, you will only be billed for what you use.
* Auto-partitioning: It will grow with your needs automatically, as storage requests go up you will receive additional resources to meet demand.
* Accessible: Azure storage can be accessed from anywhere in the world with low-latency only offered by a cloud provider as large as Azure.

Services? <br>
* Blob Storage: stores unstructured object data - binaries, documents, media - (container)
  * Every blob is orgnanized into a container w/ individual security policies for groups of objects
  * A single storage account can have any number of containers --> each container can have any number of blobs 
    * 500 TB limit of a single storage account
  * Optimized for streaming/storing documents/media/files/backups
* Table Storage: stores structured datasets - databases - (entities)
* Queue Storage: provides reliable messaging for communications between components of services (messages)
* File Storage: stores legacy applications using SMB protocol (share)
  * Can mount a file share in the cloud just like desktop mounts an SMB share
  * Applications access via file system I/O APIs
  * 

Accounts? <br>
* General-purpose: Access to Tables, Queues, Files, and Blobs under a single account 
  * Standard storage performance
  * Premium storage performance
* Blob: Specialized account to store unstructured data
  * Hot access: high-frequency of access so you're charged lower access cost
  * Cold access: low-frequency of access so you're charged lower storage cost

How much does it cost? <br>
* [Base storage costs] (https://docs.microsoft.com/en-us/azure/storage/storage-blob-storage-tiers#pricing-and-billing)