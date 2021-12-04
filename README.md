# Assessment
1. Clone the repository
    git clone https://github.com/spicoflorin/trg-assessment.git
2. Unzip https://github.com/spicoflorin/trg-assessment/blob/main/resources/data/2019-01.7z in the folder trg-assessment/resources/data
3. Execute command ./start-homework.sh
4. Step 3 start the Apache Zeppelin notebook server available on port 9080. If the port is not available, please modify the docker-compose.yaml and expose a free port. 
 Go to http://localhost:9080 
5. In the Zeppelin UI, open the trg-assessment notebook (http://localhost:9080/#/notebook/2GPY2C1BN)
6. First paragraph contains the ETL - loads the police data from csv file to rquested parquest file format . Run it with Shift+Enter
7. Second paragraph loads the parquet file into Spark Dataframe. Run it.
8. The KPIs will be in the next paragraphs,each of them details with their purpose
9. After the analysis, you might destroy the stack by calling ./detroy-homework.sh
