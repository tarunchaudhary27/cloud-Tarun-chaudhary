
Descriptive Analysis of City of Vancouver’s Public Washrooms
Project Description
This project focuses on designing and implementing a data analytics platform for the City of Vancouver. It especially addresses the need for descriptive analysis of public washroom information to offer insights for city planning and aid allocation.
Project Title
AWS Data Analytic Platform for The City of Vancouver - Descriptive Analysis of Public Washrooms
Objective
The objective is to design and put into effect a data analytic platform the usage of AWS services to support descriptive analysis of the City of Vancouver's public washroom records.  This involves a chain of steps to ingest, profile, clean, catalog, and summarize the data, in the end supplying valuable insights for the town.
Dataset
The dataset used for this analysis is the City of Vancouver's public washroom data, provided in CSV format (public_washroom.csv)
Methodology
This section provides information on the steps undertaken to research the data.
Data Extraction: The record was sourced from Vancouver’s Open Data platform.
Data Ingestion: The public washroom data, available in CSV layout, changed into ingested into an Amazon S3 bucket named “vancity-pbwashroom-raw-tarun”. This step affords scalable and flexible data processing, sharing, archiving, control, and analysis solutions.
Data Cleaning and Profiling: AWS Glue DataBrew is used to profile the "public washrooms" dataset within the "vancity-pbwashroom-trf-tarun" S3 bucket to apprehend its schema and data characteristics. The dataset includes one hundred and five rows of string information.  No missing values or duplicates were observed.  Subsequently, the dataset was cleaned using AWS Glue DataBrew, with the project named “vancity-pbwashroom-prj-tarun”.  Cleaning involved steps which include renaming, separating, and reordering the information to enhance readability and put together it for in additional analysis.
Descriptive Statistics: The file mentions calculating descriptive data as part of the information summarisation process and the count of washrooms per location.
Data Exploration and Analysis: 
Data exploration and evaluation involved examining the clean and summarized data to extract significant insights.
●	Analysing the distribution of public washrooms throughout unique geographical regions of Vancouver.
●	Identifying areas with a high or low density of public washrooms.
●	Exploring the connection among washroom availability and populace density or traveller regions.
●	Analyzing tendencies in protection frequency to become aware of capability regions for development.
Tools and Technologies
The following AWS services were applied on this task:
●	Amazon S3: For storing the raw and transformed public washroom statistics.
●	AWS Glue DataBrew: For statistics profiling and cleaning obligations.
●	AWS Glue Data Catalog: For cataloging and handling the metadata of the data statistics.
●	AWS Glue: For records summarization and ability ETL (Extract, Transform, Load) techniques.
Deliverables
The project deliverables include:
●	Ingested raw public washroom data saved in the Amazon S3 bucket “vancity-pbwashroom-uncooked-tarun”.
●	A cleaned and converted dataset, prepared for analysis.
●	A statistics catalog in AWS Glue Data Catalog, offering metadata management.
●	Summarized data, providing key descriptive statistics.
●	Descriptive analysis of the public washroom facts, including insights and traits related to distribution, accessibility, and protection.
●	A cost estimate for the AWS resources used within the assignment.
Recommendations:
Optimize washroom distribution based on location utilization: Analyze the summarized facts to perceive locations with high public washroom utilization and recommend optimizing the distribution of centers to meet demand. Prioritize regions with excessive foot traffic, tourist pastime, or confined existing centers.
Improve accessibility in key regions: Based at the evaluation of accessibility data, suggest particular locations wherein accessibility enhancements are needed. Prioritize regions with high utilization or in which accessibility is currently restrained.
Enhance renovation schedules primarily based on utilization patterns: Analyze the data to discover tendencies in washroom utilization and endorse adjusting maintenance schedules hence. Increase protection frequency in high-utilization regions to make sure cleanliness and hygiene.
Integrate user feedback for service improvement: Explore integrating user comments facts (e.g., rankings, evaluations) with the existing dataset to advantage insights into consumer pleasure and discover areas for provider development. Develop a machine for gathering and analyzing person remarks.
Allocate resources for excessive-demand centers: Use the analysis to tell resource allocation choices, prioritizing investment and staff for the preservation and improvement of excessive-call for public washrooms.
Data Wrangling for City of Vancouver’s Public Washrooms
Project Description
This project specializes in data wrangling of the City of Vancouver's public washroom data to ensure its accuracy, consistency, and usability for subsequent analysis and urban planning functions. The assignment utilises AWS gear to easily rework and prepare the dataset.
Project Title
Data Wrangling of City of Vancouver's public washroom data.
Objective
The primary objective of this undertaking is to carry out end-to-end information wrangling on the City of Vancouver’s public washroom data to guarantee its correctness, completeness, and usability. The clean and consolidated data will enable effective analysis, revealing patterns and assisting city planning choices.
Background
The City of Vancouver collects and maintains information on public washrooms, including information on location, accessibility, and maintenance schedules. However, the raw dataset may comprise inconsistencies, missing values, and formatting problems that preclude its powerful use for evaluation and choice-making.
Dataset
The project utilizes the City of Vancouver’s public washroom dataset. Key attributes of this dataset include:
●	Location records (e.g., address, coordinates).
●	Accessibility information (e.g., wheelchair available, hours of operation).
●	Maintenance statistics (e.g., cleaning schedules).
Methodology
This phase information the steps worried in wrangling the general public washroom information.
Data Collection: This step involves acquiring the general public washroom information from the City of Vancouver's open records portal.
Data Ingestion: The raw dataset is ingested into an Amazon S3 bucket (vancity-pbwashroom-raw-tarun) for a centralized and secure storage
Data Assessment: AWS Glue DataBrew is used to assess the dataset's quality. This involves:
●	Identifying missing values in key attributes.
●	Detecting and documenting duplicate records.
●	Examining data codecs for inconsistencies.
●	Creating data profiles to summarize key facts.
●	Logging any inconsistencies or anomalies that require cleaning.
Data Cleaning: This level involves addressing the data’s great troubles, which are identified at some stage in the evaluation. This can also consist of:
●	Imputing or deahandlingling with missing values (e.g., for location or accessibility records).
●	Removing or marking duplicate data.
●	Standardising data formats (e.g., for addresses, dates, or accessibility indicators).
Data Transformation: AWS Glue DataBrew is used to transform the dataset, which may additionally involve:
●	Converting data types.
●	Creating new features (e.g., extracting location features from address).
●	Normalising data.
Data Consolidation with Amazon Glue (Visual ETL) and DynamoDB:
●	Import the clean and transformed public washroom dataset into a Visual ETL pipeline using AWS Glue.
●	AWS Glue used to structure the statistics, define variations, and load it into a tarket information store.
●	The schema for the consolidated data will include applicable attributes from the clean dataset, together with:
○	Location information (e.g., address, coordinates).
○	Accessibility info.
○	Maintenance data.
●	The processed data is stored in Amazon DynamoDB, a NoSQL database service.
●	DynamoDB lets in for efficient storage, retrieval, and querying of the consolidated public washroom statistics, supporting diverse use cases, which includes:
○	Geographical analysis of washroom distribution.
○	Analysis of accessibility functions across different locations.
○	Supporting real-time applications that require quick access to washroom information.
This provides a clearer image of how AWS Glue was used for the ETL process and the way DynamoDB is employed for storing and permitting efficient access to the consolidated data.
Monitoring and Security: Implement security features to shield the records, along with IAM roles for access manage and encryption for data at rest. Set up monitoring to song facts processing jobs and data quality metrics.
Tools and Technologies
●	Amazon S3: For storing raw and transformed data.
●	AWS Glue DataBrew: For statistics evaluation, cleaning, and transformation.
●	AWS Glue: For facts consolidation and ETL procedures.
●	IAM: For access control and security.
Deliverables
●	A cleaned and converted dataset is stored in an appropriate layout.
●	Documentation of the records wrangling technique, together with cleansing steps and alterations carried out.
Timeline
A distinct timeline for the data wrangling undertaking, outlining the duration of every stage:
Week 1: Data intake and storage configuration on Amazon S3.
Week 2: Data evaluation using AWS Glue DataBrew.
Weeks 3–4: Data cleaning and transformation the usage of AWS Glue DataBrew.
Week 5: Data transformation and function engineering using AWS Glue DataBrew.
Week 6: Data consolidation with Amazon Glue (Visual ETL) and DynamoDB.
Week 7: Monitoring and protection implementation the use of IAM, KMS.
Week 8: Documentation and evaluation of the facts wrangling method.

Data Quality Control of the City of Vancouver’s Public Washrooms
Project Description
This project pursues to establish a Data Quality Control (DQC) framework for the City of Vancouver's public washroom dataset using AWS services. The purpose is to ensure the dataset's accuracy, completeness, consistency, and reliability for effective city making plans and public service management.
Project Title
Implementing data quality control for public washroom data with AWS.
Objective
The objective is to implement a complete Data Quality Control framework the use of AWS to ensure the public washroom dataset is clean, correct, and reliable. This framework will assist knowledgeable choice-making regarding the allocation of resources and enhancements to public offerings.
Background
The City of Vancouver's public washroom data is critical for city plans. However, like many datasets, it can be afflicted by problems inclusive of missing values, inconsistencies in statistics formats, and inaccuracies. These information problems can lead to flawed analysis and useless decision-making.
Scope
●	Data Profiling: Assessing the dataset's completeness, accuracy, and consistency.
●	Data Cleaning: Correcting mistakes, coping with lacking values, and standardizing data formats.
●	Data Validation: Implementing policies and tests to hold facts accuracy over the years.
●	Data Monitoring: Setting up tracking and indicators for ongoing tracking of facts best.
●	Data Protection: Ensuring steady get admission to and storage of the information.
Methodology
Phase I: Data Ingestion and Storage 
●	Ingest the public washroom dataset into an Amazon S3 bucket (vancity-pbwashroom-raw-tarun).
●	Configure IAM roles to control get admission to the S3 bucket.
●	Implement S3 versioning to hold data records.
Phase II: Data Profiling
●	Use AWS Glue DataBrew to profile the dataset.
●	Analyze data completeness, uniqueness, consistency, and accuracy.
●	Identify missing values and ability anomalies.
Phase III: Data Cleaning
●	Use AWS Glue DataBrew to smooth the dataset based on profiling consequences.
●	Handle lacking values and use of appropriate techniques.
●	Standardise information codecs.
Phase IV: Data Validation
●	Implement validation policies for the usage of AWS Glue and Amazon Athena.
●	Ensure data integrity and accuracy.
●	Check for adherence to predefined standards.
Phase V: Data Monitoring
●	Set up tracking the use of Amazon CloudWatch.
●	Track statistics, high-quality metrics and pipeline overall performance.
●	Implement alerts for any deviations from expected quality levels.
Phase VI: Data Protection
●	Implement security features with the use of IAM and KMS.
●	Control access to data and encrypt data at rest and in transit.
Tools and Technologies
Amazon S3: For storing raw and processed records.
AWS Glue DataBrew: This is used to profile and cleanse the data.
AWS Glue: For ETL processes and data validation.
Amazon Athena: For querying and validating data.
Amazon CloudWatch: For monitoring data quality and pipeline performance.
IAM (Identity and Access Management): For secure access control.
KMS (Key Management Service): For data encryption.
Deliverables
●	A clean and validated dataset stored in Amazon S3.
●	A data quality report detailing the metrics and any troubles identified.
●	A data quality monitoring dashboard.
●	Documentation of the data quality control techniques.
Timeline
Week 1: Data ingestion and storage setup in Amazon S3.
Week 2: Data profiling using AWS Glue DataBrew.
Weeks 3-4: Data cleansing and transformation using AWS Glue DataBrew.
Week five: Data validation using AWS Glue and Amazon Athena.
Week 6: Data tracking setup using Amazon CloudWatch.
Week 7: Implementation of data protection measures.

