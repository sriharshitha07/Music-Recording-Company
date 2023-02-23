## Music Recording Company

*Sa Re Ga Ma - When words fail,music speaks .*


This is a java-DBMS project for a music recording company.
we made the webpage using swing and added our backend database from postgresql. 
this webpage helps the company to maintain the artist details .


## Class Description
A **Java Project** with *PostgreSQL* as backend. 
* Package: **core**

  * **Driver.java** - **Driver code** *for the Application*
  * *Terminate.java - Terminates the JDBC Connections*

* Package: **databases**

  * *ConnectDB.java  - Connects the JDBC Client*
  * *GUILoginCheck.java - Validates the Login Credentials used at Start*
  * **QueryEvaluator.java**  - **Mainstream Query Processor** *which sends all JDBC requests*
  * #### Interfaces:

  * *dbDisplay.java  - Consists of SQL Queries as methods to perform Display Operations*
  * *dbInsert.java  - Consists of SQL Queries as methods to perform Insert Operations*
  * *dbUpdater.java  - Consists of SQL Queries as methods to perform Update Operations*
  * *RecordRemover.java  - Consists of SQL Queries as methods to perform Delete Operations*

* Package: **gui**

  * *GUIManager.java  - Handles the GUI for Load Animations*
  * *Login.java -  Handles the GUI for Initial Login Screen*
  * **StartAdmin.java**  *- **Core GUI Handler**. Manages the GUI for the Entire Application*
  * #### Interfaces:

  * *Messages.java  - Handles the Success/Fail messages Displayed in the Application*
  * *ResourcePaths.java  - Contains the Path to all the Resources used in the Application*



