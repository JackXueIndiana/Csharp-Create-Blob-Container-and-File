# Csharp-Create-Blob-Container-and-File
This article shows you how to use C# to access an Azure Storage Account and then create a Blob containter and add a file in it.

Regarding blob container creation and file movement, we followed this example: 
https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet?tabs=windows

Assuming an Azure Storage Account has been created and you have Visual Studio 2017 handy, you can run this code, which does the folloiwng for you:

1. Access the Storage Account

2. Create aBlob container

3. Assign the security to the container

4. Make a local file and then copy it to the container

5. After a DOS prompt, delete the file and then the container.

In this project you need to add Nuget package WindowsAzure.Storage v 9.3
