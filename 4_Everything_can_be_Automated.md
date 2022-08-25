## 3.0.1 Iota - Why Should I Take this Module?

- Still with me? Great! Because this module might just blow your mind. The IoT relies on data, and lots of it. What do I mean by data? Well, where you live is data. Your birthday is data. Your blood type is data. Almost everything can be qualified (and quantified) as data. When you click ‘Like’ on various social media platforms, that is a little piece of data that gets added to thousands, and even millions of other little pieces of data. The IoT is all about people finding uses for all that data, and you can too

## 3.0.2 What Will I Learn in this Module?

- Explain how data provides value to Digital Business and Society

![image](https://user-images.githubusercontent.com/29455975/186419720-d2a1fbae-6c0a-495e-b802-5b6199ecf8ff.png)

## 3.1.1 What is Big Data?

- Data comes from a variety of sources, such as people, pictures, text, sensors, and web sites. Data also comes from devices like cell phones, computers, kiosks, tablets, and cash registers. Most recently, there has been a spike in the volume of data generated by sensors. Sensors are now installed in an ever-growing number of locations and objects. These include security cameras, traffic lights, intelligent cars, thermometers, and even grape vines
- Big Data is a lot of data, but what is a lot? No one has an exact number that says when data from an organization is considered “Big Data.”

- Here are three characteristics that indicate an organization may be dealing with Big Data:
    - They have a large amount of data that increasingly requires more storage space (volume)
    - They have an amount of data that is growing at ever-increasing speed (velocity)
    - They have data that is generated in different formats (variety)
- How much data do sensors collect? Here are some estimated examples.
    - For comparison, assume that the average MP3 song is about 3 megabytes

- Sensors in one smart connected home can produce as much as 1 gigabyte (GB) of information a week, or the equivalent of 333 MP3 songs
- Sensors in one autonomous car can generate 4,000 gigabits (Gb) of data per day. That’s 500 gigabytes (GB) of data, which is the equivalent of about 167,000 MP3 songs
- Safety sensors in mining operations can generate up to 2.4 terabits (TB) of data every minute. That is 300 GB or about 100,000 MP3 songs
- An Airbus A380 Engine generates 1 petabyte (PB) of data on a flight from London to Singapore. That is one million GB, or about 334 million MP3 songs
- While Big Data does create challenges for organizations in terms of storage and analytics, it can also provide invaluable information to fine-tune operations and improve customer satisfaction

## 3.1.2 Check Your Understanding - Identify Scenarios that Generate Big Data

 -Check your understanding of big data by choosing the correct answer to the following questions

- 3 Quiz

## 3.1.3 Check Your Understanding - Big Data: Volume, Velocity, or Variety Characteristics

- Check your understanding of volume, velocity and variety by choosing the correct answer to the following questions

- 3 Quiz

## 3.1.4 Large Datasets

- Companies do not necessarily have to generate their own Big Data. Smaller organizations might not have the sensors, the volume of customers, or the ability to generate the variety of information that could benefit their company. There are sources of free data sets available, ready to be used and analyzed by anyone willing to look for them
- Many companies of various sizes believe they have to collect their own data to see benefits from big data analytics, but it is simply not true

## 3.1.5 Lab – Explore a Large Dataset

- In this lab you will explore a sample dataset to view the power of Big Data

## 3.1.6 Check your Understanding - Large Data Sets

- Check your understanding of large data sets by choosing the correct answer to the following questions

- 3 Quiz

## 3.2.1 What Are the Challenges of Big Data?

- The World Economic Forum predicts that the amount of data generated daily will be 463 exabytes (EB) globally. One EB is equal to one billion gigabytes!

- To put this into context, according to Statista, every minute of every day:
    - We upload over 500 hours of YouTube video
    - We send over 69 million instant messages
    - We stream over 347,000 GB of Netflix video
    - We send 198 million emails
    - We upload over 60,000 Instagram images
- To see more dynamic internet statistics search on “internet live stats.”

- The rapid growth of data can be an advantage or an obstacle when it comes to achieving business goals. To be successful, enterprises must be able to easily access and manage their data assets
- With this enormous amount of data being constantly created, traditional technologies and data warehouses cannot keep up with storage needs. Even with the cloud storage facilities that are available from companies like Amazon, Google, Microsoft, and many others, the security of stored data becomes a big problem. Big Data solutions must be secure, have a high fault tolerance, and use replication to ensure data does not get lost. Big Data storage is not only about storing data, but also about managing and securing it

## 3.2.2 Where Can We Store Big Data?

- Big data is typically stored on multiple servers, usually housed within data centers. For security, accessibility, and redundancy, the data is usually distributed and/or replicated on many different servers in many different data centers
- Edge Computing
    - Edge computing is an architecture that utilizes end-user clients or devices at the edge of the network to do a substantial amount of the pre-processing and storage required by an organization. Edge computing was designed to keep the data closer to the data source for pre-processing
- Sensor data, in particular, can be pre-processed closer to where it was collected. The information gained from that pre-processed analysis can be fed back into companies’ systems to modify processes if required. Because the sensor data is pre-processed by end devices within the company system, communications to and from the servers and devices is quicker. This requires less bandwidth than constantly sending raw data to the cloud
- After the data has been pre-processed, it is often shipped off for longer term storage, backup, or deeper analysis within the cloud

## 3.2.3 The Cloud and Cloud Computing

- As mentioned before, the cloud is a collection of data centers or groups of connected servers. Access to software, storage, and services available on the servers is obtained through the internet via a browser interface. Cloud services are provided by many large companies such as Google, Microsoft, and Apple. Cloud storage services are provided by different vendors such as: Google Drive, Apple iCloud, Microsoft OneDrive, and Dropbox
- From an individual’s perspective, using the cloud services allows you:
    - To store all of your data, such as pictures, music, movies, and emails, freeing up local hard drive space
    - To access many applications instead of downloading them onto your local device
    - To access your data and applications anywhere, anytime, and on any device
- One of the disadvantages of using the cloud is that your data could fall into the wrong hands. Your data is at the mercy of the security robustness of your chosen cloud provider

- From the perspective of an enterprise, cloud services and computing support a variety of data management issues:
    - It enables access to organizational data anywhere and at any time
    - It streamlines the IT operations of an organization by subscribing only to needed services 
    - It eliminates or reduces the need for onsite IT equipment, maintenance, and management
    - It reduces the cost of equipment, energy, physical plant requirements, and personnel training needs
    - It enables rapid responses to increasing data volume requirements

## 3.2.4 Distributed Processing

- From a data management perspective, analytics were simple when only humans created data. The amount of data was manageable and relatively easy to sift through. However, with the explosion of business automation systems and the exponential growth of web applications and machine-generated data, analytics is becoming increasingly more difficult to manage. In fact, 90% of data that exists today has been generated in just the last two years. This increased volume within a short period of time is a property of exponential growth. This high volume of data is difficult to process and analyze within a reasonable amount of time
- Rather than large databases being processed by big and powerful mainframe computers and stored in giant disk arrays (vertical scaling), distributed data processing takes the large volume of data and breaks it into smaller pieces. These smaller data volumes are distributed in many locations to be processed by many computers with smaller processors. Each computer in the distributed architecture analyzes its part of the Big Data picture (horizontal scaling)
- Most distributed file systems are designed to be invisible to client programs. The distributed file system locates files and moves data, but the users have no way of knowing that the files are distributed among many different servers or nodes. The users access these files as if they were local to their own computers. All users see the same view of the file system and are able to access data concurrently with other users
- Hadoop was created to deal with these Big Data volumes. The Hadoop project started with two facets: The Hadoop Distributed File System (HDFS) is a distributed, fault tolerant file system, and MapReduce, which is a distributed way to process data. Hadoop has now evolved into a very comprehensive ecosystem of software for Big Data management
- Hadoop is open-source software enabling the distributed processing of large data sets that can be terabytes in size and that are stored in clusters of computers. Hadoop is designed to scale up from single servers to thousands of machines, each offering local computation and storage. To make it more efficient, Hadoop can be installed and run on many VMs. These VMs can all work together in parallel to process and store the data
- Hadoop has two main features that have made it the industry standard for handling Big Data:
    - Scalability - Larger cluster sizes improve performance and provide higher data processing capabilities. With Hadoop, cluster size can easily scale from a five node cluster to a one thousand node cluster without excessively increasing the administrative burden
    - Fault tolerance – Hadoop automatically replicates data across clusters to ensure data will not be lost. If a disk, node, or a whole rack fails, the data is safe

## 3.2.5 Check Your Understanding - Define Big Data Terms

- Check your understanding of where big data is stored by choosing the correct answer to the following questions

- 6 Quiz

## 3.3.1 Why Do Businesses Analyze Data?

- Every organization must become more efficient and innovative to stay competitive and relevant in the digitized world. The IoT is an integral part of achieving that efficiency and innovation
- The goal of many businesses is to collect and analyze the massive amounts of new product-usage data to gain valuable insights. Data analytics allows businesses to better understand the impact of their products and services, adjust their methods and goals, and provide their customers with better products faster. The ability to gain new insights from their data brings value to the business
- To businesses, data is the new oil. Like crude oil, it is valuable, but if it is unrefined it cannot be easily used. Crude oil has to be changed to gasoline, plastic, chemicals, and other substances to create a valuable product. It is the same with data. Data must be broken down and analyzed for it to have value
- Value comes from two primary types of processed data, transactional and analytical. Transactional information is captured and processed as events happen. Transactional information is used to analyze daily sales reports and production schedules to determine how much inventory to carry. Analytical information supports managerial analysis tasks like determining whether the organization should build a new manufacturing plant or hire additional sales personnel

## 3.3.2 Sources of Information

- The source of data in the large datasets is varied. Apart from sensor data, other data originates from anything that has been scanned, entered, and released to the internet from sources such as:
    - Social media sites - Facebook, YouTube, WhatsApp, WeChat, TikTok, and Instagram
    - HTTP, Web pages, and search engines on the internet
    - Historical data from public and private archives
    - Metadata that is attached to emails, transmitted documents, and pictures
    - Medical forms, insurance forms, and tax forms
    - Genomics research using DNA
    - Collected data can be categorized as structured or unstructured

- Structured data is created by applications that use “fixed” format input such as spreadsheets or medical forms. Even if data is considered structured, different applications create files in different formats that are not necessarily compatible with one another. Structured data may need to be manipulated into a common format such as CSV
- Comma-separated values (CSV) files are a type of plaintext file that use commas to separate columns in a table of data, and the carriage return character to separate rows. Each row is a record. Although they are commonly used for importing and exporting in traditional databases and spreadsheets, there is no specific standard. JSON and XML are also plaintext file types that use a standard way of representing data records. These file formats are compatible with a wide range of applications. Converting data into a common format is a valuable way to combine data from different sources
- Unstructured data is generated in a “freeform” style such as audio, video, web pages, and tweets. Unstructured data requires different tools to prepare data for processing or analysis

- The following are two examples:
    - Web pages are created to provide data to humans, not machines. “Web scraping” tools automatically extract data from HTML pages. This is similar to a Web Crawler or spider of a search engine. It explores the web to extract data and create the database to respond to the search queries. Web scraping software may use Hypertext Transfer Protocol or a web browser to access the World Wide Web. Typically, web scraping is an automated process which uses a bot or web crawler to do data mining. Specific data is gathered and copied from the web to a database or spreadsheet. The data can then be easily analyzed
    - Many large web service providers such as Facebook provide standardized interfaces to collect the data automatically using application programming interfaces (APIs). The most common approach is to use RESTful APIs. RESTful APIs use HTTP as the communication protocol and JSON structure to encode the data. Internet websites like Google and Twitter gather large amounts of static and time series data. Knowledge of the APIs for these sites allow data analysts and engineers to access the large amounts of data that are constantly being generated on the internet

## 3.3.3 Data Visualization

- Data mining is the process of turning raw data into meaningful information by discovering patterns and relationships in large data sets
- To be of value, the mined data must be analyzed and presented to managers and decision makers. There are many different visualizations that can be used to present the value in the data. Determining the best chart to use will vary based on the following:
    - Number of variables to show
    - Number of data points in each variable
    - Is the data representing a timeline
    - Items that require comparisons
    - Some of the most popular chart types are line, column, bar, pie, and scatter

## 3.3.4 Chart Types and Uses

- Selectable image component. Select each item to show more information
- Click each image for more information about different types of charts and their uses

- Line Chart
    - Line charts are one of the most commonly used types of comparison charts. Use line charts when you have a continuous set of data, the number of data points is high, and you would like to show a trend in the data over time
- Scatter Plot
    - Scatter plots are very popular for correlation visualizations, or when you want to show the distribution of a large number of data points
- Pie Chart
    - Pie charts are used to show the composition of a static number. Segments represent a percentage of that number. The number of categories should be kept to a minimum. After ten or more segments, the slices begin to lose meaning and impact. The total sum of the segments must equal 100%
- Column Chart
    - Column charts are positioned vertically. They are probably the most common chart type used when you want to display the value of a specific data point and compare that value across similar categories
- Bar Chart
    - Bar charts are similar to column charts except they are positioned horizontally or vertically. Longer bars indicate larger numbers. They are best used when the names for each data point is long

## 3.3.5 Video: Hans Rosling: 200 years in 4 Minutes

- Data scientists transform overwhelming raw data into compelling information through data visualization. Search the internet for the video “Hans Rosling: 200 Countries, 200 Years, 4 Minutes”. In this narrated demonstration of interactive data visualization, Dr. Hans Rosling uses data visualization to illustrate the global relationship between wealth and life expectancy over a period of 200 years. Dr. Rosling brings the data to life by presenting a dynamic visualization that is supported by historical observations along the way

## 3.3.6 Analyzing Big Data for Effective Use in Business

- Big data is just that – BIG! It is most useful if you can analyze it to get value out of it. Data analysis is the process of inspecting, cleaning, transforming, and modeling data to uncover useful information. Analyzing big data typically requires tools and applications created for this purpose. These analysis tools have been designed to provide businesses with detailed information, patterns, and valuable insights
- Before beginning any analysis, it is critical to know what problem the business is trying to solve or what information the business is looking for. Are they interested in customer behavior in specific states, energy consumption patterns in different city quadrants, or the number of Facebook “likes” based on age?
- Having a strategy helps a business determine the type of analysis required and the best tool to do the analysis. A strategy also helps to determine the most effective way to present the results for management
- Tools and applications range from using an Excel spreadsheet or Google Analytics for small to medium data samples, to the applications dedicated to manipulating and analyzing really big datasets
- There are many desktop Big Data Analytics tools that businesses could select such as: Knime, OpenRefine, Orange, and RapidMiner. Cloud-based analytics tools include Google’s Big Query, IBM Cognos Analytics, TIBCO Spotfire, and Board

## 3.3.7 Lab – Use Excel to Forecast

- The following lab is an example of using an Excel spreadsheet to execute some forecasting on a small sampling of data. The Forecast menu option is available in recent versions of Excel. If you do not have this version, the formula is provided

## 3.3.8 Check Your Understanding - Big Data Terms

- Check your understanding of supporting business with big data by choosing the correct answer to the following questions

- 7 Quiz

## 3.3.9 Iota - Reflection

- So, all these Things are generating data, but what can we do with it? If you are in an area with air pollution, an air quality app on your smartphone can tell you when to avoid prolonged time outside. In some cities, waste management pick up routes get optimized using sensors that detect how full the garbage bins are
- Think about all the IoT data that you create as you move through your day. How might you make use of it? Entrepreneurs see opportunities in data! Big and small, data can show us what is happening, but more importantly it can show us where there is a need. Maybe it will give you an idea for a product or service that doesn’t even exist yet

## 3.4.1 Everything Generates Data Summary

- List of expandable sections. Select each button to expand the content
- What is Big Data?
- Big Data usually has three characteristics:
    - It is a large amount of data that increasingly requires more storage space (volume)
    - It is growing exponentially fast (velocity)
    - It is generated in different formats (variety)

- Where is Big Data Stored?
    - Edge computing is an architecture that utilizes end-user clients or “edge” devices to do a substantial amount of the pre-processing and storage required by an organization. Edge computing was designed to keep the data closer to the source for pre-processing

- The cloud is a collection of data centers or groups of connected servers giving anywhere, anytime access to software, storage, and services using a browser interface. Cloud services provide increased data storage as required and reduce the need for onsite IT equipment, maintenance, and management. They also reduce the cost of equipment, energy, physical plant requirements, and personnel training needs

- Distributed data processing takes large volumes of data from a source and breaks it into smaller pieces. These smaller data volumes are distributed in many locations to be processed by many computers with smaller processors. Each computer in the distributed architecture analyzes its part of the Big Data picture

- Supporting Business with Big Data
    - Businesses gain value by collecting and analyzing massive amounts of new product-usage data to understand the impact of their products and services, adjust their methods and goals, and provide their customers with better products faster

- Collected data can be categorized as structured or unstructured. Structured data is created by applications that use “fixed” format input such as spreadsheets or medical forms. Unstructured data is generated in a “freeform” style such as audio, video, web pages, and tweets. Both forms of data need to be manipulated into a common format to be analyzed. CSV, JSON, and XML are plaintext file types that use a standard way of representing data records. Converting data into a common format is a valuable way to combine data from different sources

- Data mining is the process of turning raw data into meaningful information by discovering patterns and relationships in large data sets. Data visualization is the process of taking the analyzed data and using charts such as line, column, bar, pie, or scatter to present meaningful information. A strategy helps a business determine the type of analysis required and the best tool to do the analysis. A strategy also helps to determine the most effective way to present the results for management

## 3.4.2 Everything Generates Data Quiz

- 14 Quiz

[Go to Next Module](./4_Everything_can_be_Automated.md)