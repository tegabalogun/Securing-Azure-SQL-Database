<h1>Securing Azure SQL Database</h1>

<h2>Description</h2>
Demonstrated how to secure an Azure SQL Database by showcasing various security features, including Dynamic Data Masking, firewall rules, encryption, and role-based access controls. Used Azure Monitor and Defender for SQL to explore options for monitoring database activity and mitigating potential threats. This project highlights best practices for database security and the capabilities of Azure’s built-in security tools.

<h2>Languages and Utilities Used</h2>

- <b>SQL</b>
- <b>Azure SQL Database</b>
- <b>Azure Monitor</b>
- <b>Azure Defender for SQL</b>

<h2>Environments Used</h2>

- <b>Azure Cloud</b> - SQL Server on Azure

<h2>Program Walk-through:</h2>

<p align="center">
Created an Azure SQL Server using SQL Server Authentication: <br/>
<img src="images/create sql db"/>
<br />
<br />
Demonstrated how to import a pre-populated database from GitHub using the Azure import feature:  <br/>
<img src="images/Import db"/>
<br />
<br />
Connected to the database from a Virtual Machine to illustrate secure access via SSH and demonstrate data retrieval: <br/>
<img src="images/Secure connection to db"/>
<br />
<br />
Executed an SQL query to retrieve and display data from the database, showing sample output:
<img src="images/sql output"/>
<br />
<br />
Data output from the database: <br/>
<img src="images/db output"/>
<br />
<br />
Configured network security by disabling public network access to restrict exposure, and explored firewall rules for further restrictions: <br/>
<img src="images/Networing"/>
<br />
<br />
Applied Dynamic Data Masking on sensitive fields (e.g., phone number, email) to control data visibility: <br/>
<img src ="images/data masking"/>
<br />
<br />
Demonstrated masked data visibility by logging in as a non-admin user and retrieving masked fields: <br/>
<img src="images/masked date"/>
<br />
<br />
Showed the auditing settings, where database access and modification logging can be configured. Added a storage account as the log destination and set authentication to managed identity: <br/>
<img src="images/auditing"/>
<br />
<br />
Examined Microsoft Defender for SQL options to showcase proactive threat monitoring and recommendations (without enabling the feature):  <br/>
<img src="images/showcasing defender for cloud"/>
<br />
<br />
Explored Azure’s Data Classification and Discovery section, demonstrating recommended sensitivity classifications for columns (without applying changes): <br/>
<img src="images/data classification"/>
</p>




















