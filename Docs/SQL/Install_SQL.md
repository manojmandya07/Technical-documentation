# Installing SQL Server on Windows

SQL Server is a relational database management system (RDBMS) developed by Microsoft. SQL Server supports ANSI SQL, which is the standard Structured Query Language. However, SQL Server comes with its implementation of the SQL language, T-SQL (Transact-SQL). It is primarily designed and developed to compete with MySQL and Oracle databases.

## Before you begin

You must have completed the following tasks:

- Ensure that you have a windows machine or VM to install the SQL server.
- Dowloaded the SQL Server installation file for Windows. For more information refer to [SQL Server downloads site](https://www.microsoft.com/en-in/sql-server/sql-server-downloads)
- Installed the .Net Framework, 1GB of recommended memory, and NTFS system.

## Procedure

1. Open the downloaded .exe file.
   The installation wizard opens.   
2. Click the edition that you want to install.
3. Read the license terms and conditions and then click **Accept**.
4. Browse to choose the path for installation or enter the file path and then click **Install**.
   The installation package is downloaded first and then the installation will start. Once installation is completed successfully, the following window is displayed:
5. You can perform the following actions on the **Installation has completed successfully!** window:
   - **Instance name**: This is by default labeled as MSSQLSERVER.
   - **Connect now**: Click this button to open a separate command line window for connection testing of what we have just installed.The system will run by default 
     ‘select @@Version’ statement to confirm that we can connect to new MSSQLSERVER instance successfully.
   - **Customize**: Click this button to open the SQL Installation center to customize further and add feature other than which are there as a part of the BASIC 
     installation.
   - **Install SSMS**: Click this button to go to Microsoft SSMS download link. 
   - **Close**: Click this button to close the window.

## Result

You have successfully installed the SQL Server on Windows.