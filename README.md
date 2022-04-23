# Python coding tips


## RBDB

* Notebooks
    - Jupyter, Apache Spark, Databricks coud, RMD, Jupyter R, Apache Zeppelin
* Sharing data
    - Dropbox, GitHub, Jupyter NOtebook viewer

## DBMS
    - Python code connects to a DB using Python code written (for ex, on a Jupyter notebook), a web-based editor.  
    - Python code connects using API calls
    - API is a set of funtions that you can call to get access to some type of service (lib function calls)
    - To pass the SQL commands to the DBMS, an application program calls functions in the API, and it calls other functions in the API, and it in-turn calls other functions to retrieve query results/status info from the DBMS. 
###  DB and their corresponding API 
     ``` 
     Appln or DB            SQL API
     MySQL                  MySQL C API
     PostgreSQL             psycopg2
     SQL Server             dblib API
     Oracle                 OCI
     Java                   JDBC
     ```
   


