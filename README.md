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



















</details>
