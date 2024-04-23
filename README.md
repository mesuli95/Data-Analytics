# Data-Analytics

<details>
 <summary> Week 1 </summary>
 
# Introduction to Data Analytics

* Analytics is at the heart of modern business. Virtually every organization collects large quantities of data about its customers, products, employees, and service offerings.
* Managers naturally seek to analyze that data and harness the information it contains to improve the efficiency, effectiveness, and profitability of their work.
* The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization. 
* This involves several key responsibilities and skills.

# Keys responsibilities of data analysts
# Data Collection and Preparation:

* Sourcing data from various channels, including databases, spreadsheets, and external sources,
* Cleaning and organizing the data to ensure it is accurate, consistent, and ready for analysis.

# Data Analysis:

* Employing statistical methods, machine learning techniques, or other analytic tools to interpret data,
* Identifying trends, patterns, and correlations that might not be immediately obvious.

# Data Visualization and Storytelling:

* Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,
* Articulating findings in a compelling narrative to communicate the significance of the data to stakeholders.

# Decision Support:

* Making recommendations based on data-driven insights to help guide business decisions,
* Providing context around the data, including potential implications and future trends.

# Collaboration and Communication:

* Working closely with other departments, such as marketing, finance, and operations, to understand their data needs and provide insights,
* Effectively communicating complex data findings in a clear and concise manner to non-technical stakeholders,
Continuous Learning and Adaptation:

# Continuous Learning and Adaptation

* Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.
* Adapting to new types of data and analytical methods as the organization's needs evolve.

# Analytics is made possible by:

* modern data, storage, and computing capabilities.

# Analytics process

* Data acquisition
* Cleaning & manipulation
* Analysis
* Visualisation
* Reporting and communication

# Analytics techniques

* Descriptive analytics, which answers the question, “What happened?”
* Diagnostic analytics, which answers the question, “Why did this happen?”
* Predictive analytics, which answers the question, “What might happen in the future?”
* Prescriptive analytics, which answers the question, “What should we do next?”

# Machine Learning, Artificial Intelligence, and Deep Learning

* Machine learning (ML) - is a subset of AI techniques. ML techniques attempt to apply statistics to data problems in an effort to discover new knowledge.
 Or, in other terms, ML techniques are AI techniques designed to learn.
* Artificial intelligence (AI) - includes any type of technique where you are attempting to get a computer system to imitate human behavior. 
 * As the name implies, you are trying to ask computer systems to artificially behave as if they were intelligent. Now, of course, it is not possible for a modern computer to function at the level of complex reasoning found in the human mind, but you can try to mimic some small portions of human behavior and judgment.
* Deep learning - is a further subdivision of machine learning that uses quite complex techniques, known as neural networks, to discover knowledge in a particular way. It is a highly specialized subfield of machine learning that is most commonly used for image, video, and sound analysis.

# Data gorvanance

* Data governance programs ensure that the organization has high-quality data and is able to effectively control that data,

# Data analytics tools

* Software helps analysts work through each one of the phases of the analytics process.
* These tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data.
* They also provide invaluable assistance in reporting and communicating results.

# Data element

* A data element is an attribute about a person, place, or thing containing data within a range of values.
*  Data elements also describe characteristics of activities, including orders, transactions, and events.

# Data type

* A data type limits the values a data element can have. 
* Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic. Each column represents a uniquely named field within a table, also called a variable, about a single characteristic. The contents of each column contain values for the data element as defined by the column header

# Structured data

* Structured data is tabular in nature and organized into rows and columns. Structured data is what typically comes to mind when looking at a spreadsheet. With clearly defined column headings, spreadsheets are easy to work with and understand. In a spreadsheet, cells are where columns and rows intersect.

# Character data

* The character data type limits data entry to only valid characters. Characters can include the alphabet that you might see on your keyboard, as well as numbers. Depending on your needs, multiple data types are available that can enforce character limits.

# Alphanumeric

* Alphanumeric is the most widely used data type for storing character-based data. As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters.
* The alphanumeric data type is ideal for storing product stock-keeping units (SKUs).
* It is common in the retail clothing space to have a unique SKU for each item available for sale. If you sell jeans, you may stock products from Armani Jeans, Diesel, Lee Jeans, Levi's, and Wrangler.
* Tracking inventory at the SKU level allows you to manage availability in your online and in-store systems, all courtesy of the alphanumeric data type.

# Data type names

* Char
* Varchar2
* Varchar
* CLOB
* Varchar(max)
* LONGTEXT
# Character Sets

* When considering alphanumeric and text data types, you need to think about the character set you are using to input and store data when using a database. Databases use character sets to map, or encode, data and store it digitally. The ASCII encoding standard is based on the U.S. English alphabet.

# Numeric

* When numbers exclusively make up values for a data attribute, numeric becomes the data type of choice. This data type appears to be simple and obvious based on its name. As seen with the character data type, implementation nuances about numeric are essential to understand. Databases accommodate two types of numeric data types: integer and numeric.

# Whole numbers 

* The integer, and all its subtypes, are for storing whole numbers. As seen with the character family of data types, implementation differences exist across databases.
* In computer science, flags indicate whether something is on or off, or if a function has completed successfully. To show something is on, 1 or TRUE is used. For a value of off, 0 or FALSE is used.
* The bit data type is intended for storing the status of a flag. Note also that the value ranges for smallint and shortinteger are identical.
* The same is true for int and integer, as well as bigint and longinteger. Although the data types have different names, their functionality is equivalent.

# Rational numbers

* In all its variants, the numeric data type is for rational numbers that include a decimal point. As with the integer family of data types, each database vendor has its implementation nuances.
* Realizing that data types are inconsistently named across databases, you need to consider the ultimate range of values a given data element handle.
* All the data types in Table 2.4 store numbers to a configurable number of significant digits.
* There are scientific use cases that require an even greater number of significant digits; additional numeric data type variants exist to accommodate that need.

# Date and time

* For example, suppose you operate a veterinary clinic and need to store birth date information for pets. In that case, you need to store the year, month, and day. With those three components of date, you can effectively administer medication and determine when to schedule annual veterinary appointments.
* There are many occasions when it is more appropriate to include time, in addition to the day, month, and year. For instance, consider package tracking information for companies like FedEx, United Parcel Service, or DHL. Consumers want to know where a specific package is up to the minute.
* The company itself may need second-level details to optimize labor, infrastructure investments, and route planning.

# Currency

* Many people use spreadsheets to manage their finances. Organizations typically use enterprise-scale software for the same purpose, with the data residing in a database.
* The column headings indicate what each column contains. The currency symbols in each cell tell the reader what the data represents, even if the column headings have scrolled off the screen.

# Strong and weak typing

* Data types define values placed in columns. Strong typing is when technology rigidly enforces data types.
* Databases, discussed in Chapter 3, use strong typing. A database column defined as numeric only accepts numerical values.
* A database column defined as numeric only accepts numerical values. You will get an error if you attempt to enter characters into a numeric column.

# Unstructured data

* Unstructured data is any type of data that does not fit neatly into the tabular model.
* Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses.
* Analyzing unstructured data creates a wealth of information and insight.

# Types of unstructured data

  # Binary

  * Binary data types are one of the most common data types for storing unstructured data.
  * It supports any type of digital file you may have, from Microsoft Excel spreadsheets to digital photographs.
  * When considering which binary data type to use, file size tends to be the limiting factor. You need to select a data type that is as large as the largest file you plan on storing.
  * Databases offer a much more sophisticated collection of data types for storing binary data.
     
  # Audio

  * Audio data can come from a variety of sources. Whenever you interact with a customer service agent and hear “this call may be recorded for quality assurance purposes,” your conversation is probably being recorded and stored for later analysis.
  * The impact of capturing, storing, and analyzing audio data has led to the development of avalanche detection systems.
  * These systems listen for and detect the acoustic characteristics of an avalanche. With real-time notification capabilities, these systems reduce the time it takes for emergency services to respond and alert hikers to treacherous conditions.
  *  In order to ingest audio data into a system and make it available for processing, data is first captured via a microphone.
  *  The data is then digitized and stored. Audio can be stored in its raw form, which consumes the most storage space.
  *  Alternatively, it can be encoded with a compression algorithm to reduce the amount of space required. Regardless of if it is in raw or compressed form, storing audio requires a data type designed to handle raw binary data.

 # Images

 * As the use of image data grows, understanding how it is stored is vital for the modern data analyst.
 * Resolution is the most significant factor that governs how much space is required to store an image.
 * The greater the resolution, the more detail an image contains, and the more storage space it needs.

 # video

 * As is the case with audio data, the resolution has a significant impact on the storage a video consumes.
 * Video duration is also another factor that impacts storage size.
 * We see that every minute of video is equivalent to over 50 individual images, or more than 200 minutes of audio.

 # Large text 

 * I got to outline that data types names differ across vendor products

# Categories of data

  # Quantitative data
  
  * Regardless of structure, data is either quantitative or qualitative. Quantitative data consists of numeric values. Data elements whose values come from counting or measuring are quantitative.
  * Quantitative data answers questions like “How many?” and “How much?” Qualitative data consists of frequent text values.
  * example: the Height and Weight columns are quantitative

# Qualitative data

 * Qualitative data answers questions like “Why?” and “What?”
 * Example Pet Name, Animal Type, and Breed Name are all qualitative.

# Discrete vs Continuous data

 # Discrete 
 
 * A helpful way to think about discrete data is that it represents measurements that can't be subdivided.
 * Another way to think about it is that discrete data is useful when you have things you want to count.
 * For example, a veterinary clinic may be interested in the number of dogs and cats under its care.

# Continuous data

*  Continuous data typically need a decimal point,
*  Examples of continuous data are average weight and average height.
*  Qualitative data is discrete, but quantitative data can be either discrete or continuous data.

# Catagorical data

* Text data with a known, finite number of categories is categorical.
* When considering an individual data element, it is possible to determine whether or not it is categorical.
* Animal Type is a good example of categorical data.
* One of the reasons text files are so widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software.

# Dimentional data

* Dimensional modeling is an approach to arranging data to facilitate analysis. Dimensional modeling organizes data into fact tables and dimension tables.
* Fact tables store measurement data that is of interest to a business.
* Dimensions are tables that contain data about the fact.
* Dimensional data contains groupings of individual attributes about a given subject.


# Common data structures
In order to facilitate analysis, data needs to be stored in a consistent, organized manner. When considering structured data, several concepts and standards inform how to organize data. On the other hand, unstructured data has a wider variety of storage approaches.

# Structured data

* Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows.
* Data is consistent when all entries in a column contain the same type of value.
* This method of organization facilitates aggregation
* However, structured data does not translate directly to data quality

# Data entry error

* Just as there is an expectation that the values in a given column are consistent, it is a convention that each row contains data about a single record.
* It is a best practice to specify a key that uniquely identifies all values for a given row.
* Once again, nothing structural prevents a person from incorrectly putting data about Thor into Alexander's row. However, the intent is that each row's data pertains to a single animal.

#  Unstructured data

* Unstructured data is qualitative, describing the characteristics of an event or an object.
* images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data.
* There is very little that is common about different kinds of unstructured data. Since the data is highly variable, its organizational and storage needs are different from structured data.
* Unstructured data also represents a significant opportunity. A Forbes study shows that over 90 percent of businesses need to manage and derive value from unstructured data.
* Machine data is a common source of unstructured data. Machine data has various sources, including Internet of Things devices, smartphones, tablets, personal computers, and servers.
* As machines operate, they create digital footprints of their activity.
* This data is unstructured and can identify machine-to-machine interaction.
* Although some may think of machine data as digital exhaust, it is a treasure trove just waiting to be exploited by organizations.
* A wide variety of technologies has emerged to facilitate the storage of unstructured data.
* Operationally, these technologies are similar to how a key in a tabular dataset identifies its associated values.
* With unstructured data, the key is a unique identifier, whereas the value is the unstructured data itself.

# Semi-structured data 

* Semi-structured data is data that has structure and that is not tabular.
* Email is a well-known example of semi-structured data. Every email message has structural components, including recipient, sender, subject, date, and time.
* However, the body of an email is unstructured text, while attachments could be anything type of file.
* The need to make semi-structured data easier to work with has led to the emergence of semi-structured formatting options.
* These formatting options use separators or tags to provide some context around a data element. Let's explore common file formats for transporting semi-structured data.

# Common file formats
Common file formats facilitate data exchange and tool interoperability. Several file formats have emerged as standards and are widely adopted.

# Text file 

* Text files are one of the most commonly used data file formats. As the name implies, they consist of plain text and are limited in scope to alphanumeric data.
* One of the reasons text files are so widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software.
* Whether you are using a Microsoft Windows desktop, an Apple MacBook, or a Linux server, you can easily open a text file. Text files are also commonly referred to as flat files.
* When machines generate data, the output is commonly stored in a text file.
* A unique character known as a delimiter facilitates transmitting structured data via a text file.
* The delimiter is the character that separates individual fields.
* A delimiter can be any character. Over the years, the comma and tab grew into a widely accepted standard.
* Various software packages support reading and writing delimited files using the comma and the tab.
* In addition, many coding languages have libraries that make it easy to write comma- or tab-delimited files.
* When a file is comma-delimited, it is known as a comma-separated values (CSV) file.
* Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.

# Fixed-width files

* Before it was common to use delimited files with variable-length columns, flat files were fixed-width.
* Fixed-width files are more laborious to create since they require a few extra steps.
* The first row in a fixed-width file describes the column names.
* For the data rows, you first need to determine the maximum length of each column.
* Then, you must pad values that are shorter than the maximum length.
*  For numeric fields, you accomplish padding by prepending a leading zero. For alphanumeric or text fields, this is done by prepending or appending spaces.

# JavaScript Object Notation (JSON)

* JavaScript Object Notation (JSON) is an open standard file format, designed to add structure to a text file without incurring significant overhead.
* One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages.
* Languages such as Python, R, and Go have libraries containing functions that facilitate reading and writing JSON files.

# Extensible Markup Language (XML)

* Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file.
* While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags.
* Tags describe a data element and enclose each value for each data element. While these tags help readability, they add a significant amount of overhead.

# HyperText Markup Language (HTML)

* HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser.
* HTML pages serve as the foundation for how people interact with the World Wide Web.
* Similar to XML, HTML is a tag-based language.

# Consider the values of what you will store before selecting the data type

* Data types are used to store different kinds of values. When dealing with numeric information, the best option is a numeric data type that can accommodate decimals.
* For sequences of whole numbers, an integer data type is a good choice. Be wary of using currency-specific data types—that can lead to calculation errors.
* For text values, the alphanumeric data type is the optimal choice.
* When dealing with dates, you will want to consider whether you need to store the time as well.
* For binary data, including audio, video, and images, you should use a BLOB data type.

</details>
<details>
 <summary> Week 2 </summary>

# The relational model

*  The relational model builds on the concept of tabular data.
*  In the relational model, an entity contains data for a single subject.
*  When creating an IT system, you need to consider all the entities required to make your system work.
*  You can think of entities as nouns because they usually correspond to people, places, and things.

# Entity

* The header corresponds to the name of an entity, look at the rows of the Person entity.
* Each row represents an individual attribute associated with a person.
* Each of these entities becomes a separate table in the database, with a column for each attribute.
* The power of the relational model is that it also allows us to describe how entities connect or relate, to each other. 

# Entity relationship diagram

* The entity relationship diagram (ERD) is a visual artifact of the data modeling process.
* A relationship is a connection between entities. The symbols adjacent to an entity describe the relationship.

# Cardinality

* Cardinality refers to the relationship between two entities, showing how many instances of one entity relate to instances in another entity.
* You specify cardinality in an ERD with various line endings.
* The first component of the terminator indicates whether the relationship between two entities is optional or required.
* The second component indicates whether an entity instance in the first table is associated with a single entity instance in the related table or if an association can exist with multiple entity instances.
*  ERDs are particularly useful when formulating how to retrieve information from the database that is spread across multiple tables because the diagrams allow you to visualize the connections between entities.

# Unary relationship

* A unary relationship is when an entity has a connection with itself.

# Binary relationship

* A binary relationship connects two entities. Example, relationship Connecting Animal and Person.
* Binary relationships are the most common and easy to explore, whereas unary and ternary are comparatively complex and rare.

# Ternary relationship

* A ternary relationship connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price.
* A ternary relationship connects three entities.

# Relational databases

* Relational databases are pieces of software that let you make an operational system out of an ERD.
*  You start with a relational model and create a physical design. Relational entities correspond to database tables, and entity attributes correspond to table columns.
*  When creating a database table, the ordering of columns does not matter because you can specify the column order when retrieving data from a table.
*  When an attribute becomes a column, you assign it a data type.
*  Completing all of this work results in a diagram known as a schema.

# Pulling of data

*  To pull data from a relational database table, you perform a query. You compose queries using a programming language called Structured Query Language (SQL).
*  Your query needs to perform a database join to retrieve the data to substitute in the email reminder.
* A join uses data values from one table to retrieve associated data in another table, typically using a foreign key.

# Foreign key

* Foreign keys enforce referential integrity, or how consistent the data is in related tables.

# Non-relational

* A nonrelational database does not have a predefined structure based on tabular data. The result is a highly flexible approach to storing data.
# Key value

* A key-value database is one of the simplest ways of storing data. Data is stored as a collection of keys and their corresponding values.
* A key must be globally unique across the entire database.
* The use of keys differs from a relational database, where a given key identifies an individual row in a specific table.
* There are no structural limits on the values of a key. A key can be a sequence of numbers, alphanumeric strings, or some other combination of values.

# Document

* A document database is similar to a key-value database, with additional restrictions. In a key-value database, the value can contain anything.
* With a document database, the value is restricted to a specific structured format.
* With a known, structured format, document databases have additional flexibility beyond what is possible with key-value.

# Column family

* Column-family databases use an index to identify data in groups of related columns. A relational database stores the data in Table 3.2 in a single table, where each row contains the Person_ID, Title, First_Name, Middle_Name, Last_Name, and Email columns.
* In a column-family database, the Person_ID becomes the index, while the other columns are stored independently.
* This design facilitates distributing data across multiple machines, which enables handling massive amounts of data.
* The main reason for choosing a column-family database is its ability to scale.

# Graph 

* Graph databases specialize in exploring relationships between pieces of data.
* Graph models map relationships between actual pieces of data.Relational models focus on mapping the relationships between entities.
* Graphs are an optimal choice if you need to create a recommendation engine, as graphs excel at exploring relationships between data.
* Understanding the connection between products is a challenge that graphs solve with ease.

# Database use cases

* Different business needs require different database designs. While all databases store data, the database's structure needs to match its intended purpose. Business requirements impact the design of individual tables and how they are interconnected.
* Transactional and reporting systems need different implementation approaches to serve the people who use them efficiently.
* Databases tend to support two major categories of data processing: Online Transactional Processing (OLTP) and Online Analytical Processing (OLAP).

# Online Transactional Processing 

* OLTP systems handle the transactions we encounter every day. Example transactions include booking a flight reservation, ordering something online, or executing a stock trade.
* While the number of transactions a system handles on a given day can be very high, individual transactions process small amounts of data.
* OLTP systems balance the ability to write and read data efficiently.

# Normalization

* Normalization is a process for structuring a database in a way that minimizes duplication of data.
* One of the principles is that a given piece of data is stored once and only once. As a result, a normalized database is ideal for processing transactions.
* First normal form (1NF) is when every row in a table is unique and every column contains a unique value.
* Second normal form (2NF) starts where 1NF leaves off.
* In addition to each row being unique, 2NF applies an additional rule stating that all nonprimary key values must depend on the entire primary key.
* Third normal form (3NF) builds upon 2NF by adding a rule stating all columns must depend on only the primary key.

# Online Analytical Processing

* OLAP systems focus on the ability of organizations to analyze data.
* While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different.
* OLTP databases need to balance transactional read and write performance, resulting in a highly normalized design. Typically, OLTP databases are in 3NF.
* On the other hand, databases that power OLAP systems have a denormalized design. Instead of having data distributed across multiple tables, denormalization results in wider tables than those found in an OLTP database.
* It is more efficient for analytical queries to read large amounts of data for a single table instead of incurring the cost of joining multiple tables together.
* The greater the number of joins, the more complex the query.
* The more complex the query, the longer it takes to retrieve results.

# Schema Concepts

* The design of a database schema depends on the purpose it serves. Transactional systems require highly normalized databases, whereas a denormalized design is more appropriate for analytical systems.

# Data warehouse

* A data warehouse is a database that aggregates data from many transactional systems for analytical purposes.
* Transactional data may come from systems that power the human resources, sales, marketing, and product divisions.
*  A data warehouse facilitates analytics across the entire company.

# Data mart

* A data mart is a subset of a data warehouse.
* Data warehouses serve the entire organization, whereas data marts focus on the needs of a particular department within the organization.
* For example, suppose an organization wants to do analytics on their employees to understand retention and career evolution trends. 
*  To satisfy that use case, you can create a data mart focusing on the human resources subject area from the data warehouse.

 # Data lake 

 * A data lake stores raw data in its native format instead of conforming to a relational database structure.
 * Using a data lake is more complex than a data warehouse or data mart, as it requires additional knowledge about the raw data to make it analytically useful.
 * Relational databases enforce a structure that encapsulates business rules and business logic, both of which are missing in a data lake.

# Star schema design

* The star schema design to facilitate analytical processing gets its name from what the schema looks like when looking at its entity relationship diagram.
* At the centre of the star is a fact table. Fact tables chiefly store numerical facts about a business.
* Qualitative data, including names, addresses, and descriptions, is stored in a series of dimension tables that connect to the main fact table.
* When data moves from an OLTP design into a star schema, there is a significant amount of data duplication.
* As such, a star schema consumes more space than its associated OLTP design to store the same data.
* These additional resource needs are one of the factors that makes data warehouses expensive to operate.

# Snowflake

* Another design pattern for data warehousing is the snowflake schema.
* As its name implies, the schema diagram looks like a snowflake.
* Snowflake and star schemas are conceptually similar in that they both have a central fact table surrounded by dimensions.
* Where the approaches differ is in the handling of dimensions. With a star, the dimension tables connect directly to the fact table.
* With a snowflake, dimensions have subcategories, which gives the snowflake design its shape.
* A snowflake schema is less denormalized than the star schema.
* With a snowflake schema, you may need more than one join to get the data you are looking for.
* Recall that as the number of tables in a schema grows, queries become more complicated.
* A snowflake schema query is more complex than the equivalent query in a star schema.
* Part of the trade-off is that a snowflake schema requires less storage space than a star schema.
* Data warehouses often use snowflake schemas, since many different systems supply data to the warehouse.
* Data marts are comparatively less complicated, because they represent a single data subject area. As such, data marts frequently use a star-schema approach.

# Dimenstionality

* Dimensionality refers to the number of attributes a table has.
* The greater the number of attributes, the higher the dimensionality.
* A dimension table provides additional context around data in fact tables.
* It is crucial to understand the types of questions an analyst will need to answer when designing dimension tables.

# Handling Dimentionality 

* There are multiple ways to design dimensions.
* An understanding of this method is required to write a query to retrieve the current price.
* Another method extends the snowflake approach to modelling dimensions.
* You have a product dimension for the current price and a product history table for maintaining price history.
* One advantage of this approach is that it is easy to retrieve the current price while maintaining access to historical information.
* Another approach is to use an indicator flag for the current price.
* The indicator flag method keeps all pricing data in a single place.
* It also simplifies the query structure to get the current price. Instead of doing date math, you look for the price where the Current flag equals “Y.”
* It is also possible to use the effective date approach to handling price changes.
* There is additional complexity with the effective date approach because queries have to perform date math to determine the price.

# Data Acquisition Concepts

# Integration

* Data from transactional systems flow into data warehouses and data marts for analysis.
* Recall that OLTP and OLAP databases have different internal structures.
* You need to retrieve, reshape, and insert data to move data between operational and analytical environments.
* You can use a variety of methods to transfer data efficiently and effectively.
* One approach is known as extract, transform, and load (ETL). As the name implies, this method consists of three phases.

# Extract

*  In the first phase, you extract data from the source system and place it in a staging area. The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible.

# Transform

*  The second phase transforms the data. The goal is to reformat the data from its transactional structure to the data warehouse's analytical design.

# Load

*  The purpose of the load phase is to ensure data gets into the analytical system as quickly as possible.

# Extract, load and transform (ELT)

* With ELT, data is extracted from a source database and loaded directly into the data warehouse.
* Once the extract and load phases are complete, the transformation phase gets underway.
* One key difference between ETL and ELT is the technical component performing the transformation.
* With ETL, the data transformation takes place external to a relational database, using a programming language like Python. ELT uses SQL and the power of a relational database to reformat the data.
* ELT has an advantage in the speed with which data moves from the operational to the analytical database.
* Suppose you need to get massive amounts of transactional data into an analytical environment as quickly as possible.
* In that case, ELT is a good choice, especially at scale when the data warehouse has a lot of capacity.
* Whether you choose ETL or ELT is a function of organizational need, staff capabilities, and technical strategy.

# ETL Vendors

* Whether you choose ETL or ELT for loading your data warehouse, you don't have to write transformations by hand.
* Many products support both ETL and ELT.

# Delta load 

* An initial load occurs the first time data is put into a data warehouse.
* After that initial load, each additional load is a delta load, also known as an incremental load.
* A delta load only moves changes between systems.
* The initial load happens right before the data warehouse becomes available for use.
* The frequency with which delta loads happen depends on business requirements.
* Depending on how fresh the data needs to be, delta loads can happen at any interval.
* When moving data between systems, you have to balance the speed and complexity of the overall operation.

# Data Collection Methods

* Augmenting data from your transactional systems with external data is an excellent way to improve the analytical capabilities of your organization.
* For example, suppose you operate a national motorcycle rental fleet and want to determine if you need to rebalance your fleet across your existing locations.
* You also want to evaluate whether it is profitable to expand to a new geographic region, as well as predict the best time and place to add motorcycles to your fleet.

# The Methods include:

# Application Programming Interfaces (APIs)

* An application programming interface (API) is a structured method for computer systems to exchange information.
* APIs provide a consistent interface to calling applications, regardless of the internal database structure.
* Whoever calls an API has no idea whether a transactional or analytical data store backs it.
* The internal data structure does not matter as long as the API returns the data you want.
* APIs can be transactional, returning data as JSON objects. APIs can also facilitate bulk data extraction, returning CSV files.
* APIs represent a specific piece of business functionality. Let's return to our motorcycle rental business.

# Web Services

* A web service is an API you can call via Hypertext Transfer Protocol (HTTP), the language of the World Wide Web.
* Many smartphone applications need a network connection, either cellular or Wi-Fi, to work correctly.
* The reason is that much of the data these applications need is not on the smartphone itself.
* Instead, data is found in private and public data sources and is accessible via a web service.
* If you imagine an API as the door behind which data treasures exist, an API key is what unlocks the door.
* API providers generate a unique API key for each calling application.
* Centralized creation and distribution of API keys allow the provider to understand who is using the API and to turn off individual keys' access in the event of abuse.

# Web Scraping

* Some of the data you want may not be available internally as an API or publicly via a web service.
* However, data may exist on a website.
* As seen in Chapter 2, data can present itself in an HTML table on a web page.
* If data exists in a structured format, you can retrieve it programmatically.
* Programmatic retrieval of data from a website is known as web scraping.  
* You can use software bots to scrape data from a website.
* Many modern programming languages, including Python and R, make it easy to create a web scraper.
* Instead of using an API or a web service, a web scraper reads a web page similar to a browser, such as Chrome, Safari, or Edge.
* Web scrapers read and parse the HTML to extract the data the web pages contain.
* The search results for some websites span multiple web pages.
* Your web scraper has to account for pagination to ensure that you are not leaving any data behind.
* The scraper must understand how many result pages exist and then iterate through them to harvest the data.

# Human-in-the-Loop

* There are times when the data you seek exists only in people's minds.
* For example, you can extract the most popular and profitable motorcycling destination from your existing internal data.
* You can get weather information from an API packaged as a web service.
* You can glean insight into competitive pricing by scraping your competitors' websites.
* Even with all of these data sources, you may still want insight into how customers feel about the services you provide.

# Surveys

* One way to collect data directly from your customers is by conducting a survey.
* The most simplistic surveys consist of one question and indicate customer satisfaction.
* As you design a survey, you want to keep in mind how you will analyse the data you collect.
* Numeric data is easy to analyse using a variety of statistical methods.
* Free-response questions result in unstructured text data, which is more challenging to interpret.
* You need to clearly understand what is essential to your organization and what decisions you will make using the output to develop and administer an impactful survey.

# Survey tools

* Instead of designing a custom application to collect survey data, several survey products let you design complex surveys without worrying about building a database.
* Qualtrics is a powerful tool for developing and administering surveys.
* What makes Qualtrics so compelling is its API, which you can use to integrate survey response data into a data warehouse for additional analysis.

# Observation

* Observation is the act of collecting primary source data, from either people or machines.
* Observational data can be qualitative or quantitative. Collecting qualitative observational data leads to unstructured data challenges.
* Quantitative observations are much easier to collect and interpret.
* For example, suppose you are trying to establish the defect rate on a production line.
* You can count the number of vehicles that come off the line, as well as how many fail post-production quality checks.

# Sampling

*Regardless of the data acquisition approach, you may end up with more data than is practical to manipulate. 

# Working With Data

* Determining an appropriate database structure, identifying data sources, and loading a database takes a considerable amount of effort.
* To turn a database design into an operational database ready to accept data, you use the Data Definition Language (DDL) components of SQL.
* DDL lets you create, modify, and delete tables and other associated database objects.
* To generate insights, a productive analyst must be comfortable using the Data Manipulation Language (DML) capabilities of SQL to insert, modify, and retrieve information from databases.
* While DDL manages the structure of a database, DML manages the data in the database.
* The DML components of SQL change very slowly. As long as relational databases exist, you will need to understand SQL to work with them.
* It is worth learning SQL, as the foundational knowledge of DML operations will serve you well.

# Data Manipulation
When manipulating data, one of four possible actions occurs:

* Create new data.
* Read existing data.
* Update existing data.
* Delete existing data.
* The acronym CRUD (Create, Read, Update, Delete) is a handy way to remember these four operations.

# Data manipulation in SQL

* Create with keyword INSERT - Create new data in an existing table.
* Read with keyword SELECT - Retreives data from an existing table.
* Update with keyword UPDATE - Changes existing data in an existing table.
* Delete with keyword DELETE - Removes existing data from an existing table.
* The FROM clause in a query identifies the source of data, which is frequently a database table. Both the SELECT and FROM clauses are required for a SQL statement to return data.

# SQL Considerations 

* The keywords in SQL are case-insensitive. However, the case-sensitivity of column names and values depend on the database configuration.
* SQL can also span multiple lines. For example, rewriting the previous query as follows will return identical results.
* How a query appears is a function of organizational conventions.
* Factors that influence convention include database configuration, query efficiency, and how easy it is for people to read and understand the query.

# Filtering

* Examining a large table in its entirety provides insight into the overall population.
* To answer questions that an organization's leadership has typically requires a subset of the overall data.
* Filtering is a way to reduce the data down to only the rows that you need.
* To filter data, you add a WHERE clause to a query.
* Note that the column you are filtering on does not have to appear in the SELECT clause.

# Filtering and Logical Operators

* A query can have multiple filtering conditions. You need to use a logical operator to account for complex filtering needs.
* For example, suppose you need to retrieve the name and breed for dogs weighing more than 60 pounds.
* In that case, you can enhance the query using the AND logical operator.
* The AND operator evaluates the Animal_Type and Weight filters together, only returning records that match both criteria.
* OR is another frequently used logical operator.
* Complex queries frequently use multiple logical operators at the same time.
* It is good to use parentheses around filter conditions to help make queries easy for people to read and understand.
* Filtering data is essential to making effective use of these massive data stores.

# Sorting 

* When querying a database, you frequently specify the order in which you want your results to return.
* The ORDER BY clause is the component of a SQL query that makes sorting possible.
* Similar to how the WHERE clause performs, you do not have to specify the columns you are using to sort the data in the SELECT clause.
* The ASC keyword at the end of the ORDER BY clause sorts in ascending order whereas using DESC with ORDER BY sorts in descending order.
* If you are sorting on multiple columns, you can use both ascending and descending as appropriate.
* Both the ASC and DESC keywords work across various data types, including date, alphanumeric, and numeric.

# Data Functions

*  Date columns also appear in transactional systems.
*  Storing date information about an event facilitates analysis across time.
*  The most important thing to note is that you have to understand the database platform you are using and how that platform handles dates and times.
* Since each platform provider uses different data types for handling this information, you need to familiarize yourself with the functions available from your provider of choice.

# Logical Functions

* Logical functions can make data substitutions when retrieving data.
* Remember that a SELECT statement only retrieves data.
* The data in the underlying tables do not change when a SELECT runs.
* When writing SQL, there are frequently many ways to write a query and create the same results.
* Boolean Expression:  The expression must return either TRUE or FALSE.
* True Value:  If the Boolean expression returns TRUE, the IFF function will return this value.
* False Value:  If the Boolean expression returns FALSE, the IFF function will return this value.

# Aggregate Functions 

* Summarized data helps answer questions that executives have, and aggregate functions are an easy way to summarize data.
* Aggregate functions summarize a query's data and return a single value.
* While each database platform supports different aggregation functions.
* COUNT - Returns the total number of rows of a query.
* MIN - Returns the minimum value from the results of a query. Note that this works on both alphanumeric and numeric data types.
* MAX - Returns the maximum value from the results of a query. Note that this works on both alphanumeric and numeric data types.
* AVG - Returns the mathematic average of the results of a query.
* SUM - Returns the sum of the results of a query.
* STDDEV - Returns the sample standard deviation of the results of a query.
* You can also use aggregate functions to filter data.
* System functions also return data about the database environment.
* For example, whenever a person or automated process uses data from a database, they need to establish a database session.
* A database session begins when a person/program connects to a database.
* The session lasts until the person/program disconnects.
* For example, a poorly written query can consume most of the resources available to the database.

# Query Optimization

* Writing an SQL query is straightforward. Writing a SQL query that efficiently does what you intend can be more difficult. There are several factors to consider when creating well-performing SQL.

# Parametrization

* Whenever a SQL query executes, the database has to parse the query. 
* Parsing translates the human-readable SQL into code the database understands.
* Parsing takes time and impacts how long it takes for a query to return data. 
* Effective use of parameterization reduces the number of times the database has to parse individual queries.
* Suppose you operate a website and want to personalize it for your customers. Login details serve as parameters to the query to retrieve your information for display.
* After logging in, a customer sees a welcome message identifying them by name.
* Instead of looking specifically for an exact string match for every customer, the query uses a variable called &customer_name.
* The code in the web server populates the variable with the appropriate customer name.
* To the database, this appears as a single query.
* While the value of &customer_name changes for every customer, the database parses it only once.

# Indexing

* When retrieving data from a table, the database has to scan each row until it finds the ones that match the filters in the WHERE clause.
* The process of looking at each row is called a full table scan.
* As data volumes increase, scanning the entire table takes a long time and is not efficient.
* To speed up query performance, you need a database index.
* A database index works like the index in the back of a book.
*  Instead of looking at each page in a book to find what you are looking for, you can find a specific page number in the index and then go to that page.
* A database index can point to a single column or multiple columns.
* When running queries on large tables, it is ideal if all of the columns you are retrieving exist in the index.
* If that is not feasible, you at least want the first column in your SELECT statement to be covered by an index.
* If a query is running slowly, look at the indexes on the underlying tables. If you think a new index would help improve query performance.
* While indexing improves query speed, it slows down create, update, and delete activity.
* An indexing strategy needs to match the type of system the database supports, be it transactional or reporting.

# Data Subsets and Temporary Tables

* When dealing with large data volumes, you may want to work with a subset of records.
* In this situation, the Order table in the data warehouse would have 2 billion rows.
* If you want to explore trends for a specific customer's order history, it would not be efficient to query the main Order table.
* It is possible to create a temporary table to make the data more manageable.
* Temporary tables can store the results of a query and are disposable.
* Temporary tables automatically get removed when the active session ends.
* Using temporary tables is an effective method of creating subsets for ad hoc analysis.
* For example, you can establish a database session, create a temporary table with the order history for a single customer, run queries against that temporary table, and disconnect from the database.
* When the session disconnects, the database automatically purges any temporary tables created during the session.

# Execution Plan

* An execution plan shows the details of how a database runs a specific query.
* Execution plans are extremely helpful in troubleshooting query performance issues.
* They provide additional information about how a query is spending its time.
* For example, an execution plan can tell you if a slow-running query uses a full table scan instead of an index scan.
* In this case, it could be that the query is poorly written and not using the existing indexes.
* It also could be that a column needs a new index.
* Looking at execution plans is an integral part of developing efficient queries.
* It is worth understanding the nuances of how to interpret execution plans for the database platform you use. 

# Data Quality Challenges

# Duplicate Data

* Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system. Suppose you want to open a spreadsheet on your local computer.
* To open the spreadsheet, you locate the file and double-click it.
* This method of opening documents establishes muscle memory that associates double-clicking with the desired action.
* Humans are primarily responsible for creating duplicate data. System architects work diligently to prevent duplicate data from being created.
* The best way to resolve duplicate data is to prevent its creation in the first place.
* One common approach to stopping duplicate data before it gets into a system is a visual warning to alert users.
* To resolve duplicate data issues, the company has a duplicate resolution process.
* This process looks for customers with multiple billing addresses, validates the correct address, and updates the Sales database by removing the duplicate record.

# Redundant Data

* While duplicate data typically comes from accidental data entry, redundant data happens when the same data elements exist in multiple places within a system.
* Frequently, data redundancy is a function of integrating multiple systems.
* For example, multiple source systems that perform different business functions and use shared data elements create the conditions for data redundancy.
* When a record changes in one system, there is no guarantee that its new value changes in another system.
* Since there is no certainty of data synchronization, a data element can have conflicting values across systems.
* When integrating multiple data sources, dealing with redundant data is a persistent challenge.
* There are several options for resolving redundant data.
* One approach synchronizes changes to shared data elements between the Accounting and Sales systems.
* This integrated ETL process takes a delta load approach.
* When an address changes, the ETL job sets the effective end date for the old address and inserts a new row for the current address.
* While the data discrepancy between the Sales and Accounting systems still needs resolution, the analyst has the proper customer address in the data warehouse.
* Another root cause of data redundancy is an inappropriate database design.

# Missing Values

* Another issue that impacts data quality is the concept of missing values.
* Missing values occur when you expect an attribute to contain data but nothing is there.
* Missing values are also known as null values. A null value is the absence of a value.
* There are situations when allowing nulls makes sense.
* Suppose you are storing data about people and have a column for Middle Initial.
* Null values present several challenges depending on the tools you use to analyze data.
* Trying to calculate the average, which was successful in SQL, results in an error in Python and R as the equivalent functions in those languages do not handle null values.
* To handle missing values, you first have to check for their existence.
* QL offers functions to check for null and functions that can replace a null with a user-specified value.

# Invalid Data

* Invalid data are values outside the valid range for a given attribute.
* An invalid value violates a business rule instead of having an incorrect data type.
* Invalid values violate business rules, not technical rules.
* As such, programming languages do not have native functions that definitively tell you whether or not a given value is invalid.
* When considering data types, numeric and date data is comparatively easy to check for invalid values.
* Text data is more complex. One thing that leads to invalid character data is an absence of referential integrity within a database.
* If two tables have a relationship but no foreign keys, the conditions for invalid character data exist.
* Implementing relationships appropriately reduces the likelihood of invalid character data.

 # Nonparametric Data

 * Nonparametric data is data collected from categorical variables.

# Data Outliers

* A data outlier is a value that differs significantly from other observations in a dataset.
* With outliers, you need to understand why they exist and whether they are valid in the context of your analysis.
* Outliers exist regardless of data type.

# Specification Mismatch

* A specification describes the target value for a component.
* A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values.
* When data is invalid, it has values that fall outside a given range.
* On the other hand, a specification mismatch occurs when data does not conform to its destination data type.
* For example, you might be loading data from a file into a database.
* If the destination column is numeric and you have text data, you'll end up with a specification mismatch.
* To resolve this mismatch, you must validate that the inbound data consistently maps to its target data type.

# Data type Validation

* Data type validation ensures that values in a dataset have a consistent data type.
* Programming languages, including SQL, Python, and R, all have data type validation functions. Use these functions to validate the data type for each column in a data file before attempting a database load.
* It's in your best interest to detect and remediate data type issues as early as possible to ensure data is ready for analysis.

# Data Manipulation Techniques

# Recoding Data

* Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis.
* Recoding groups data into multiple categories, creating a categorical variable. A categorical variable is either nominal or ordinal.
* Nominal variables are any variable with two or more categories where there is no natural order of the categories, like hair color or eye color.
* Ordinal variables are categories with an inherent rank.

# Derived Variables

* A derived variable is a new variable resulting from a calculation on an existing variable.
* Storing age as a derived column is a bad practice, as it would need constant updates over time.
* Instead of keeping age as a derived variable, you should embed the formula to derive age in code.

# Data Merge

* A data merge uses a common variable to combine multiple datasets with different structures into a single dataset.
* Merging data improves data quality by adding new variables to your existing data.
* Additional variables make for a richer dataset, which positively impacts the quality of your analysis.
* ETL processes commonly append data while transforming data for use in analytical environments.

# Data Blending

* Data blending combines multiple sources of data into a single dataset at the reporting layer.
* While data blending is conceptually similar to the extract, transform, and load process, there is a crucial difference.
* Data blending differs from ETL in that it allows an analyst to combine datasets in an ad hoc manner without saving the blended dataset in a relational database.
* Instead of the blended dataset persisting over time, it exists only at the reporting layer, not in the source databases.
* For example, data visualization tools such as Tableau allow analysts to connect to different source systems and blend the data using a shared attribute.
* Data blending can reduce the burden on IT as it gives analysts the ability to merge data.

# Concatenation

* Concatenation is the merging of separate variables into a single variable.
* Concatenation is a highly effective technique when dealing with a source system that stores components of a single variable in multiple columns.
* The need for concatenation frequently occurs when dealing with date and time data. Concatenation is also useful when generating address information.

# Data Append

* A data append combines multiple data sources with the same structure, resulting in a new dataset containing all the rows from the original datasets.
* When appending data, you save the result as a new dataset for ongoing analysis.
* Consider the needs of a franchisor with multiple franchisee locations.
* Although each franchise operates independently, they use the same point of sales system.
* When the franchisor conducts aggregate sales analysis, it appends data from each franchisee's point of sales system into a single, unified table for ongoing analysis.

# Imputation

* Imputation is a technique for dealing with missing values by replacing them with substitutes.
*  When merging multiple data sources, you may end up with a dataset with many nulls in a given column.
* If you are collecting sensor data, it is possible to have missing values due to collection or transmission issues.

 # Here are a few approaches an analyst can use for imputing values:

 * Remove Missing Data:  With this approach, you can remove rows with missing values without impacting the quality of your overall analysis.
 * Replace with Zero:  With this approach, you replace missing values with a zero. Whether or not it is appropriate to replace missing data with a zero is contextual. In this case, zero isn't an appropriate value, as a person's weight should be a positive number. In addition, replacing a zero in this case has an extraordinary impact on the overall average weight.
 * Replace with Overall Average:  Instead of using a zero, you can compute the average Weight value for all rows that have data and then replace the missing Weight values with that calculated average.
 * Replace with Most Frequent (Mode):  Alternatively, you can take the most frequently occurring value, called the mode, and use that as the constant.
* Closest Value Average:  With this approach, you use the values from the rows before and after the missing values. For example, to replace the missing measurements for 2/13/2021 and 2/14/2021, take the values from 2/12/2021 and 2/15/2021 to compute the average.

# Reduction 

* When dealing with big data, it is frequently unfeasible and inefficient to manipulate the entire dataset during analysis.
* Reduction is the process of shrinking an extensive dataset without negatively impacting its analytical value.
* There are a variety of reduction techniques from which you can choose.
* Selecting a method depends on the type of data you have and what you are trying to analyze.
* Dimensionality reduction and numerosity reduction are two techniques for data reduction.

# Dimentionality Reduction

* One reduction technique is dimensionality reduction, which removes attributes from a dataset.
* Removing attributes reduces the dataset's overall size.
* However, you can use any programming language, including Python or R, to remove dimensions.

# Numerosity Reduction

* Another technique is numerosity reduction, which reduces the overall volume of data.
* As data volumes grow, numerosity reduction can improve the efficiency of your analysis.
* One way to reduce the volume of quantitative data is by creating a histogram.
* You can create a histogram in Python, R, and many visualization-specific tools.
*A histogram is a diagram made up of rectangles, or bars, that show how frequently a specific value occurs.

# Aggregation

* Data aggregation is the summarization of raw data for analysis. When you are dealing with billions of individual records, a data summary can help you make sense of it all.
* You might want to know facts about the data that would be difficult to Figure out looking through the data by hand.
* Aggregating data provides answers that help make decisions.
*  Imagine you are on a road trip. While travelling, running out of fuel is the last thing you want to do.
* Onboard computers summarize your control inputs and give you a meaningful metric: distance to empty.
* With an understanding of how far you can travel with the fuel remaining, you have the data you need so you can stop, refuel, and avoid being stranded.

# Transposition

* Transposing data is when you want to turn rows into columns or columns into rows to facilitate analysis.
* When transposing, each value from a column becomes a new column.
* The transposed data could be more helpful, especially if you imagine thousands of rows of sales data.
* Combining aggregation with transposition is a powerful data manipulation technique.
* This data representation makes it easy to view performance across fiscal years at a glance.

# Normalization

* In the context of data manipulation, normalizing data differs from our discussion of database normalization in Chapter 3.
* In this context, normalizing data converts data from different scales to the same scale.
* If you want to compare columns whose measurements use different units, you want to normalize the data.
* After normalization is complete, the dataset is ready for statistical analysis.

# Min-Max Normalization

* The first thing you need to do is find the minimum value of column you working with. Then, find the maximum value of the column you working with.
* The value you want to convert within the column.
* Min-max normalization is one of the most straightforward approaches to normalizing data.

# Parsing/String Manipulation

* Raw data can contain columns with composite or distributed structural issues.
*  A composite issue is when a raw data source has multiple, distinct values combined within a single character column.
*  When this happens, each value in a composite column has data that represents more than one attribute.
* Composite columns need to be split into their component parts to aid analysis.
* Similarly, it is possible to have a distributed structural issue when data in a single column spreads across multiple columns.
* When that happens, you need to combine the individual columns.
* Whenever you have composite or distributed structural data issues, you need to manipulate the strings before starting your analysis.
* In order to analyse the data by date, the string manipulation process combines the values from the Day, Month, and Year columns into a new Date column.
* Once you have a Date column, you can use programming functions to extract the day, month, and year if you need them.
* You also may need to manipulate string data to improve data quality.

# Circumstances to Check for Quality
Errors during data acquisition, transformation, manipulation, and visualization all contribute to degrading data quality. You should recognize the types of quality issues that can occur and have an overarching strategy to ensure the quality of your data.

* Data Acquisition
* Data Transformation and Conversion
* Data Manipulation
* Final Product Preparation

# Automated Validation

* Many data sources feed analytics environments. While some of these data sources are other computer systems, others depend directly on people.
* Whenever people interact with systems, it's possible to introduce data-related errors.
* Whether source data is machine- or human-generated, one way to prevent data entry mistakes from adversely impacting data quality is to automate data validation checks.
* Before automatically validating input data, you need to understand how source data fields map to their corresponding database columns.
* When mapping input data, pay close attention to the data types in the database.
* For example, suppose you have a web form where customers supply phone numbers, and the destination database uses a numeric data type to store phone data.
* If the input form allows for free text entry, someone may enter (312) 555-1212. Attempting to insert the parentheses and hyphen into a numeric column results in a database error due to a data type mismatch. 
* Automating the data type validation before passing the data to the database prevents this from happening.
* Another example of automation is verifying the number of data points. For example, suppose you are collecting hourly temperature data from a collection of sensors.
* For each sensor, you would expect to have 24 data points per day. If a sensor fails, it no longer reports data.
* Automating the verification of the number of data points instead of their values can help you identify a sensor failure.
* Early identification of sensor failure prevents missing data from flowing into your analytics environment.

# Data Quality Dimentions

* It is essential to consider multiple attributes of data when considering its quality.
* Six dimensions to take into account when assessing data quality are accuracy, completeness, consistency, timeliness, uniqueness, and validity.
* Understanding these dimensions and how they are related will help you improve data quality.
# 6 Dimensions of Improving Data

* Data Accuracy
* Data Completeness
* Data Consistency
* Data Timeliness
* Data Uniqueness
* Data Validity

# Data Quality Rules and Metrics

* With an understanding of data quality dimensions, you need to consider how to measure each of them in your quest to improve overall quality.
* When consolidating data from multiple source systems into an analytics environment, one factor you want to assess is the conformity or nonconformity of data.
* If source data does not match the destination data type size and format, you have nonconformity.
* If source data does not match the destination data type size and format, you have nonconformity.
* One way to validate data conformity issues is to confirm how many rows pass successfully to the target environment and how many fail.
* Suppose you have 1 million billing records to migrate into the Data Warehouse.
* Instead of aborting the entire data load, the Warehouse Load ETL job sends the 100,000 nonconforming rows to a Bad Data staging area.
* A data engineer then resolves the root cause of the data quality issue before sending the remediated data into the Data Warehouse.
* With this design, the nonconformity of a single row does not cause the entire load process to fail.
* By only reprocessing failed rows, this approach makes efficient use of resources as well as improving quality.

# Methods to Validate Quality

# Reasonable Expectations

* One approach is to determine whether or not the data in your analytics environment meets your reasonable expectations.
* For example, if your transactional systems process 10 million records per day, it is reasonable to expect an incremental 300 million records in your analytics environment at the end of 30 days
* If after 30 days you only see an additional 20 million records, it is reasonable for you to presume that the data propagation ETL is failing.
* It is worth spending time reflecting on what measures are reasonable for your environment.
* After defining how you want to measure your expectations, automate the reasonable expectation check by creating exception reports as part of your ETL processes.
* For example, if the number of successful rows is less than a large percentage of attempted rows, your internal alarm bells should start ringing.
* The root cause of the ETL load failure needs remediation to prevent ongoing issues with data quality.

# Data Profiling

* Another approach to improving quality is to profile your data.
* Data profiling uses statistical measures to check for data discrepancies, including values that are missing, that occur either infrequently or too frequently, or that should be eliminated.
* Profiling can also identify irregular patterns within your data.
* For example, suppose you are trying to analyse customer engagement by examining the frequency with which customers log into your website.
* On average, you see that customers log in once per day from one of four devices.
* However, profiling your data shows that a specific customer is logging in three hundred times per day from three hundred unique devices.
* Further analysis shows that these logins originate from multiple different places around the globe.
* The results of your data profiling activity fail the reasonable expectation test, as customers typically log in less frequently and from fewer devices.
* Instead of trusting this data, you proceed to investigate whether or not this activity is fraudulent.

# Data Audits

* Another method to keep in mind is auditing your data. Data audits look at your data and help you understand whether or not you have the data you need to operate your business.
* Data audits use data profiling techniques and can help identify data integrity and security issues.
* For example, suppose you work with a large company that has relationships with numerous suppliers.
* To understand what is reasonable, you create a report to show the average payment amount by the supplier.
* For example, suppose you work with a large company that has relationships with numerous suppliers.
* To understand what is reasonable, you create a report to show the average payment amount by the supplier.
* One day, you notice an unusually large supplier payment. Looking into the disbursement, you also discover that the payment was sent to a new financial institution.

# Sampling

* Another method for validating data quality is by examining a sample of your data. Sampling is a statistical technique in which you use a subset of your data to inform conclusions about your overall data.
* For example, suppose you are an automotive manufacturer and want to ensure the quality of fasteners from one of your suppliers. Suppose you have a daily production volume of 10,000 at one of your assembly plants.
* If each vehicle requires 3,500 fasteners, you need 35 million per day.
* Fastener failures can lead to quality issues, safety issues, and recalls. All of these quality issues are expensive to address and generate bad press.

# Cross-Validation

* Analysts frequently use existing data to generate predictive models using a variety of statistical methods.
* Cross-validation is a statistical technique that evaluates how well predictive models perform.
* Cross-validation works by dividing data into two subsets. The first subset is the training set, and the second is the testing, or validation, set.
* You use data from the training set to build a predictive model.
* You then cross-validate the model using the testing subset to determine how accurate the prediction is.
* Cross-validation is also helpful in identifying data sampling issues.

# Data Analysis and Statistics

# Descriptive Statistics

* Descriptive statistics is a branch of statistics that summarizes and describes data. As you explore a new dataset for the first time, you want to develop an initial understanding of the size and shape of the data.
* You use descriptive statistics as measures to help you understand the characteristics of your dataset.
* When initially exploring a dataset, you may perform univariate analysis to answer questions about a variable's values.
* You also use descriptive measures to develop summary information about all of a variable's observations.
* This context helps orient you and informs the analytical techniques you use to continue your analysis.

# Measure of Frequency 

* Measures of frequency help you understand how often something happens.
* When encountering a dataset for the first time, you want to determine how much data you are working with to help guide your analysis.
* For example, suppose you are working with human performance data.
* One of the first things to understand is the size of the dataset. One way to accomplish this quickly is to count the number of observations.
* Understanding the total number helps influence the tools you use to explore the data.

# Count

* The most straightforward way to understand how much data you're working with is to count the number of observations.
* Understanding the total number of observations is a frequently performed task. As such, there is a count function in everything from spreadsheets to programming languages.

# Percentage

* The percentage is a frequency measure that identifies the proportion of a given value for a variable with respect to the total number of rows in the dataset.
* To calculate a percentage, you need the total number of observations and the total number of observations for a specific value of a variable.
* Understanding proportions across a dataset aids in determining how you proceed with your analysis.

# Frequency 

* Frequency describes how often a specific value for a variable occurs in a dataset. You typically explore frequency when conducting univariate analysis.

# Measures of Central Tendency 

* To help establish an overall perspective on a given dataset, an analyst explores various measures of central tendency.
* You use measures of central tendency to identify the central, or most typical, value in a dataset.
* There are numerous ways to measure central tendency, and you end up using them in conjunction with each other to understand the shape of your data.

# Mean

* The mean, or average, is a measurement of central tendency that computes the arithmetic average for a given set of numeric values.
* To calculate the mean, you take the sum of all values for an observation and divide by the number of observations.
* Data analysis tools, including spreadsheets, programming languages, and visualization tools, all have functions that calculate the mean.
* While the mean is one of the most common measurements of central tendency, remember that you can only calculate a mean for quantitative data.
* You should also be mindful of the effect outliers have on the mean's value.
* An outlier is a value that differs significantly from the other values of the same observation.

# Median

* Another measurement of central tendency is the median, which identifies the midpoint value for all observations of a variable.
* The first step to calculating the median is sorting your data numerically.
* Once you have an ordered list of values, the next step depends on whether you have an even or an odd number of observations for a variable.
* Identifying the median for an odd number of observations is straightforward—you just select the number in the middle of the ordered list of values.
* Suppose you have the following numbers: {1,3,5,7,9}. To find the median, you take the total number of values, add 1, divide by 2, and retrieve the corresponding value.
* For datasets with an even number of observations, you need to take the average of the two observations closest to the midpoint of the ordered list.
* Suppose you have the following numbers: {1,3,5,7,9,11}. Since there are six observations, the median is the mean of the values that surround the midpoint.
* In this case, you find the mean of 5 and 7, which is 6.
* Outliers don't impact the median as dramatically as the mean.

# Mode

* The mode is a variable's most frequently occurring observation. Depending on your data, you may not have a mode.
* Depending on the level of precision and amount of data, the mode may not facilitate insight when working with numeric data.
* However, the mode is more applicable when working with categorical data.

# Measures of Dispersion

# Range 

* The range of a variable is the difference between its maximum and minimum values.
* Understanding the range helps put the data you are looking at into context and can help you determine what to do with outlier values.

# Distribution

* In statistics, a probability distribution, or distribution, is a function that illustrates probable values for a variable, and the frequency with which they occur.
* Histograms are an effective tool to visualize a distribution, because the shape provides additional insight into your data and how to proceed with analysis.
* Distributions have many possible shapes, including normal, skewed, and bimodal.

# Normal Distribution

* The normal distribution is symmetrically dispersed around its mean, which gives it a distinctive bell-like shape.
* Due to its shape, the normal distribution is also known as a “bell curve.”
* The normal distribution is applicable across a number of disciplines due to the central limit theorem (CLT), a foundational theorem for statistical analysis.
* According to the CLT, as sample size increases, it becomes increasingly likely that the sampling distribution of all those means will be normally distributed.
* For example, suppose you are working with quantitative data about people. According to the CLT, you can expect the normal distribution to describe the people's height, weight, and shoe size.
* You can test out the CLT at home by rolling a pair of dice at least 30 times to get a sufficiently large sample and then plotting the value and frequency of your rolls.
* One way to use measures of central tendency to verify the normal distribution is to examine the proximity of the mean and median.
* When the mean and median are relatively close together, the distribution will be symmetrical. If the mean and median are far apart, the data is skewed, or asymmetrical.

# Skewed Distribution

* A skewed distribution has an asymmetrical shape, with a single peak and a long tail on one side. Skewed distributions have either a right (positive) or left (negative) skew.
* When the skew is to the right, the mean is typically greater than the median. On the other hand, a distribution with a left skew typically has a mean less than the median.
* The long tail to the right of the peak shows that while most people have a salary of under $100,000, a large portion of the population earns significantly more.
* It is reasonable to expect a right skew for income.
* There are times when you would expect to see a left skew in the data. For example, imagine grades on a 100-point exam for students in a graduate statistics class.

 # Bimodal Distribution

 * A bimodal distribution has two distinct modes, whereas a multimodal distribution has multiple distinct modes. When you visualize a bimodal distribution, you see two separate peaks.
 * Suppose you are analyzing the number of customers at a restaurant over time. You would expect to see a large numbers of customers at lunch and dinner.
 * 

# Variance

* Variance is a measure of dispersion that takes the values for each observation in a dataset and calculates how far away they are from the mean value.
* This dispersion measure indicates how spread out the data is in squared units. Mathematically,  signifies population variance, which you calculate by taking the average squared deviation of each value from the mean.
* The slight difference in the denominator between the formulas for calculating population and sample variance is due to a technique known as Bessel's correction.
* Bessel's correction specifies that when calculating sample variance, you need to account for bias, or error, in your sample.
* Recall that a sample does not fully represent the overall population. When you have sample data and use the degrees of freedom in the denominator, it provides an unbiased estimate of the variability.
* When the variance is large, the observations’ values are far from the mean and thus far from each other. Meanwhile, a small variance implies that the values are close together.

# Standard Deviation

* Standard deviation is a statistic that measures dispersion in terms of how far values of a variable are from its mean. Specifically, standard deviation is the average deviation between individual values and the mean.
* Mathematically,  signifies population standard deviation, which you calculate by taking the square root of the variance.
* Similar to the difference between population and sample variance, the formula for sample standard deviation uses Bessel's correction.
* Standard deviation is a widely accepted measure of quality control in manufacturing processes. Large manufacturers implement programs to improve the consistency of their manufacturing processes.
* Combining the central limit theorem and the empirical rule makes standard deviation a common way of describing and discussing variability.
* One quality control program is known as Six Sigma, which sets the goal for a production process to six standard deviations. Achieving that degree of consistency is difficult and expensive.

# Measure of Position

# Special Normal Distribution

* The Central Limit Theorem and empirical rule combine to make the normal distribution the most important distribution in statistics. There are two special normal distributions that have broad applicability and warrant a deeper understanding.

# Standard Normal Distribution

* The standard normal distribution, or Z-distribution, is a special normal distribution with a mean of 0 and a standard deviation of 1.
* You can standardize any normal distribution by converting its values into Z-scores.
* Converting to the standard normal lets you compare normal distributions with different means and standard deviations.

 # Student T-Distribution

 * The Student's t-distribution, commonly known as the t-distribution, is similar to the standard normal distribution in that it has a mean of 0 with a bell-like shape.
 * One way the t-distribution differs from the standard normal distribution is how thick the tails are since you can use the t-distribution for sample sizes of less than 30.
 * It's crucial to note that the height of the bell and the thickness of the tails in t-distributions vary due to the number of degrees of freedom. Numerically, the value for degrees of freedom is 1 less than the number of observations in your sample data.
 * The degrees of freedom represent the number of values that can vary when calculating a statistic.

# Measure of Position

* Understanding a specific value for a variable relative to the other values for that variable gives you an indication of the organization of your data. Statisticians commonly use quartiles to describe a specific observation's position.
* The process of obtaining quartiles is similar to that of determining the median. You first sort a numeric dataset from smallest to largest and divide it positionally into four equal groups.
* Each grouping is known as a quartile. The first quartile is the group that starts with the minimum value, whereas the fourth quartile is the group that ends with the maximum value.
* The interquartile range (IQR) is the combination of the second and third quartiles and contains 50 percent of the values in the data. When exploring a dataset, recall that outliers can have a significant impact on mean and range.
* Using the IQR as a dispersion indicator, in addition to the range, improves your perspective since the IQR excludes outliers.
* 




 </details>

 <details>
<summary> Week 3 </summary>

</details>
























 









</details>
