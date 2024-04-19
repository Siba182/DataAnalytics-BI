# DataAnalytics-BI

<details>
<summary> Week 1 </summary>
<br>


 **What is Data Analytics** 
 - The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization. This involves several key responsibilities and skills.

**1. Data Collection and Preparation:**
- Sourcing data from various channels, including databases, spreadsheets, and external sources,
- Cleaning and organizing the data to ensure it is accurate, consistent, and ready for analysis.


**2. Data Analysis:**
- Employing statistical methods, machine learning techniques, or other analytic tools to interpret data,
- Identifying trends, patterns, and correlations that might not be immediately obvious.


**3. Data Visualization and Storytelling:**
- Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,
- Articulating findings in a compelling narrative to communicate the significance of the data to stakeholders.

**4. Decision Support:**
- Making recommendations based on data-driven insights to help guide business decisions,
- Providing context around the data, including potential implications and future trends.

**5. Collaboration and Communication:**
- Working closely with other departments, such as marketing, finance, and operations, to understand their data needs and provide insights,

- Effectively communicating complex data findings in a clear and concise manner to non-technical stakeholders,

**6. Continuous Learning and Adaptation:**
- Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.
- Adapting to new types of data and analytical methods as the organization's needs evolve.


Analytics is made possible by modern data, storage, and computing capabilities.

**The Analytics Process**
- Data Acquisition
- Cleaning and Manipulation
- Analysis
- Visualization
- Reporting and Communication


**The Analytics Process is Iterative**
While we describe the steps of the analytics process as a series of sequential actions, it is more accurate to think of them as a set of interrelated actions that may be revisited frequently while working with a dataset.


**Analytics Techniques**
- Descriptive Analytics
- Predictive Analytics
- Prescriptive Analytics

</details>

<details>
<summary> Week 2 </summary>
<br>

**Exploring Data Types**
All columns in a table or set does represent a particular data type


**Tabular Data**
- Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic.
- Each column represents a uniquely named field within a table, also called a variable, about a single characteristic
- The contents of each column contain values for the data element as defined by the column header.

**Structured Data Types**
- is tabular in nature and organized into rows and columns. Structured data is what typically comes to mind when looking at a spreadsheet.
- With clearly defined column headings, spreadsheets are easy to work with and understand
- In a spreadsheet, cells are where columns and rows intersect.


**Character**
- The character data type limits data entry to only valid characters
- Characters can include the alphabet that you might see on your keyboard, as well as numbers

**Alphanumeric** is the most widely used data type for storing character-based data. As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters.


**Character Sets**


 **Numeric** 
 - When numbers exclusively make up values for a data attribute, numeric becomes the data type of choice


**Whole Numbers**
- The integer, and all its subtypes, are for storing whole numbers.

**Rational Numbers**
- In all its variants, the numeric data type is for rational numbers that include a decimal point. As with the integer family of data types, each database vendor has its implementation nuances. 

![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/6156f6b8-f376-4f89-9e86-4ba79a3b7e1d)


![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/a690628b-80f3-4083-a4cf-a834dd13f546)


**Date and Time**
- Gathered together under the broad category of date, day of year and time of day are data elements that appear with great frequency

![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/6de62299-4be5-428e-9bbd-0402a64e067c)


**Currency**
![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/47530385-8390-4c4e-a247-60c42cce9819)



**Strong And Weak Typing**

**Strong** 
- Strong typing is when technology rigidly enforces data types. A database column defined as numeric only accepts numerical values. You will get an error if you attempt to enter characters into a numeric column.


**Weak**
- Weak typing loosely enforces data types. Spreadsheets use weak typing to help make it easier for people to accomplish their work. Spreadsheets default to an “automatic” data type and accommodate practically any value.





**Unstructured Data Types**
- While much of the data we use to record transactions is highly structured, most of the world's data is unstructured. Unstructured data is any type of data that does not fit neatly into the tabular model.

- Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses.


**Binary**
- It supports any type of digital file you may have, from Microsoft Excel spreadsheets to digital photographs like audio, image and video data 

**Audio**
- Audio data can come from a variety of sources. Whenever you interact with a customer service agent and hear “this call may be recorded for quality assurance purposes,” your conversation is probably being recorded and stored for later analysis

**Images** 
- Each digital picture is a piece of unstructured data. 

**Videos**
- As is the case with audio data, the resolution has a significant impact on the storage a video consumes. Video duration is also another factor that impacts storage size.
  
**Large Text**
![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/3fe7dc52-d530-4424-b581-49fb0866a926)


**Catagories of Data**


**Quantitative vs Qualitative Data**

**Quantitative** - data consists of numeric values. Data elements whose values come from counting or measuring are quantitative

**Qualitative** - data consists of frequent text values. Data elements whose values describe characteristics, traits, and attitudes are all qualitative



 **Discrete vs. Continuous Data**
 
  **Discrete** 
  - data is that it represents measurements that can't be subdivided. You may intuitively think of discrete data as using whole numbers, but that doesn't have to be the case.
  - useful when you have things you want to count


**Continuous**
- Instead of counting, when you measure things like height and weight, you are collecting continuous data.
  
- continuous data typically need a decimal point.


**Categorical Data**
- Text data with a known, finite number of categories is categorical.
- You can also use categories to enforce data validation when someone is first entering data.


  **Dimensional Data**
  - Dimensional modeling is an approach to arranging data to facilitate analysis.
  - Dimensional modeling organizes data into fact tables and dimension tables
  - Fact tables store measurement data that is of interest to a business
  - A table holding appointment data would be called a fact table. Dimensions are tables that 
     contain data about the fact
  


**Common Data Structures**

**Structured Data**
- Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows. Data is consistent when all entries in a column contain the same type of value. This method of organization facilitates aggregation.


**Unstructured Data**
- Unstructured data is qualitative, describing the characteristics of an event or an object. Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data. There is very little that is common about different kinds of unstructured data


**Semi-Structured Data**
- Semi-structured data is data that has structure and that is not tabular. Email is a well-known example of semi-structured data. Every email message has structural components, including recipient, sender, subject, date, and time. However, the body of an email is unstructured text, while attachments could be anything type of file.




**Common File Formarts**
- Common file formats facilitate data exchange and tool interoperability.

**Text Files**
- Text files are one of the most commonly used data file formats. As the name implies, they consist of plain text and are limited in scope to alphanumeric data

When a file is comma-delimited, it is known as a **comma-separated values (CSV)** file

Similarly, when a file is tab-delimited, it is called a **tab-separated values (TSV)** file.


**Fixed-Width Files**

**JavaScript Object Notation** 
- JSON is an open standard file format, designed to add structure to a text file without incurring significant overhead
- One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages


**Extensible Markup Language (XML)**
- is a markup language that facilitates structuring data in a text file
- While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags
- Tags describe a data element and enclose each value for each data element.

**HyperText Markup Language (HTML)**
- is a markup language for documents designed to be displayed in a web browser
- HTML pages serve as the foundation for how people interact with the World Wide Web.
- HTML is a tag-based language


**Chapter 3**

**Relational Databases** 
- a database structured to recognize relations between stored items of information.

**Benefits**
- **Atomicity** defines elements that make up a complete transaction.
- **Consistency** defines rules for maintaining data integrity following a transaction.
- **Isolation** keeps the effects of transactions invisible to others so they don't contend with one another.
- **Durability** ensures data changes become permanent after each committed transaction.


**Relational Model**
- header corresponds to the name of an entity
- Each of these entities becomes a separate table in the database, with a column for each attribute.
- Each row represents an instance of the entity
- The power of the relational model is that it also allows us to describe how entities connect or relate, to each other.


**Entity Relationship Diagram**
- is a visual artifact of the data modeling process
- it shows the connection between related entities
-  A relationship is a connection between entities
-  The symbols adjacent to an entity describe the relationship.


**Cardinality**
- refers to the relationship between two entities, showing how many instances of one entity relate to instances in another entity

![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/5e155dbd-c385-4618-84d8-311559b2f819)


**Relationships**

**Unary relationship** - is when an entity has a connection with itself. For example, where a single manager has multiple employees
**Binary relationship** - connects two entities
**Ternary relationship** - connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price



**Relational Databases**
- are pieces of software that let you make an operational system out of an ERD
- You start with a relational model and create a physical design
- Relational entities correspond to database tables, and entity attributes correspond to table columns.


**Nonrelational databases**
- does not have a predefined structure based on tabular data
- The result is a highly flexible approach to storing data.
- the data types available in relational databases are absent
- you need to know more about the data itself to interact with it
- Data validation happens in code, as opposed to being done in the database.

**Key-value** - database is one of the simplest ways of storing data. Data is stored as a collection of keys and their corresponding values. A key must be globally unique across the entire database. 


**Document** - is similar to a key-value database, with additional restrictions. In a key-value database, the value can contain anything. With a document database, the value is restricted to a specific structured format


**Column-family** databases use an index to identify data in groups of related columns

**Graph** databases specialize in exploring relationships between pieces of data




**Databases Use Cases**

**Online Transactional Process (OLTP)**
- OLTP systems handle the transactions we encounter every day
- Example transactions include booking a flight reservation, ordering something online, or executing a stock trade


**Normalization**
**First Normal Form (1NF)** - is when every row in a table is unique and every column contains a unique value.

**Second normal form (2NF)** starts where 1NF leaves off. In addition to each row being unique, 2NF applies an additional rule stating that all nonprimary key values must depend on the entire primary key

**Third normal form (3NF)** builds upon 2NF by adding a rule stating all columns must depend on only the primary key.



**Online Analytical Processing**
- OLAP systems focus on the ability of organizations to analyze data.
- While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different.


**Schema Concept**

**Database** 
- Designed to capture and record data
- Live, real--time data
- Data stored in tables with column and rows
- Data is highly detailed
- Flexible schema

**Data Warehouse**
- Designed for analytical processing
- Data is refreshed from source systems - stores current and historical
- Data is summarised
- Rigid schema - hoe data is organized

**Data Lake**
- Designed to capture raw data (structured, semi-structured and unstructured)
- Made for large amounts of data
- Used for ML and AI in its current state or for Analytics with processing
- Can organised and put into Databases or Data Warehouses


**Dimensionality**
- Dimensionality refers to the number of attributes a table has.
- The greater the number of attributes, the higher the dimensionality.
- A dimension table provides additional context around data in fact tables

**Handling Dimensionality**
- There are multiple ways to design dimensions



**Data Acquisition Concepts**
To perform analytics, you need data. Data can come from internal systems you operate, or you can obtain it from third-party sources. 


**Integration**

**Extract, Transform, Load**
**Extract** - In the first phase, you extract data from the source system and place it in a staging area. The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible


**Transform** -  The second phase transforms the data. The goal is to reformat the data from its transactional structure to the data warehouse's analytical design

**Load** - The purpose of the load phase is to ensure data gets into the analytical system as quickly as possible



**Differences between ETL and ELT**
Extract, load, and transform (ELT) is a variant of ETL. With ELT, data is extracted from a source database and loaded directly into the data warehouse


Once the extract and load phases are complete, the transformation phase gets underway. One key difference between ETL and ELT is the technical component performing the transformation


 With ETL, the data transformation takes place external to a relational database, using a programming language like Python. ELT uses SQL and the power of a relational database to reformat the data.



 **Data Collection Methods**
 - Application Programming Interfaces (APIs)
 - Web Services
 - Web Scraping
 - Human-in-the-Loop
 - Surveys
 - Survey Tools
 - Observation
 - Sampling
 
 



**Working with Data**


**Data Manipulation**
When manipulating data, one of four possible actions occurs:

Create new data        - INSERT - Creates new data in an existing table
Read existing data.    - SELECT - Retrieves data from an existing table
Update existing data.  - UPDATE - Changes existing data in an existing table
Delete existing data.  - DELETE - Removes existing data from an existing table


**SQL Considerations**
The keywords in SQL are case-insensitive. However, the case-sensitivity of column names and values depend on the database configuration.


**Filtering**
- Filtering is a way to reduce the data down to only the rows that you need.
- To filter data, you add a WHERE clause to a query. Note that the column you are filtering on does not have to appear in the SELECT clause.

**Filtering and Logical Operators**
- A query can have multiple filtering conditions. You need to use a logical operator to account for complex filtering needs
- Using AND and OR

**Sorting**
- When querying a database, you frequently specify the order in which you want your results to return.
- The ORDER BY clause is the component of a SQL query that makes sorting possible


**Date Function**
- date columns are frequently found in OLAP environments. Date columns also appear in transactional systems. Storing date information about an event facilitates analysis across time.


**Logical Functions**
- When writing SQL, there are frequently many ways to write a query and create the same results. Another way to generate the output is by using the IFF logical function. 

 syntax:
IFF(boolean_expression, true_value, false_value)


**Aggregate Functions**
- Summarized data helps answer questions that executives have, and aggregate functions are an easy way to summarize data. Aggregate functions summarize a query's data and return a single value

![image](https://github.com/Siba182/DataAnalytics-BI/assets/60964130/07d44816-d1ec-4222-8c9f-9685905acbc8)



**System Functions**
- Each database platform offers functions that expose data about the database itself. One of the most frequently used system functions returns the current date.
- The current date is a component of transactional records and enables time-based analysis in the future. The current date is also necessary for a system that uses an effective date approach.
- System functions also return data about the database environment.


**Query Optimization**
- Writing an SQL query is straightforward. Writing a SQL query that efficiently does what you intend can be more difficult. There are several factors to consider when creating well-performing SQL.




**Chapter 4**

**Data Quality Challenges**

**Duplicate Data**
- Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system. 

**Redundant Data**
- While duplicate data typically comes from accidental data entry, redundant data happens when the same data elements exist in multiple places within a system. Frequently, data redundancy is a function of integrating multiple systems.


**Missing Values**
- Another issue that impacts data quality is the concept of missing values. Missing values occur when you expect an attribute to contain data but nothing is there. Missing values are also known as null values. A null value is the absence of a value. A null is not a space, blank, or other character


**Invalid Data**
- Invalid data are values outside the valid range for a given attribute. An invalid value violates a business rule instead of having an incorrect data type. As such, you have to understand the context of a system to determine whether or not a value is invalid


**Nonparametric Data**
- Nonparametric data is data collected from categorical variables
- Sometimes the categories indicate differentiation, and sometimes they have a rank order associated with them


**Data Outliers**
- A data outlier is a value that differs significantly from other observations in a dataset.
- With outliers, you need to understand why they exist and whether they are valid in the context of your analysis


**Specification Mismatch**
- A specification describes the target value for a component. A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values


**Data Type Validation**
- Data type validation ensures that values in a dataset have a consistent data type.



**Data Manipulation Techniques**
- There are several potential issues to be aware of and account for when working with data.


**Recoding Data**
- Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis
-  Recoding groups data into multiple categories, creating a categorical variable. A categorical variable is either nominal or ordinal.
- Nominal variables are any variable with two or more categories where there is no natural order of the categories, like hair color or eye color
-  Ordinal variables are categories with an inherent rank



**Derived Variables**
- A derived variable is a new variable resulting from a calculation on an existing variable.

**Data Merge**
- A data merge uses a common variable to combine multiple datasets with different structures into a single dataset
- Merging data improves data quality by adding new variables to your existing data


**Data Blending**
- Data blending combines multiple sources of data into a single dataset at the reporting layer.
- Data blending differs from ETL in that it allows an analyst to combine datasets in an ad hoc manner without saving the blended dataset in a relational databas


**Concatenation**
- Concatenation is the merging of separate variables into a single variable
- Concatenation is a highly effective technique when dealing with a source system that stores components of a single variable in multiple columns.

**Data Append**
- A data append combines multiple data sources with the same structure, resulting in a new dataset containing all the rows from the original datasets
-  When appending data, you save the result as a new dataset for ongoing analysis.


**Imputation**
- Imputation is a technique for dealing with missing values by replacing them with substitutes
- When merging multiple data sources, you may end up with a dataset with many nulls in a given column

Here are a few approaches an analyst can use for imputing values:

- **Remove Missing Data**:  With this approach, you can remove rows with missing values without impacting the quality of your overall analysis.
- **Replace with Zero**:  With this approach, you replace missing values with a zero. Whether or not it is appropriate to replace missing data with a zero is contextual. In this case, zero isn't an appropriate value, as a person's weight should be a positive number. In addition, replacing a zero in this case has an extraordinary impact on the overall average weight.
- **Replace with Overall Average**:  Instead of using a zero, you can compute the average Weight value for all rows that have data and then replace the missing Weight values with that calculated average.
- **Replace with Most Frequent (Mode)**:  Alternatively, you can take the most frequently occurring value, called the mode, and use that as the constant.
- **Closest Value Average**:  With this approach, you use the values from the rows before and after the missing values. For example, to replace the missing measurements for 2/13/2021 and 2/14/2021, take the values from 2/12/2021 and 2/15/2021 to compute the average.



**Reduction**
- Reduction is the process of shrinking an extensive dataset without negatively impacting its analytical value
- There are a variety of reduction techniques from which you can choose. 


**Dimensionality Reduction**
- One reduction technique is dimensionality reduction, which removes attributes from a dataset. Removing attributes reduces the dataset's overall size.

**Numerosity Reduction**
- which reduces the overall volume of data
- One way to reduce the volume of quantitative data is by creating a histogram. 



**Managing Data Quality**
There are many techniques you can use to improve data quality


**Circumstances to Check for Quality**
- There are numerous circumstances where it is appropriate to implement data quality control checks. Every stop along the data life-cycle journey can impact data quality. Errors during data acquisition, transformation, manipulation, and visualization all contribute to degrading data quality



**Automated Validation**
- Whether source data is machine- or human-generated, one way to prevent data entry mistakes from adversely impacting data quality is to automate data validation checks.


**Data Quality Dimensions**
- Six dimensions to take into account when assessing data quality are accuracy, completeness, consistency, timeliness, uniqueness, and validity.

**Data Quality Rules and Metrics**
- With an understanding of data quality dimensions, you need to consider how to measure each of them in your quest to improve overall quality

**Methods to Validate Quality**
- Numerous methods are available for validating data quality. These methods range from whether or not your data passes reasonable expectations to statistical methods that look for irregular patterns within your data

- Reasonable Expectations, Data Profiling, Data Audits, Sampling, Cross-Validation



**What is statistics**
- the collection and intepretation of data 

</details>




<details>
<summary> Week 3 </summary>
<br>

 **Data Analytics Tools**

 **Spreadsheets**
 - The spreadsheet is the most widely used tool in the world of analytics.
 - It is hard to imagine anyone who does not use spreadsheets as part of their work because they provide an intuitive way to organize our data into rows and columns.
 - Spreadsheet software is installed on pretty much every computer in the modern work environment, and web-based spreadsheets are freely available to anyone.


**Microsoft Excel**
- Microsoft Excel is the most commonly used desktop spreadsheet application.
- It is available as a component of the widely deployed Microsoft Office productivity suite and most modern knowledge workers have access to it.
- Excel then allows users to perform calculations and visualizations on their data


**Programming Languages**

**R**
- The R programming language is extremely popular among data analysts because it is focused on creating analytics applications

**Python**
- Python is arguably the most popular programming language in use today. Python is about the same age as R, but the major difference between Python and R is that Python is a general-purpose programming language

**Structured Query Language (SQL)**
- The Structured Query Language (SQL) is the language of databases. Any time a developer, administrator, or end user interacts with a database, that interaction happens through the use of a SQL command

SQL is divided into two major sublanguages:

- **The Data Definition Language (DDL)** is used mainly by developers and administrators. It's used to define the structure of the database itself. It doesn't work with the data inside a database, but it sets the ground rules for the database to function.
- **The Data Manipulation Language (DML)** is the subset of SQL commands that are used to work with the data inside of a database. They do not change the database structure, but they add, remove, and change the data inside a database.


There are three DDL commands that you should know:

- The **CREATE** command is used to create a new table within your database or a new database on your server.
- The **ALTER** command is used to change the structure of a table that you've already created. If you want to modify your database or table, the ALTER command lets you make those modifications.
- The **DROP** command deletes an entire table or database from your server. It's definitely a command that you'll want to use with caution!



There are also four DML commands that you should know:

- The **SELECT** command is used to retrieve information from a database. It is the most commonly used command in SQL as it is used to pose queries to the database and retrieve the data that you're interested in working with.
- The **INSERT** command is used to add new records to a database table. If you are adding a new employee, customer order, or marketing activity, the INSERT command allows you to add one or more rows to your database.
- The **UPDATE** command is used to modify rows in the database. If you need to change something that is already stored in your database, the UPDATE command will do that.
- The **DELETE** command is used to delete rows from a database table. Don't confuse this command with the DROP command. The DROP command deletes an entire database table, whereas the DELETE command just deletes certain rows from the table.




**Microsoft Power BI**
- Power BI is Microsoft's analytics suite built on the company's popular SQL Server database platform.
- Power BI is popular among organizations that make widespread use of other Microsoft software because of its easy integration with those packages and cost-effective bundling within an organization's Microsoft enterprise license agreement



The major components of Power BI include the following:

- **Power BI Desktop** is a Windows application for data analysts, allowing them to interact with data and publish reports for others.
- The **Power BI** service is Microsoft's software-as-a-service (SaaS) offering that hosts Power BI capabilities in the cloud for customers to access.
- **Mobile apps** for Power BI provide users of iOS, Android, and Windows devices with access to Power BI capabilities.
- **Power BI Report Builder** allows developers to create paginated reports that are designed for printing, email, and other distribution methods.
- **Power BI Report Server** offers organizations the ability to host their own Power BI environment on internal servers for stakeholders to access.


**AWS QuickSight**
- AWS QuickSight is a dashboarding tool available as part of the Amazon Web Services cloud offering
- This tool's power comes from the fact that it is available on a pay-as-you-go basis and its integration with the powerful data storage, data warehousing, machine learning, and artificial intelligence capabilities offered by the Amazon cloud.


**Tableau**
- Tableau is arguably the most popular data visualization tool available in the market today.
- The focus of this tool is on the easy ingestion of data from a wide variety of sources and powerful visualization capabilities that allow analysts and business leaders to quickly identify trends in their data and drill down into specific details.



**Qlik**
- Qlik is another popular SaaS analytics platform, offering access to cloud-based analytics capabilities.


The major products offered by Qlik include the following:

- **QlikView** is the company's original analytics platform that focuses on providing rapid insights.
- **Qlik Sense** is a more advanced platform providing more sophisticated analytics capabilities




**Understanding the Business Requirements**
- Reports and dashboards both summarize data for end users, but they distribute those summaries in different ways

- A **report** is a static electronic or physical document that reflects information at a given point in time.
-  A **dashboard** is an interactive visualization that encourages people to explore data dynamically.



-  a **pull approach**, you publish a report to a known location, like a web page, and let people know the frequency and timing of when the report updates. With this approach, people can go to the website when they want to use the report.

-  a **push approach**, the report is automatically sent to the appropriate people as it becomes available. When designing a push approach, you need to think through distribution considerations.

- **blended approach**, you inform people that the report is available while maintaining central control of the report itself 




**Understanding Report Design Elements**
- **Control** has to do with how you focus the attention of your audience. When someone encounters a dashboard for the first time, one of your goals is to deliver the pertinent information quickly.

- **Correctness** makes sure that your information is accurate and that there are no spelling mistakes. Pay close attention to correctness when using corporate names and logos.

- **Clarity** refers to selecting the right visualization tool for communicating your message, making sure the visualization is easy to interpret and visually crisp, and using fonts and sizes that are easy to read

- **Consistency** refers to using the same design and documentation elements throughout your report or dashboard to give your visualization a cohesive and complete feel.

- **Concentration** refers to using visuals to focus your audience's attention on the most relevant information without overwhelming them with details




**Report Cover Page**
- When developing a printed report, keep in mind that the first thing people see is the cover page. Since the cover page is the first thing a person sees, it is vital that it sets expectations about the observations and insights the reader will find within.


**Executive Summary**
- The executive summary provides an overview of the report's contents
- When crafting an executive summary, you should begin with the end in mind, summarizing crucial observations and insights.
- With time as an executive's most precious resource, the summary needs to convey the big ideas, while the body of the report details the analysis that led to those ideas


**Color Schemes**
-  color scheme is a limited selection of colors you use when creating a report or a dashboard
-  The first decision to make is whether you need to use a monochromatic color palette or have the flexibility to use more than one color
-  A monochromatic palette limits you to working with shades of a single color


**Layouts**
- The layout of a report or dashboard determines the arrangement of its component parts.
- It is crucial to consider approachability when thinking about the design.
- When developing the layout for a report, begin with a summary before diving into the supporting details.



**Fonts**
- When choosing a font style, pick one that is easy for people to read by avoiding ornate fonts
- In typography, a serif is a finishing detail for each letter in a typeface.
- A serif font style includes serifs (the curls), whereas a sans serif font style does not


**Graphics**
- Using graphics to present summary information is a practical choice, whether creating a report or developing a dashboard.
- As the saying goes, a picture is worth a thousand words, and visually conveying information with charts helps focus your audience's attention


**Corporate Reporting Standards**
- When developing any type of visualization, be mindful of any existing corporate reporting standards
- A style guide is a set of standards that drives consistency in communication.
- As a means of enforcing structure and consistency, style guides define the use of a variety of branding elements, including page layout, font selection, corporate color codes, logos, and trademarks. 


**Documentation Elements**
- People must trust the information in your visualizations.
- To help establish trust, you can incorporate documentation elements, including version numbers, reference data sources, and reference dates.
- Reference dates include the initial creation date, report run date, and data refresh date.


**Version Number**
- A version number is a numeric value that refers to a specific version of a report
- Version numbers help you keep track of changes to content and layout over time
- Reference data sources identify where data in the report originates.



**Reference Data Sources**
- Reference dates help people understand what to expect in terms of data recency.
- For example, if a report has a daily refresh cycle, the report run date helps people realize when the last data refresh date was. 
-  If they see that the refresh date is from a week ago, they know the report is missing a week's worth of data.



**Frequently Asked Questions**
- When developing a report or a dashboard, it is good to maintain a set of frequently asked questions (FAQs)
- A FAQ provides answers to people's most common questions.
- If the dashboard is available online, the FAQ can contain links to a glossary of unique terms, cross-references to other dashboards or reports, and contact information if there are additional questions.



**Appendix**
- When developing a report, use an appendix to include supporting details that are inappropriate to include in the main body.



**Understanding Dashboard Development Methods**


**Consumer Types**
- As with developing a report, it is crucial to identify who will be interacting with the dashboard you create
- C-level executives, with titles like chief executive officer and chief financial officer, have the most senior leadership positions in an organization.
-  Ensure you spend sufficient time identifying the key performance indicators (KPIs) crucial to senior leaders.
- A KPI is a metric that leadership agrees is crucial to achieving the organization's business objectives.
- Your organization may enter into a service level agreement (SLA) that describes the level of service an external vendor or partner can expect.


**Data Source Considerations**
- With clarity on what your dashboard needs to contain, you can proceed with identifying data sources.

- **Static data** is data that refreshes at some regular interval. A typical design pattern is for operational databases to update a data warehouse every night.

- **Continuous data**, also known as live data, typically comes directly from an operational database that people use to perform their daily duties

- The operational database provides a **live data feed** to the dashboard.



**Data Type Considerations**
- One thing that differentiates dashboards and reports is the fact that dashboards use software as the delivery mechanism.
- A **measure** is a numeric, quantitative value that a dashboard user is curious about


**Development Process**
- After you identify the data sources that will power your dashboard, you must turn your attention to developing the dashboard itself
- A **wireframe** is a blueprint for an application that defines the basic design and functions of a dashboard
- A **mock-up** extends a wireframe by providing details about the visual elements of the dashboard, including fonts, colors, logos, graphics, and page styles
- Incorporating wireframes, mock-ups, and a data story plan helps design an optimal **web interface**



**Delivery Considerations**
- Delivery considerations are a crucial part of the development process.
- Accounting for how you will refresh data is one of the many things to consider
- As you document their requirements and develop mock-ups, you need to determine whether people can subscribe to changes
- If subscription capability is a requirement, you need to have a system where people can opt-in to receive a notification when the underlying data changes.


**Operational Considerations**
- Once you have final approval, you proceed with developing the dashboard.
-  Similar to the design stage, make sure you include frequent opportunities to gather feedback
-  Once dashboard development is complete, test it thoroughly to verify its functionality.





**Exploring Visualization Types**
- You have many options for presenting information visually.
- It is vital to select a visualization type that appropriately conveys the story you are telling with your data in a compelling format.

**Charts**
- Charts are one of the foundational methods for visualizing both qualitative and quantitative data.
- There are many chart types, including line, pie, bar, stacked, scatter, and bubble charts


**Histogram**
- A histogram is a chart that shows a frequency distribution for numeric data.
- When performing an exploratory data analysis, create histograms for numeric data


**Maps**
- People frequently use maps to convey the location of a country, town, or individual address. 
- Maps are effective methods of orienting a person to a dataset
- There are numerous types of maps available to visualize data, including geographic, heat, and tree maps



**Waterfall**
- A waterfall chart displays the cumulative effect of numeric values over time.
- Waterfall charts facilitate an understanding of how a series of events impact an initial value.



**Infographic**
- An infographic, which gets its name from the words “information” and “graphic,” is a visualization that presents information clearly and concisely.
- Infographics minimize text in favor of visual elements to represent a topic in a format that is easy to understand


**Word Cloud**
- A word cloud is a visualization that uses shape, font size, and color to signify the relative importance of words.
- Word clouds are effective at visualizing free-form text responses. When creating a word cloud, you eliminate common words and conjunctions as they occur frequently and don't add value in terms of meaning. 



**Comparing Report  Types**
- There are several report types to choose from, depending on the information you want to convey.



**Static and Dynamic**
It is imperative to identify whether a report needs to be static or dynamic, as that difference impacts where you get your data. 

- **Static reports** pull data from various data sources to reflect data at a specific point in time. Suppose you work in a financial services firm and develop a five-year trend report for securities in the automotive sector, including Ford, Volkswagen, and Tesla.

- **Dynamic reports** give people real-time access to information. Using your five-year trend report to inform their analysis, a financial analyst in your company may want to execute a trade. For the analysts to determine the price they are willing to pay for a given security, they need access to real-time pricing data.


**Ad Hoc**
- **Ad hoc reports, or one-time reports**, use existing data to meet a unique need at a specific point in time. For example, suppose a hospital suffers an information security breach.



**Self-Service (On-Demand)**
- Self-service reports, or on-demand reports, allow individuals to answer questions that are unique to them at a time of their choosing.
- Instead of having data pushed to them, an attribute of self-service reporting is that individuals can pull a report at the time of their choosing


**Recurring Reports**
Recurring reports provide summary information on a regularly scheduled basis. Typically, recurring reports get delivered to their audience immediately after creation


There are numerous types of recurring **operational reports** that organizations use to monitor organizational health and performance. Operational reports typically show the KPIs for an organization.


From a **financial compliance reporting** standpoint, if you are a public company in the United States, you need to document annual compliance with the Sarbanes–Oxley Act (SOX). SOX compliance ensures that your company provides proof of accurate financial reporting.


From a **safety compliance reporting** standpoint, you need to comply with the Occupational Safety and Health Act (OSHA) in the United States to ensure the safety of your employees.


If you process health-related data in the United States, you must meet health **compliance reporting** obligations.


Organizations develop **risk compliance reports** to engender trust. For example, System and Organization Controls (SOC) reports document how an organization maintains its IT systems’ security, availability, and confidentiality in the information technology space. 



**Tactical and Research**
It is vital to identify whether the report you create is for tactical or strategic purposes.


- **Tactical reports** provide information to inform an organization's short-term decisions. Tactical information helps organizations accomplish initiatives like constructing a building, opening a manufacturing plant, or shipping products from one location to another.


- A **research report** helps an organization make strategic decisions. To achieve strategic objectives, an organization executes multiple tactical initiatives. Where a tactical report informs a decision with a finite scope and duration, research reports inform the development of an overarching strategy. The implications of strategic decisions are broad, including whether to acquire a competitor, how many component suppliers an organization needs, and whether to diversify and enter an entirely new market.
  
</details>



<details>
<summary> Week 4 </summary>
<br>

**Data Governance Concepts**
- Data governance is the set of policies, procedures, and controls that an organization develops to safeguard its information while making it useful for transactional and analytic purposes.


**Data Governance Roles**
- It takes multiple people fulfilling a variety of roles for data governance to thrive. A crucial concept relating to data governance is data stewardship
- Stewardship denotes looking after something, like an organization or property
  
-  **Data stewardship** is the act of developing the policies and procedures for looking after an organization's data quality, security, privacy, and regulatory compliance

-   An **organizational data steward**, or data steward, is the person responsible for data stewardship.

- A **data owner** is a senior business leader with overall responsibility for a specific data domain. A data domain, or data subject area, contains data about a particular operational division within an organization


- **A data custodian** is a role given to someone who implements technical controls that execute data governance policies. Data custodians are frequently information technology employees who configure applications, dashboards, and databases





**Access Permissions**
It is a best practice to use role-based access to grant people permission to access data.

- **Role-based access** means that instead of giving access to individual people, you grant access to the role they occupy
- A role-based access approach facilitates permissions maintenance and improves consistency


- The alternative to role-based access is **user-based access**, which assigns permissions directly to individuals
-  User-based access is a dangerous practice as it increases operational complexity and the potential for mistakes.




**Group Permissions**
- It's best to start by visualizing people within an organization when creating data access roles. An organization chart documents the reporting structure within an organization


**Data Use Agreements**
- A data use agreement (DUA) is a contractual document for transferring private data between organizations. 
- You should establish a DUA before sharing data with an outside party
- It is essential to understand the classification for each piece of data when crafting a DUA


**Security Requirements**
- With data access requirements in place, you need to determine the technical controls for protecting data
- In cryptography, encryption is the process of encoding data with a key so that only authorized parties can read it
- Data encryption is one of the fundamental components of data protection, as the data is unusable without the key to decrypt it.
- An encryption key is a series of letters, numbers, and symbols used during the encoding process to make data unreadable




**Storage Environment Requirements**
- There are many environments where data at rest exists, including local storage, a shared drive, and the cloud.
- Regardless of the storage environment, you need to encrypt all data at rest. Local storage is the storage media on an individual device, such as a hard drive in a laptop.


Encrypting local storage is straightforward, regardless of the operating system you use. The steps, visualized in Figure 11, are as follows:

- Create a password for encrypting the local storage.
- Determine the operating system.
- Use the encryption tool appropriate for the chosen operating system.







 
</details>
