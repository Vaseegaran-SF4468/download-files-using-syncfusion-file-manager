# Use a Dynamic Blob Container in the Blazor File Manager

**Repository Description**  
This repository contains a Blazor sample that demonstrates how to **download files from Azure Storage and configure a dynamic Azure Blob container** using the Syncfusion **Blazor File Manager** component.

The project showcases how Azure Blob Storage can be integrated with the Blazor File Manager to dynamically determine and access blob containers at runtime.

## Project Overview
The purpose of this project is to help developers understand how to integrate **Azure Blob Storage** with the Syncfusion Blazor File Manager. It focuses on configuring blob containers dynamically, enabling flexible file management scenarios in Blazor applications that use cloud storage.

## Features
- Integration of Syncfusion **Blazor File Manager**  
- Connect to **Azure Blob Storage**  
- Dynamically set and use blob containers  
- Download files from Azure Storage  
- Cloud‑based file management in Blazor applications  

## Prerequisites
Ensure the following requirements are met before running this project:
- Visual Studio  
- .NET SDK compatible with Blazor  
- Azure Storage account and Blob container  
- Valid Azure Storage connection string  

## Installation
1. Clone or download this repository to your local machine.
2. Open the solution in Visual Studio.
3. Restore NuGet packages.
4. Configure Azure Storage details such as connection strings and container names.

## Usage
Run the Blazor application to view the File Manager connected to Azure Blob Storage. The File Manager dynamically resolves and accesses blob containers, allowing users to browse and download files stored in Azure.

This approach is useful for:
- Multi‑tenant storage scenarios  
- Cloud‑based document management  
- Applications requiring flexible storage configuration  

## Configuration
The Azure Blob container is configured dynamically within the Blazor application. This allows the File Manager to adapt to different storage requirements without hard‑coding container names.

## Examples
- Dynamic blob container selection  
- File download from Azure Storage  
- Blazor File Manager cloud integration  

## Documentation
- **General Syncfusion documentation:**  
  https://help.syncfusion.com/
- **Blazor Introduction:**  
  https://blazor.syncfusion.com/documentation/introduction
- **Blazor File Manager Getting Started:**  
  https://blazor.syncfusion.com/documentation/file-manager/getting-started

## Additional Resources
- Blog reference:  
  https://www.syncfusion.com/blogs/post/easily-use-a-dynamic-blob-container-in-the-blazor-file-manager.aspx

## Troubleshooting
- Verify Azure Storage connection strings are valid.
- Ensure the blob container exists and has proper access permissions.
- Rebuild the solution if changes to configuration are not reflected.
- Check runtime logs for Azure connectivity or authorization issues.

## Support
For detailed API references, Azure integration guidance, and Blazor File Manager configuration options, refer to the Syncfusion Blazor documentation links provided above.