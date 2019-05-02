# Azure Storage - Blobs

Azure Blob storage is Microsoft's object storage solution for the cloud.

Blob is perfect and optmized solution for storing massive amounts of unstrcutured data , such as text and binary data.

## :point_right: What can be stored?

- Images and documents to be access from browser
- Audio/Video
- Storing files for distrubted acces.
- Storing data for backup, recovery , and archiving.
- Stroing data for analysis.

_Users or client applications can access objects in Blob storage via HTTP/HTTPS, from anywhere in the world._

## :point_right: Blog storage

1. Create a Storage Account
2. A container in the storage account
3. A blob in the container

### :point_right: Storage Account

A storage account provides unique namespace in Azure for your data. The combination of the storage account and blob endpoints forms the base address for the objects in your account.

### :point_right: Containers

A container organizes a set of blobs, similar to a directory in a file system. A storage account can include an unlimited number of containers, and a container can store an unlimited number of blobs.

### :point_right: Blob

_Type of Blob_

1. Block Blob
2. Append Blob
3. Page Blob

## :point_right: Blob Storage for Web Developers

1. Save static images
2. Save dynamic images
3. Save JSON files/data
4. Save videos
5. Save Audios

https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-javascript-client-libraries

https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-host

https://docs.microsoft.com/en-us/rest/api/storageservices/cross-origin-resource-sharing--cors--support-for-the-azure-storage-services
