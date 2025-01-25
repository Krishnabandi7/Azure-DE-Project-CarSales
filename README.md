# Azure-DE-Project-CarSales

![image](https://github.com/user-attachments/assets/64b43782-1da3-43da-bd95-af3032d9ae42)


This process leverages SQL databases, GitHub, and Azure to handle data storage and transformation. Data is stored in Azure, processed through ETL/ELT tools like Azure Data Factory using the Medallion Data Structure, focusing on incremental data in the silver layer (Parquet format). Databricks is used to load data into the gold layer with Delta format. The Unity Catalog in Databricks manages metadata and ensures smooth data flow. Pipelines are created for incremental data processing, and watermarks are used for tracking changes. Data is modeled with star schemas, using surrogate keys and Slowly Changing Dimensions (SCD Type-1) for efficient updates. The system also supports creating and managing catalogs, clusters, and schemas, with parameters for both initial and incremental runs, ensuring that the gold layer tables are continuously updated with fresh data.
![Screenshot 2025-01-24 230000](https://github.com/user-attachments/assets/18a4acfd-bd65-4eba-a01d-1759acf10c90)

![Screenshot 2025-01-24 225924](https://github.com/user-attachments/assets/438eb431-aef0-49ae-95bb-3d2e953ab065)


![Screenshot 2025-01-24 230754](https://github.com/user-attachments/assets/1d320f43-9a36-41fa-bf86-a9832ea98e5b)


![image](https://github.com/user-attachments/assets/155cd773-9044-4856-a0e9-d254dd01441f)
