---
title: Create SPDocKit Query 
description: This section describes how to use the SPDocKit wizard to create a query report.
author: Iva Novoselic  
date: 25/5/2017  
---

This section describes how to use the SPDocKit Query wizard to create a query report. We will now create a query that will provide you with a list of all checked-out documents on a selected scope.

1. Go to Queries & Rules and click New Query from the Home ribbon.  
2. Type in the name of your query and select a query scope. The query scope defines the type of SharePoint objects that will be crawled for their properties in this report. Click Next to continue.  
3. Select the list fields you would like to include in this report. Read more about [supported query properties](#internal/get-to-know-spdockit/queries-and-rules-screen). Click Next to continue.  
4. Use the Up and Down arrows to choose and modify the order and sorting type. Click Next to continue.  
5. Choose whether you would like to manually execute this query or automatically execute it. Click Next to continue.

   * __Manual execution__ – you will have to run this query from the Home ribbon using the Run button every time you want to check whether there are any changes.
   * __Automatic execution__ – requires an active SPDocKit Service and a [defined schedule](#internal/get-to-know-spdockit/queries-and-rules-screen).

   If the SPDocKit Service is not running, a warning bar will appear. Click __Configure__ to enable the SPDocKit Service.  
6. Under Filters select the Checked Out To list property, click the underlined value “specific” and choose the Is Not Empty condition. Click Next to continue.  
7. Define the query targets. Depending on your selected query scope in the first step of this wizard, you can target an entire __web application, specific site collections, subsites, or lists and list items__. Each time the query is executed, it will list all files that are currently checked out to someone on the specified scope.

   If you have chosen the manual execution in the previous steps, you can skip this step – select the __Skip target selection; ask me on execution__ check box. You will be able to choose the desired scope each time you start the query. Click Finish to run your query.

   It is also possible to send the query results to specified email addresses in one of the three available formats: __XLSX, DOCX, PDF__. This will be sent for both manual and automatic execution, each time a query is executed.

8. Run this query right away or wait for the scheduled time for the query to run automatically, after which you can explore the results. Each time you or the SPDocKit Service executes a query definition, a history record is created. Click on the desired record and explore the query results by date.


#### Tips & tricks

SPDocKit comes with a couple of predefined manual queries grouped into two folders.

The __Samples__ folder contains following queries: __Checked Out Files__, __Document Libraries Without Check Out__, and __Document Libraries Without Versioning__. 

The __Audit Settings__ folder contains following queries: __Audit Log Trimming__, __Documents and Items__, and __Lists, Libraries, and Sites__.


If you wish to run them, you will just be required to select a query scope. Also, you can edit the query definitions to better suit your needs.

To learn more about the __Audit settings__ queries, please check out the [following article](#internal/how-to/queries-and-rules/create-audit-queries-and-rules/).