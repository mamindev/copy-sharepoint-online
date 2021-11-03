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
