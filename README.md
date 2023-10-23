# asian-games-azure-data-engineering-project

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/359ab763-53be-4717-ad71-ca7ac02d324b)

Creating storage account and container:

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/5f60f176-e37a-4d51-9d42-735b699c8d19)

Creating directories

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/d5ebf319-b790-4674-bb23-adf23b420eb0)

Creating Azure Data Factory

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/8afeb95a-ce25-41d7-b4d8-39726a86a68c)

Creating data ingestion pipeline

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/916a7adf-e2ce-4471-a38a-be439c5dc126)

Debugging the pipeline to copy data from github

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/9184b632-ddcb-408a-8eda-2cb9258f539c)

Creating app registration

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/262e9cd6-a12e-4190-8735-524451b8e0bc)

Creating secret key

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/81103185-b734-4f25-8a94-33e5534e632e)

Creating databricks workspace

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/c7784431-162a-4d45-a83a-2a2f817dad7d)

Creating cluster

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/c315c14a-cceb-46c7-a98b-db2deb9d28fc)

Creating Key vault

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/b2482bbf-38eb-4d96-95e0-8d77ef741b44)

Giving access of key vault

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/f3257880-34dd-4499-ac1b-4d00c993d294)

Creating secrets in key vault for app client id, tenant id and secret key

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/bb75bae0-40a8-4c55-b7a1-d9a9d9a5d9c9)

Giving access to key vault secrets

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/bbd68dac-1414-4303-9c6f-d92dd5e5730d)
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/6046b6df-5cb8-4439-86c9-50cd5d2ccf8a)


If you face issue while accessing secrets, read https://learn.microsoft.com/en-us/azure/role-based-access-control/troubleshooting?tabs=bicep#:%7E:text=az%20role%20assignment%20create%20%2D%2Dassignee%2Dobject%2Did%2011111111%2D1111%2D1111%2D1111%2D111111111111%20%20%2D%2Drole%20%22Contributor%22%20%2D%2Dscope%20%22/subscriptions/%7BsubscriptionId%7D/resourceGroups/%7BresourceGroupName%7D%22

Creating scope in databricks workspace

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/1355686c-1b6f-44ff-8cee-4d4f91d21c62)

![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/a51f15ea-37cf-4baf-8764-0c4b64a94cd6)

Checking secrets through cli
Install databrick-cli using following command in cmd - pip install databricks-cli
After installation check version by following command - databricks --version
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/7673f408-dccc-468c-96ac-97999986e909)

If it gives error of couldnt recognize databricks something, just add your folder path where databricks.exe is installed into your PATH of environment varialbles
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/f8b562f2-784c-44c4-af41-aa88c7311ddf)

Connecting cli to databricks using following command- databricks configure --token
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/10b3a1e0-4c60-4ceb-85e8-d595c11ae6e5)

Generating and using token from databricks User settings
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/73ba9315-6413-41e3-a2e3-040e3d7789f7)

Reading secrets from cli
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/067ac24c-d291-413e-a11d-3761034a1227)
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/49c45567-2fef-4910-86a9-f80ae7852013)

Creating dedicated sql pool
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/b1289ad0-c44d-4551-8d79-f79ef0666fe5)

Logging in using query editor by SQL authentication
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/e2389f5f-29d9-4c39-95b2-24a79c6c9811)

Generating SAS key in storage account
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/564690f7-a25a-4db6-bf41-3d671748a89a)

Finding Primary endpoint for storage account
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/b3b89929-1aaf-47b4-be04-9c1507b48c19)

Creating MASTER KEY
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/69446ddf-f72c-4f5b-9800-ba6d9be35a2d)

CREATING CREDENTIAL
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/4b2e99cb-2bce-40d5-8ff9-426d8d7ea72e)

Creating External Data Source
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/be9b5b3c-8c04-4446-9311-ca66182d8624)

Creating External File Format for parquet
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/36b6d4ef-819c-422b-933e-9d132214bf6d)

Creating External table on top of parquet data in ADLS
![image](https://github.com/TejasBav/asian-games-azure-data-engineering-project/assets/148721897/9026954a-7f75-4106-9012-42c586277933)
