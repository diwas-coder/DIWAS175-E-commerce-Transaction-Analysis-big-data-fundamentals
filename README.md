# DIWAS175-E-commerce-Transaction-Analysis-big-data-fundamentals
Big Data project using Hadoop (HDFS, MapReduce, Hive) to analyze e-commerce transactions and identify top-selling products and peak sales time.
      E-Commerce Transaction Analysis using Hadoop 
Big Data Fundamentals Project 
Implemented using Hadoop Ecosystem (HDFS, MapReduce, Hive) 
 
     Project Overview 
This project demonstrates a complete Big Data processing pipeline to analyze e-commerce 
transaction data using the Hadoop ecosystem. 
With the rapid growth of online shopping platforms, large volumes of transaction data are 
generated daily. Traditional systems struggle to process such data efficiently. 
This project solves that problem using distributed computing techniques to extract meaningful 
insights such as: 
• Top-selling products  
• Peak sales time  
 
       Objectives 
• To store large datasets using HDFS  
• To process data using MapReduce (Python)  
• To perform analytical queries using Hive  
• To understand distributed data processing  
• To generate insights from raw data  
 
        Architecture 
Raw CSV Dataset 
        ↓ 
HDFS (Storage Layer) 
        ↓ 
MapReduce (Processing Layer) 
        ↓ 
Processed Output (HDFS) 
        ↓ 
Hive (Analysis Layer) 
        ↓ 
Insights (Top Products & Peak Time) 
 
    Technologies & Tools Used 
• HDFS (Storage Layer)  
• MapReduce (Data Processing)  
• Hive (Data Analysis)  
• Python  
• Linux / Cloudera  
• ChatGPT (Generative AI Assistance)  
 
      Dataset Information 
The dataset contains e-commerce transaction details used for sales analysis. 
     Key Attributes: 
• order_id – Unique order ID  
• product – Product name  
• price – Price of product  
• quantity – Quantity sold  
• date – Transaction date  
• time – Transaction time  
 
    Workflow Explanation 
• The dataset is stored in HDFS for distributed storage  
• MapReduce processes the data to calculate total sales per product  
• Processed data is stored back in HDFS  
• Hive is used to analyze and query the results  
• Final insights such as top-selling products and peak time are generated  
 
    Output 
• Total quantity sold for each product  
• Identification of top-selling product  
• Peak sales time (hour-wise analysis)  
• Structured insights from raw data  
 
         Use of Generative AI 
Generative AI played an important role in this project: 
• Code generation (Mapper & Reducer)  
• Debugging support  
• Hive query assistance  
• Concept understanding of Big Data tools  
 
     Validation 
All generated code and outputs were: 
• Manually tested  
• Verified for correctness  
• Successfully executed in the Hadoop environment  
 
       Key Features 
• Scalable Big Data processing  
• Efficient handling of large datasets  
• Distributed computing approach  
• Integration of AI for enhanced productivity  
 
       Conclusion 
This project successfully demonstrates how the Hadoop ecosystem can be used to process and 
analyze e-commerce data efficiently. 
By combining HDFS, MapReduce, and Hive, the system transforms raw transaction data into 
meaningful insights such as top-selling products and peak sales time. 
 
                        Author 
DIWAS PAL
 
  Final Note 
This project represents a real-world Big Data solution where distributed computing helps in 
handling large-scale data efficiently and supports data-driven decision-making. 
