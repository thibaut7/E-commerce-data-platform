# E-commerce-data-platform
**Repository Overview**  
This repository hosts the data engineering pipelines and analytics framework for a scalable e-commerce platform. The architecture integrates multiple databases and tools for data storage, processing, and visualization, leveraging both on-premise and cloud-based systems.  

### Key Components  
- **Databases**:  
  - Product catalog stored in MongoDB (NoSQL).  
  - Transactional data (inventory and sales) managed in MySQL (OLTP).  
  - Staging data warehouse on PostgreSQL.  
  - Production data warehouse on IBM DB2 (cloud).  

- **Data Processing**:  
  - ETL pipelines powered by Apache Airflow to facilitate seamless data transfer between OLTP, NoSQL, and data warehouses.  
  - Hadoop cluster utilized for big data storage and processing.  
  - Spark integrated for advanced data analytics on the Hadoop platform.  

- **Business Intelligence**:  
  - Dashboards created using IBM Cognos Analytics, connected to the IBM DB2 data warehouse for operational insights.  

### Use Cases  
This setup supports real-time inventory and sales management, advanced analytics for business decision-making, and operational dashboarding.  

Feel free to explore the repository for implementation details, configurations, and best practices for managing scalable data workflows.
