# Data Fluency - Accessing Data

Data exists in a variety of different formats and styles. There is the classic structured data like a spreadsheet or a database that you and/or your team might have used. But more and more data known as unstructured data, such as multimedia sources of audio, image, or video are being built into machine learning models. It’s important to determine how your data might be stored, and then we’ll get into understanding what data looks like to you and your teams.

## Different data formats

When you think about the word "data"" does your mind go to a table of numbers? Or maybe you think about a particular graphic or data visualization that you saw recently online or in a magazine?

There are many other types of data that have begun to be analyzed with digital storage increasing dramatically over the past few decades. For example, images can be broken down into pixels with each pixel corresponding to a color value. Characteristics and trends in an image can be examined with data analysis and techniques such as image classification using a computer. For example, one could try to have a computer identify if an image is a “hyena” or a “dog.”

Text is another example of data that has become more prevalent with the popularity of social media, email, blog posts, and media organizations moving more and more content online. Entire books have also been analyzed using text mining techniques to examine how the sentiment of text has changed throughout the book. Sentiment analysis can be used to determine the attitude of characters in the text and how that changes over time. This is harder to do without the use of a computer often including careful note-taking manually and lacking precision and details. This can be done in a few seconds with powerful machine learning techniques on a computer.


Further analysis has become common with huge amounts of data such as audio or video files. Additionally with the mapping of the human genome, statistical analysis and tracking changes across the genes of multiple people has helped the medical and biological professions in ways once thought to not be possible. The intervention of data collection using computers has made this a burgeoning new field.

Data can also come in the format of spatial data. From a business perspective, these kinds of data can help one to identify the best place to open, for example, a restaurant given the other restaurants and customer trends in a given area.

## Sources of data

Publicly available data is often called “open data.” This can refer to data provided by a local, state, or national government, such as census or economic data. Social media also provides a way to interact with data that is available publicly. For example, one could look to see how a hashtag has trended over time with something like the Twitter API. An API is an application programming interface. It is a set of rules that gives how two different software programs should interact with each other. A text analyst could use the Twitter API programmatically to pull tweets related to the World Cup, for example, by tracking #worldcup over a particular time period.

Not all data is available publicly though. Data inside organizations may include financial information and projections. This data may not be available online freely due to considerations around competition and privacy. This data is often called “internal data.” This internality can refer to data that only you have access to, only your team has access to, or data within your organization that you have to request access to.

## Data types

Data can be categorized, sometimes roughly, into whether data is structured or unstructured and whether data is numeric or categorical.

Structured data is data stored in rows and columns. This is often the type of data shown in tables or in spreadsheets. It is organized in a predictable and standardized way. It is typically stored in spreadsheets or databases. This allows it to be easy to search, sort, analyze, and filter based on characteristics of a particular column or many columns. Examples of structured data are product inventory at a store, financial transactions at a bank, and customer records at a pharmacy.

Unstructured data is data that does not have a pre-defined structure. It does not fit nicely into a database and is frequently unorganized. This lack of structure makes it more difficult to search and analyze. Examples of unstructured data include a dump of emails over a time period at a company, social media posts in a given day, and videos on a site like YouTube.

The next categorization of data is classifying the data itself. Numeric data refers to quantities of a particular measurement. Categorical data refers to data that can be split into groups.

An example of numeric data could be the amount of fuel stored at a processing plant. This is also often called quantitative data. An example of categorical data could be the color of a set of cars produced by an automobile company. This is also often called qualitative data.

Determining what type of data is stored can help one to determine which type of analysis should be done. Numeric data can have calculations such as the average applied, whereas the average does not make sense to perform on qualitative data.

## Data managing

### Database basics

A database is an organized collection of data stored and accessed electronically. Databases make it easy to search, select, and sort through large amounts of data quickly and efficiently. There are many different types of databases, including relational databases, which store data in tables with rows and columns, and NoSQL databases, which store data in a more flexible format.

Relational databases are well-suited for structured data, such as customer information or financial records, while NoSQL databases are better for unstructured data, such as social media posts or log files. Database management systems (DBMS) are used to create, maintain, and interact with databases. Some examples of DBMSs include MySQL, Oracle, and Microsoft SQL Server.

Databases are used in a wide variety of applications, including online shopping, social networking, and data analytics. They are an essential component of modern information systems and play a vital role in many businesses and organizations.

Databases are often stored in larger systems known as data warehouses and data lakes. A data warehouse and a data lake are both used for storing large amounts of data, but they are designed for different purposes and have some important differences.

A data warehouse is a system used for storing and analyzing data from a variety of sources. It is designed to support fast query and analysis of the data, and is optimized for this purpose. Data warehouses are typically built using structured data and are used to support business intelligence and reporting needs. Some examples of data warehouses include:
  - Amazon Redshift: A cloud-based data warehouse service offered by Amazon Web Services (AWS).
  - Teradata: A data warehousing and analytics company that provides a range of data warehousing products and services.
  - Snowflake: A cloud-based data warehouse service that is designed to make it easy to analyze data using SQL and to integrate with a variety of other tools and services.
  - Oracle Exadata: A data warehousing and database server product offered by Oracle.
  - IBM Netezza: A data warehousing appliance offered by IBM.
  
A data lake is a storage repository that allows you to store large amounts of structured, semi-structured, and unstructured data at any scale. Data lakes are designed to be flexible and scalable, and can store a wide variety of data types. Data lakes are often used as a central repository for storing raw data that can be transformed and processed later, and are often used in big data and analytics applications. Some examples of data lakes include:
  - Amazon S3: A cloud-based data lake service offered by Amazon Web Services (AWS).
  - Hadoop Distributed File System (HDFS): The primary storage system used in the Apache Hadoop big data processing framework.
  - Google Cloud Storage: A cloud-based data lake service offered by Google Cloud.
  - Azure Data Lake: A data lake service offered by Microsoft Azure.
  - IBM Cloud Object Storage: A data lake service offered by IBM Cloud.

Many of the examples listed above for both data warehouses and data lakes are examples of data storage on the cloud. This refers to the data not being stored locally on a computer in your business, but rather on a remote server to be accessed over the internet.

To keep track of moving data around from one database to another in a data warehouse or data lake, a data pipeline is often used. It typically involves extracting data from a variety of sources, transforming it to fit the needs of different systems, and then loading it into those systems for further analysis or use. In addition to moving data across databases, data pipelines can be built using a variety of tools and technologies, and are used in a wide range of applications, such as real-time data processing and machine learning. They help organizations to efficiently and reliably move large amounts of data between systems, and to ensure that data is properly transformed and integrated for use by various applications.

To extract data from a database, the process of retrieval is often done and this is called to “query” the data. The standard language for doing this querying is called Structured Query Language (SQL). SQL is the standard language for interacting with relational databases, and is used to perform tasks such as:
  - Inserting, updating, and deleting records
  - Creating, modifying, and deleting tables and other database objects
  - Retrieving data from databases
  - Modifying the data in databases
  - Controlling access to the database
  - Setting permissions on tables and procedures

SQL is a powerful language for working with data, and is used in a wide variety of applications, including web applications, data analysis, and business operations.

### Main categories of data collection

It’s also important to think about processes for which data is also collected to be stored in these databases. There are five main categories of data collection:
  - Experimental
  - Observational
  - Simulation
  - Derived
  - Reference
  
Experimental data refers to data from lab equipment and under controlled conditions. This can be reproducible if procedures are carefully documented, but this can be expensive to replicate.

Observational data can be captured in real time such as with smart devices like an Apple Watch. It tends to not be reproducible because the surrounding environment changes and it is not done in a controlled setting. Surveys and behavioral observances usually result in observational data.

Simulation is kind of a mash up of both experimental and observational. It usually involves using the computer to replicate what an experiment might produce or building models to try to predict the future. We’ll come back to some of the dangers in how these models are reported with hurricane predictions with interpreting data.

Derived data refers to combining different data sources together by merging database tables, by converting textual data for evaluation in fields like natural language processing, and also by engineering new features. Feature engineering refers to making new columns in your data by combining some other columns in some usually mathematical way such as creating a ratio.

Reference data is just that. It means data that is used for looking up facts. The census and library catalogs are two such examples.

A particular data table in a database could have data collected in a variety of ways, but it’s important to always try to identify where and how a particular data point was gathered.

## Assessment/learning check questions

1. Which of the main categories of data management do you and your team(s) work with most often?
2. Where does your data live?
3. How is data shared with you/across your team(s)? Dashboards, raw, summaries, reports, something else?
4. Who might have relevant data for you?  
  a. How do you request access to this data?   
  b. What steps are needed to get it?  
5. How is your data archived for long term storage? How often is that data archived?
