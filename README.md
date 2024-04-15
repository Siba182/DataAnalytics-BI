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






</details>
