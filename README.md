# Microsoft-curriculum-bootcamp

### Data Science for Beginners
#### Review of Defining Data
What I have learned in this lesson
- What data is
- How data is described
- How data is classified and categorized
- Where data can be found

##### Quantitative Data
- In a dataset, quantitative data refers to numerical observations that can often be quantified, analysed, and used mathematically. The population of a nation, a person's height, or a company's quarterly profits are a few examples of quantitative data. 
- Quantitative data might be used to determine seasonal variations in the Air Quality Index (AQI) or calculate the probability of rush hour traffic on an average workday.

##### Qualitative Data
- Data that cannot be measured objectively, such as observations of quantitative data, are known as qualitative data, also known as categorical data. 
A product's or process's quality can often be captured using a variety of subjective data types. 
- Like phone numbers or timestamps, some qualitative data can be numerical but not commonly employed mathematically. Qualitative data includes things like video comments, a car's model, or the colour that your closest friends like best. Qualitative data may be used to find common job application resume keywords.

##### Structured Data
- Data that is organised into rows and columns, with the same set of columns in each row, is known as structured data. Rows hold the actual values, whereas columns indicate a value of a specific type and will be recognised with a label defining what the value represents. 
- In order to guarantee that the values appropriately reflect the column, columns frequently contain a specific set of restrictions or rules on the values. Consider a spreadsheet of customers where each row is required to have a phone number and where the phone digits are never alphabetical. To ensure that the phone number column never contains nothing but numbers, restrictions may be applied to it (phone number column).
- Relating structured data to other structured data is one advantage of structured data organisation. However, since the data is designed to be structured in a particular way, altering its overall structure may require a lot of work. You must plan how you will add these values to the current rows of customers in the dataset, for instance, if you add an email column to the customer spreadsheet that cannot be empty.
- Spreadsheets, relational databases, phone numbers, and bank statements are examples of structured data.

##### Unstructured Data
- Unstructured data generally lacks a standard or set of rules to follow and can't be organised into rows or columns. In contrast to a structured dataset, unstructured data has less constraint on its structure, making it simpler to add new information. 
- It is not necessary to change the existing data if a sensor capturing barometric pressure data every two minutes has been updated to monitor and record temperature.
- Text files, text messages, video files are examples of unstructured data.

##### Semi-structured
- Semi-structured data combines elements of both organised and unstructured data. It is organised in a way that is considered structured and may adhere to a prearranged pattern or set of principles, but often does not follow a format of rows and columns. 
- The structure will differ depending on the source, ranging from a clearly defined hierarchy to something more adaptable that makes it simple to incorporate new information. 
- Based on the type of data, metadata will have various names and serve as indicators for how the data is kept and arranged. Tags, elements, entities, and attributes are a few of the frequent names for metadata. For example, an email message has a topic, a body, and a list of recipients. It can also be classified according to whom and when it was delivered.
- HTML, CSV files, JavaScript Object Notation (JSON) are examples of semi-structured data.


#### Working with Relational Data
What I have learned in this lesson
- A collection of columns and rows called table, are the foundation of a relational database. Much like a spreadsheet. 
- The shortcomings of a single table approach
- The concepts of relationships
- Retrieving the data
- Joining data

##### The shortcomings of a single table approach
- Having numerous copies of that would be entirely unnecessary and may consume a significant amount of storage. 
- While doing so prevents row duplication, it adds a few new challenges. For this reason, we require multiple tables and relationships. By segmenting our data, we can prevent duplication and increase our flexibility in the data.

##### The concepts of relationships

- We require a "Primary Key(PK)", "id", and the database terms. A primary key is a value that can be used to locate a particular table row. 
- We need to choose the best way to reference each city before applying to table.
- The name of the city, for instance, could be used as the basis for this, although it should nearly always be a number or other identifier. 
- The relationship would end if the id ever changed, thus we do not want it to happen.
- DataFrames do not use the terminology of "primary key"

##### Retrieving the data
##### Joining data











### Python
### Fronted Bootcamp
### Web Dev for Beginners 
### Machine Learning for Beginners 
### AI for Beginners 
### IoT for beginners 
### XR Development for Beginners 
