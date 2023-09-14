# SIMPLE-ETL-PROCESS
Simple ETL (Extract, Transform and Load) using MATLAB 

## Extraction:
This step involves reading data from various sources, which can include text files, databases, web services, APIs, and more.

## Transformation: 
After extracting the data, you perform various operations and calculations on it to clean, format, and structure it in a way that is suitable for your analysis or reporting needs. This may include data cleansing, aggregations, filtering, and calculations. 

## Loading:
Once the data is transformed and prepared, it is loaded into the destination system. Loading can involve appending or replacing data, creating new, or updating existing ones.

ETL processes can be implemented using various tools and programming languages, depending on your specific requirements. Common tools for ETL include Apache Nifi, Apache Spark, Talend, Microsoft SSIS (SQL Server Integration Services), Python with libraries like Pandas, and many others.

##TASK
 In this task we are gonna process the Biometric data. At first it is in .log file then converted into .txt files using Biometric DataLog Software.Here we are gonna process that text files.
 Coming to the pratical work, 
 1. At first we are going to read the textfiles from the nexted folders.(Extraxt)
 2. Then preprocessing and cleaning the file which was read, after those processes some measures like Minimum Alveolar Concentration(MAC) value is calculated.(Transform)
 3. After calculating some measures, saving or loading those calculated measures into the our specified format that is loading those MAC values in the EXCEL sheet.
