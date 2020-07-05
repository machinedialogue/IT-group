      We joined meeting through Google Meet.
      
      Test the latest features with SQL Server 2017 Developer Edition. Full-featured free edition.
      
      https://cloudblogs.microsoft.com/sqlserver/2019/01/21/test-the-latest-features-with-sql-server-2017-developer-edition/
      
      Free Download SQL Server Management Studio (SSMS):
      
      https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
      
      Then download sample database from Microsoft.com
      
      https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=tsql
      
      -     AdventureWorks installation and configuration. OLTP downloads. AdventureWorks2017.bak
      
      Create a directory under C:\drive C:\ITGroup>Copy file AdventureWorks2017.bak
      
      Connect SQL Server Management Studio
      
      Right Click Database and restore AdventureWorks2017.bak

      Expand Database. Choose AdventureWorks2017.bak expanded (+). 

      -     Expand Table, choose Person.Address. Right click and choose Select Top 1000 Rows
            
            /****** Script for SelectTopNRows command from SSMS  ******/
            SELECT TOP (1000) [AddressID]
            ,[AddressLine1]
            ,[AddressLine2]
            ,[City]
            ,[StateProvinceID]
            ,[PostalCode]
            ,[SpatialLocation]
            ,[rowguid]
            ,[ModifiedDate]
             FROM [AdventureWorks2017].[Person].[Address]
  
      Practice SQL tutorial:
      -     Specially Inner Join Syntax
      
            SELECT column_name(s)
            FROM table1
            INNER JOIN table2
            ON table1.column_name = table2.column_name;

to be continued ..........
