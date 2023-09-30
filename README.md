# Big-Data-Modelling-and-Management
Two group projects for the Big Data Modelling and Management course of the Master's Degree in Data Science and Advanced Analytics at NOVA IMS.

The objective is to answer the questions included in the Jupyter Notebooks.
In the first project, a graph database was used and in the second project, a document based database.

# Project 1 (Neo4j): The Beer project
Project Description:

Explore the database via python neo4j connector and/or the graphical tool in the NEO4J webpage. Answer the questions.

# Project 2 (MongoDB): AirBnb Document Database
Project Description:

Congratulations! You have been successfully hired as the new Data Engineering and Management team in the AirBNB Business Intelligence department. The organization is undergoing restructuring as the performance of the previous teams was not believed to be satisfactory.

Before leaving their post, the head of the Data Modelling department left this note of identified issues.

Currently a lot of data related to AirBNB listings is all collected in the same document. While this has some advantages it has also caused issues. The query performance is known to be too slow, so some decisions on hybridization of data models are required. The previous team did not have experience in the application of patterns, which has been identified as a key area to improve performance through the enhancement of the data model. Indexes have also not been previously applied.

The AirBNB application use has been growing rapidly, especially the the number of reviews. Because of that we have been overwriting them regularly, but the business intelligence department will benefit from storing all the Reviews and analysing them over time.

Finally, there are some mistakes in the data collection : for instance, writing the same data multiple times, and assigning wrong timestamps for when transactions occurred. The new team will need to decide how to address these.

In your new role, you are expected to think about the database use case in each question, analyse all the information you have, how commonly is this query needed, how heavy will it be on reads and write etc. You should modify the database schema, where you deem appropriate, to optimise for the business use cases. To do so you should use all the tools you have learned in the lab and lectures, especially embedding and linking, indexes, and patterns. This can involve creating new fields, documents, and collections. Indicate which pattern you are applying and your reasoning for doing so in comments, remember to identify any duplication that is required and any risks of staleness.

Remember to think about the relevancy of all data that will be returned in each case and if this is needed or adding excessive time to return:
1. to streamline the data collection system;
2. to clean up the data and optimise what will be returned for each use case;
3. to use correct patterns to improve speed of typical queries;
4. to ensure that all departments receive correct and relevant information from the database;
5. to provide the data model schema to inform other departments of the changes.

Good practices in our company include:
1. all newly created fields have CAPITALIZED names;
2. all new queries function on the most updated version of the database (if you make multiple changes all your queries still work after the final changes);
3. for some of the queries you will likely want to change the database schema in some way. Each database transformation choice is properly documented using format:

TRANSFORMATION APPLIED: <NAME and DESCRIPTION OF TRANSFORMATION>

REASONING BEHIND: <WHY YOU DID IT>

EXPECTED RESULT: <WHAT IS THE (EXPECTED) RESULT OF RUNNING QUERIES GIVEN THIS TRANSFORMATION>
