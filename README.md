# fabric-cosmosdb-chat-analytics
Microsft fabconeurope2024: Demo material and Fabric notebooks for analyzing chat history stored in CosmosDB NoSQL containers

## Prerequisites

You need the following services to run this notebook.

- [Microsoft Fabric](https://aka.ms/fabric/getting-started) with 64 capacity
- [Azure CosmosDB NoSQL account](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/quickstart-portal)

You also need to upload chat_history and product catalog information to a Cosmos DB NoSQL database as separate containers. 
- For CosmosDB mirroring, please follow the [documentation](https://learn.microsoft.com/en-us/fabric/database/mirrored-database/azure-cosmos-db)


## Extracting insights


### Steps
1) Mirror chat history and product catalog data in Fabric OneLake. 
The data for product catalog is found in product_catalog directory and a sample data for chat_history data can be found in chat_history_data directory. Please use the chathistory_all.json. 

2) Create Shortcuts of chat history and product catalogin into Lakehouse

3) Run the analyis Notebook
Navigate to the analysis_notebook directory. 
Open the main_demo notebook and attach the lakehouse and run the notebook. 

