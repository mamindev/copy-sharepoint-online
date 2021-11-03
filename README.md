DISCLAIMER: 
This Sample Code is provided for the purpose of illustration only and is not intended to be used in a production environment. THIS SAMPLE CODE AND ANY RELATED INFORMATION ARE PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A PARTICULAR PURPOSE. We grant You a nonexclusive, royalty-free right to use and modify the Sample Code and to reproduce and distribute the object code form of the Sample Code, provided that You agree: (i) to not use Our name, logo, or trademarks to market Your software product in which the Sample Code is embedded; (ii) to include a valid copyright notice on Your software product in which the Sample Code is embedded; and (iii) to indemnify, hold harmless, and defend Us and Our suppliers from and against any claims or lawsuits, including attorneys’ fees, that arise or result from the use or distribution of the Sample Code.

# copy-sharepoint-online
This template ADF/Synapse pipeline is an example of how to copy data from a Sharepoint Online site. For context and prequisite steps follow: [this](https://docs.microsoft.com/en-us/azure/data-factory/connector-sharepoint-online-list?tabs=data-factory#copy-file-from-sharepoint-online). 

This pipeline implements [this step](https://docs.microsoft.com/en-us/azure/data-factory/connector-sharepoint-online-list?tabs=data-factory#copy-file-from-sharepoint-online).

## Importing the pipeline
### 1. Download this repository as a zip folder
### 2. In Synapse workspace, go to Integrate, click on + and Import from pipeline template. Choose this downloaded zipped repo. 
![alt text](https://github.com/mamindev/copy-sharepoint-online/blob/main/docs/1.png)
### 3. If you don't have it already, create a new HTTP linked service to pointing at the base of the sharepoint site
![alt text](https://github.com/mamindev/copy-sharepoint-online/blob/main/docs/2.png)
### 4. Choose "Anynomus" for authentication type
![alt text](https://github.com/mamindev/copy-sharepoint-online/blob/main/docs/3.png)
### 5. Create or choose the right destination linked service and click 'Open Pipeline'
![alt text](https://github.com/mamindev/copy-sharepoint-online/blob/main/docs/4.png)
