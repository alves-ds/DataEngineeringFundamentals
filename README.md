# DataEngineeringFundamentals
Files and notes about data engineering fundamentals

# Data engineering
## Simple definition: 
The process used to collect and validate quality data, which can be used by data analysts and data scientists. 
A bunch of techniques and procedures to turn available data into useful data.

# Data Pipeline
It's a way to move data from a local (origin) to a destination (a data warehouse or data lake, for example). In this process, the data are transformed and optimized, arriving in a state in which they can be analyzed and used for the development of business insights.
Pipeline it's a concept.

# Basic components of a data pipeline
- Origin
- Processing
- Destiny

# Pipeline ETL (extract, transform, load):
It's a type of data pipeline, but it is only a subprocess of a data pipeline. ETL is a term created in an era when the only destination was a data warehouse and the process was less complex. Today, ETL is a part of a greater data pipeline process.
A data pipeline can be created for batch data, streaming data (real time), or both.

# Questions to have in mind when planning a data pipeline:
1) What are the business requirements?
2) What final results are necessary?
3) Is the data available? What are the sources?
4) What is the format of the available data?
5) What is the expected growth of the data volume?
6) How much storage is necessary?
7) How much computational capacity is necessary?
8) Will we use batch data, streaming data, or both?
9) Do we have the technology to create the pipeline?
10) What technologies will be considered?
11) What are the service level agreements (SLAs)?
12) What are the costs of implementing and maintaining the pipelines?
13) What will be the destination of the pipeline?
14) How will the pipeline be monitored?
15) Will we use different pipelines together?
16) Will we create the pipelines locally, in the cloud, or both?

