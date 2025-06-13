## Types of Azure Storage
- Blob Storage
- File Storage
- Queue Storage
- Table Storage
- Disk storage

## Blob Storage (Binary Large Object)
Blob storage is Azure's object storage solution for the cloud. It's optimized for storing massive amounts of unstructured data like text or binary data (images, videos, backups, logs, etc.).

*Types of Blobs:*
- Block blobs

   Used for storing text and binary files (e.g., images, PDFs, videos).
- Append blobs

   Optimized for append operations (e.g., logging data from IoT devices).
- Page blobs

   Used for frequent read/write operations, commonly used for Azure VM disks.

*Key Components:*
- Storage Account: The top-level namespace for all Azure storage services.

- Container: A grouping of blobs. Similar to a folder.

- Blob: The actual file or data.

## File Storage
Azure File Storage provides a shared file system in the cloud using the SMB (Server Message Block) protocol. It can be mounted concurrently by cloud or on-premise systems.

Think of it as a network drive but hosted on Azure.

*Key Components:*
- File Share: A container for files, like a folder.

- Directory: Folders inside a file share.

- Files: The actual documents, media, etc.

## Azure Queue Storage
Queue Storage provides a messaging solution for asynchronous communication between application components. It enables decoupling of services and allows for better scalability and fault tolerance.

*Key Components:*
- Queue: A storage container for messages.

- Message: Text-based data (up to 64 KB each) added to the queue.

## Azure Table Storage
Table Storage provides NoSQL key-value storage for semi-structured and non-relational data. It is highly scalable and low-cost.

*Key Components:*
- PartitionKey: Groups related rows together

- RowKey: Uniquely identifies each row in a partition

- Entity: A single row of data

## Azure Disk Storage
Disk Storage provides persistent, high-performance block storage for Azure Virtual Machines (VMs). It's similar to a hard drive connected to your computer.

*Types of Disks:*
- OS Disk: Contains the VM's operating system

- Data Disk: Used for storing user data, applications, databases

*Performance Tiers:*
- Standard HDD: Low-cost, suitable for dev/test
- Standard SSD: Balanced performance
- Premium SSD: High-performance, low-latency
- Ultra Disk: Extreme performance for mission-critical workloads
