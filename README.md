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
1. Demonstrated the creation of an Azure SQL Server using SQL Server Authentication: <br/>
<img src="images/create-sql-server.png" height="80%" width="80%" alt="Demonstrating SQL Server Creation"/>
<br /><br />

2. Showcased how to import a pre-populated database by navigating the Azure Storage container setup and the SQL Server import feature: <br/>
<img src="images/import-database.png" height="80%" width="80%" alt="Showcasing Database Import Process"/>
<br /><br />

3. Explored network security configurations by hovering over firewall rules and disabling public network access to restrict IP-based access: <br/>
<img src="images/network-security.png" height="80%" width="80%" alt="Exploring Network Security Options"/>
<br /><br />

4. Connected to the database from a Virtual Machine to illustrate secure access via SSH and demonstrate data retrieval: <br/>
<img src="images/vm-database-access.png" height="80%" width="80%" alt="VM Database Access Demonstration"/>
<br /><br />

5. Showed how to apply Dynamic Data Masking to sensitive fields (e.g., phone number, email address) to protect data visibility for non-admin users: <br/>
<img src="images/dynamic-data-masking.png" height="80%" width="80%" alt="Applying Dynamic Data Masking"/>
<br /><br />

6. Demonstrated how data appears when masked by logging in as a non-admin user and retrieving masked fields: <br/>
<img src="images/masked-data-view.png" height="80%" width="80%" alt="Masked Data View"/>
<br /><br />

7. Navigated the auditing settings to demonstrate how logging access and modifications can be enabled with custom retention settings: <br/>
<img src="images/audit-logging.png" height="80%" width="80%" alt="Database Auditing Demonstration"/>
<br /><br />

8. Examined Microsoft Defender for SQL’s security recommendations to showcase proactive threat monitoring and improvement suggestions: <br/>
<img src="images/defender-for-sql.png" height="80%" width="80%" alt="Exploring Defender for SQL"/>
<br /><br />

9. Showed how to use Azure’s Data Classification feature to identify and categorize sensitive data within the database: <br/>
<img src="images/data-classification.png" height="80%" width="80%" alt="Data Classification Demonstration"/>
</p>
