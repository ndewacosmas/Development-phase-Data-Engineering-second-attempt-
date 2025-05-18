# Development-phase-Data-Engineering-second-attempt-
Project: Data Engineering -Development phases second attempt 


# Development-phase-Data-Engineering-
Project: Data Engineering -Development phases

This project consist of a batch processing data application for a data - intensive which include all process which govern the procedure of extracting the Data from Kaggle.com and transforming them into othe microservices which will be used for analysis and storage before transforming them to the viasualization in dashboard.

.The data are extracted from a set of CSV files containing student performance in United States of America which published in 6 year ago (https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data) which had more than 1,000,000 data sets.

. the processes the source of data are ggregating student performance in the range of score of marks to three subjects.

. the extracted of the data was loaded into the processed data to a database

. the machine learning before processing the data was coded and labeled

.the extracted data was to be updated every quarter according the application system.

. Programing language which used in all stages are pythons

. presents the processed and clusterized data in HTML web pages


**Application Architecture **
The application architecture is shown below
![BATCH DATA ARCHITECTURE PHASE 1 SECOND ATEMPTS](https://github.com/user-attachments/assets/44ab3ba7-1854-4c7c-8195-e8dc47003e94)


Architecture Implementation

The application is implemented by using three docker containers

.ETL refers the Extract Transformed and loaded in processing area, this container are used to extract data from sources and executed the ETL works by the use of the Python. this works is schedule to change the data every quarter by adding new data as updation of the system. references https://github.com/ndewacosmas/ETL-JOB-DETAILS/blob/main/README.md

. Database: the database which are used for the data analysis under this project are PostgreSQL database, according this project this database are used both for analysis and storage of the data.

.ML:is stand for machine learning, according this project machine learning are used to make data analysis also written in Python. this process is scheduleed to label the data and matipulate the table every quarter reference, https://github.com/ndewacosmas/ML-JOB-DETAILS/blob/main/README.md

.Visualization: according this project this area are used to visualize data to show the status of the work which are uploaded references https://github.com/ndewacosmas/Visualization-Job-Details/edit/main/README.md

**Containers Integration**
The project deployment leaverages Infrastructure as a Code via Docker compose with set dependencies for each containers.

. according this study it show that containers depend on the finished one container and start another cointainer, it mean that if the ETL is completed executed the the another container are started

.The status table is used to control the flow of execution between containers

.A docker network is set with the containers deployment, which allowing communication between containers

**How to execute**
before starting the execution the user must identify the type of 

.Docker

.Docker - compose

**steps**

in order to execute the application and verify the results, the following steps

1. open Github respository and then running by the use of the commang line

   https://github.com/ndewacosmas/Development-phase-Data-Engineering-/blob/main/README.md
   
3. all files on this project was created at the top of the github and this project wa conducted in the following links
   
5. https://github.com/ndewacosmas/Batch-Data-Processing-Architecture-Application-
   
7. https://github.com/ndewacosmas/Batch-Data-Processing-Architecture-Application-/blob/main/README.md

8. https://github.com/ndewacosmas/ETL-JOB-DETAILS/blob/main/README.md

9. https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data

10. https://github.com/ndewacosmas/ML-JOB-DETAILS/blob/main/README.md

11. https://github.com/ndewacosmas/Visualization-Job-Details/edit/main/README.md

12. https://github.com/ndewacosmas/Development-phase-Data-Engineering-/blob/main/README.md

according this project the links which are mention above it state the work of 

**ETL works**

**ML works**

**Visualization works**


and other relatied information.


https://github.com/ndewacosmas/Development-phase-Data-Engineerin


Project: Data Engineering 

Topic: Batch Data processing application system.

Under this project author was using the Data from Kaggle.com as a data sources, through file in a format of CSV.  The data which are extracted from the Kaggle.com was known as students-performance-in-exams which are published 6 years ago. references are   https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data



according to this project as structured in the phase one this project had four parts which are used to extract the data from the data sources, transform them to the processing part, then analysis the data and visualize the status and results of the processes data.



according the system which are proposed in the phase one it show that the data are extracted from source by the use of the microservices of ETL, ETL stand for Extract Transform and Load, this microservices are used to extract data from sources, transform them and load the data into another microservices for the processing. also according of this project ETL process hade a work of updating the data extracted every quarter. in general the programing language of this microservices are Python.

The works of the ETL was conducted into https://github.com/ndewacosmas/ETL-JOB-DETAILS/blob/main/README.md



according this project the second microservices of application system of the project are pre Processing processing microservices, under this area data which are ingested from was loaded here for the pre-processed and processed by the use of the PostgreSQL data bases and stored, this stages was started after the completion of the ETL stages. all process of the analysis of the data was using the Machine learning (ML).references https://github.com/ndewacosmas/ML-JOB-DETAILS/blob/main/README.md

According this projects the area which are used to monitoring the system are status of the application in all stages and this status are used to show where the system is what the difficult are faced by the system during the application.



according this project the author state that all status and results of all application was visualized on microservices of the visualization as a Dashboard.

This dashboard show the status and the results of the processed data by the use of the Machine learning (ML). References. https://github.com/ndewacosmas/Visualization-Job-Details/edit/main/README.md

Under this project author started by architecting the  concept of the system which show the pipeline of the movement of data from the sources and transferring to the area of the processessing and then visualizing the processed data into the Dashboard of the system.

The resources used to conduct this works was big in terms of the time i was using more time of conducting this work if compared with another work on my study, and in term of the technology under this project it make me to learn new technology of doing my work.

The problems which are Identified by the    author of this project are on the use of new technology and on the use of machine learning while machine learning is the out of the scope of the work.

The major risk which are Identified by the author of the this project is to use different technologies on answering the works and the benefit of this project will help to understand new technologies and area for improvement the use of Machine learning must be considered as a part of assignment 

author of this project is identified that status of the works are monitored by the use of the visualization of the data in the Dashboard.
