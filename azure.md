#Part 2: Azure Exploration
Storage: 
    Service #1: Access tiers for blob data
    Access tiers offered by Azure allows a user to store their data in a more cost-effective way depending on how long they want to store their data and how often they want to access it. This is important since not all data needs to be available 24/7 nor does it need to be stored for long periods of time. The same can be said for the opposite as well. That is why Azure provides a cost-effective way to store and access data depending on the needs of the user. Azure offers four different tiers which are Hot, Cool, Cold, and Archive. Hot means that data will be frequently accessed and or modified and thus does not need to be stored for long periods of time. This tier has the highest storage costs, but the lowest access costs of all tiers. Cool comes next and it is for data that is accessed or modified not as often compared to Hot tier. This tier has lower storage costs and higher access costs. It is recommended to store this data for a minimum of 30 days. Cold tier does the same as Cool except it has even lower storage costs and higher access costs compared to Cool. It is recommended to store this kind of data for a minimum of 90 days. Lastly, the Archive tier is for data that is rarely accessed and if it does need to be accessed it will take longer than the other tiers in the time frame of hours. This has the lowest storage costs and the highest access costs out of any tier. Data should be stored for a minimum of 90 days. 

    Service #2: Azure Data Lake Storage Gen2
    Azure provides its latest version of a data lake to users known as Azure Data Lake Storage Gen2. This data lake is a single repository where a user can store both structured and unstructured data. It also allows for not only ample storage, but large-scale data analysis as well. It is able to use REST APIs, hierarchy namespace when organizing files into directories and subdirectories, object tiering, and is highly scalable. It is an upgraded version of Gen1 with improvements in pricing, scalability, security, and compatibility.

    Python Interaction: 
    Both the access tiers are built on the Azure Blob Storage they both are compatible with the integration of Python. According to the Quickstart: Azure Blob Storage client library for Python you can do a pip install to import the different services and packages needed. You can use keys on specific directories or files using Python with these services. There are also links available to the GitHub for the Azure SDK for python at https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/storage/azure-storage-blob/samples. 
 

Compute:
    Service #1: App Service
    Azure App Service allows for a user to create web apps easily. It is a HTTP-based hosting service that supports a wide variety of languages such as Python, Ruby, Java and more. It has integrations with Github for deployment and VS Code for creating and debugging. It has built-in authentification with popular services such as Google, Twitter, and Meta. 

    Python Interaction:
    You are able to create apps using Django or Flask and documentation is provided https://learn.microsoft.com/en-us/azure/app-service/tutorial-python-postgresql-app?tabs=flask%2Cwindows. Using Python you could deploy a web app using this service and it could be used in a healthcare setting potentially since it also allows for support for RESTful APIs. 


    Service #2:Azure Functions
    Azure Functions is a service that allows for a serverless option to perform event-driven systems. This allows a user to write less code, save on expenditures, and rely on less infrastructure. These are essentially automations that can take place once parameters are met. For instance, once a file is uploaded to the cloud code can then run accordingly. You can also have data cleanup set up at predefined intervals. It supports a variety of languages such as C#, Java, Python, and many more. 

    Python Interaction:
    This would be useful with Python by creating a chatbot or virtual assistant. They could be created using Python and supported using Azure functions. That way it could have reliable uptime and up-to-date information. By also using these functions it could give more access to other chatbot frameworks to use that could be more advanced. 

Database:
    Service #1: Azure SQL Edge
    Azure SQL Edge is a relational database engine that is built for IoT and IoT Edge deployments. It can process and analyze relational and non-relational data like graphs and JSON data. Its capability of providing portability between IoT devices and data centers makes it flexible in its use cases. 

    Python Interaction:
    Since it is able to take in and analyze different types of data I’d say it would be useful for it to help with organizing data in a visually comprehensive way. Using SQL queries on data in the database you could use Python with a pandas package to create data frames to better view the data. 

    Service #2:SQL Server on Windows Azure Virtual Machines
    SQL Server on Windows Azure Virtual Machines allows for easy on-demand access to different-sized machines around the world to run full versions of SQL Server. This has the added benefit of having backups and disaster plans built into the service. Thus keeping large quantities of data safe in the event of an incident. It also allows for automated patching to give updated security patches during off-peak hours. 

    
    Python Interaction:
    I can see this service being used by running scripts on the SQL Server to analyze data. Then use python libraries such as Matplotlib to create reports or other visualizations. 
