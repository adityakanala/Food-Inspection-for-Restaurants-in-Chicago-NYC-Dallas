# Food-Inspection-for-Restaurants-in-Chicago-NYC-Dallas
As a part of the Graduate course of Designing Advanced Data Architecture for Business Intelligence we are dealing with Food Establishment Inspections in three cities • Chicago • Dallas • New York

### Deliverables: Part 1<br>
• Get data from downloaded files from Open Data<br>
• Load data into Stage table(s) (stg_)<br>
• Select one for target database: MySQL, SQL Server<br>
• Follow Staging Guidelines<br>
• Perform data profiling<br>
• ***Stage Table***<br>
>>• Add DI_CreateDate – date & time row loaded<br>
• Add DI_WorkflowFileName – the file name of your Alteryx workflow<br>
• If any dates are stored as text, add a column where that text is converted to date<br>

### Deliverables: Part 2
• Identify Dimensions & Facts<br>
• Create a Dimensional Data Model (ER/Studio or Navicat)<br>
• Create DDL for any database being used in this class<br>
• Create schema in chosen database<br>
• Select one: MySQL, SQL Server

### Deliverables: Part 3
• Create data preparation workflow(s) to load data into Integration Schema<br>
• Load data<br>
• ***Stage Table***
• Add DI_CreateDate – date & time row loaded<br>
• Add DI_WorkflowFileName – the file name of your Alteryx workflow<br>
• All tables must have a surrogate key (SK)<br>
• Dates or Datetimes must be in date or datetime data type(s) not text<br>
>>• you can also have a date or datetime column in the text if that is how came from the source and there are errors in dates in source<br>
>
• Dates also must have a column representing a date SK i.e. YYYMMDD

###  Deliverables: Part 4
• Create BI dashboards in both<br>
• Power BI Desktop published in PBI Service<br>
• Tableau Desktop published in Tableau Online
