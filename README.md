# Data-Analytics

<details>
 <summary> Week 1 </summary>
 
# Introduction to Data Analytics

* Analytics is at the heart of modern business. Virtually every organization collects large quantities of data about its customers, products, employees, and service offerings.
* Managers naturally seek to analyze that data and harness the information it contains to improve the efficiency, effectiveness, and profitability of their work.
* The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization. 
* This involves several key responsibilities and skills.

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

# Analytics techniques

* Descriptive analytics, which answers the question, “What happened?”
* Diagnostic analytics, which answers the question, “Why did this happen?”
* Predictive analytics, which answers the question, “What might happen in the future?”
* Prescriptive analytics, which answers the question, “What should we do next?”

# Machine Learning, Artificial Intelligence, and Deep Learning

* Machine learning (ML) - is a subset of AI techniques. ML techniques attempt to apply statistics to data problems in an effort to discover new knowledge.
 Or, in other terms, ML techniques are AI techniques designed to learn.
* Artificial intelligence (AI) - includes any type of technique where you are attempting to get a computer system to imitate human behavior. 
 as the name implies, you are trying to ask computer systems to artificially behave as if they were intelligent. Now, of course, it is not possible for a modern computer to function at the level of complex reasoning found in the human mind, but you can try to mimic some small portions of human behavior and judgment.
* Deep learning - is a further subdivision of machine learning that uses quite complex techniques, known as neural networks, to discover knowledge in a particular way. It is a highly specialized subfield of machine learning that is most commonly used for image, video, and sound analysis.

# Data element

* A data element is an attribute about a person, place, or thing containing data within a range of values. Data elements also describe characteristics of activities, including orders, transactions, and events. 

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

# Wohole numbers 

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
  * 
     
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


# Common data structures
In order to facilitate analysis, data needs to be stored in a consistent, organized manner. When considering structured data, several concepts and standards inform how to organize data. On the other hand, unstructured data has a wider variety of storage approaches.

# Structure data

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

* Before it was common to use delimited files with variable-length columns, flat files were fixed-width

</details>
