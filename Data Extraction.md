## Extraction

- ETL data extraction is the first step in the ETL process, which stands for **extract**, **transform**, and **load**. 
- It involves retrieving data from various sources, such as **databases**, **flat files**, **log files**, and **APIs**.
- The extracted data is then prepared for further processing in the **transformation** step.

### **ETL Data Extraction Concepts**

1. **Data Source Identification:**
- Identify all **relevant** data sources that need to be integrated.
- This includes understanding each source's **data structure**, **format**, and **location**.

2. **Data Access Methods:**
- Different data sources may require different access methods to extract data.
- For instance, relational databases may use **JDBC** or **ODBC** connectors.
- Flat files may require simple file read APIs, or simple Python script.

3. **Data Extraction Strategies:**
- **Full Batch Extraction:** Extracting all data from the source simultaneously.
- **Incremental Extraction:** Extracting only the data that has changed since the last extraction. (Large datasets that are frequently updated)
- **Real-time Extraction:** Extracting data as it is generated from the source. (Real-time applications)

4. **Data Quality Checks:**
- Data quality checks are crucial during extraction to ensure the data is accurate, consistent, and complete.
- This may involve validating data formats, identifying missing values, and checking for anomalies.

### **ETL Data Extraction Techniques**

1. **Native APIs:**
- Many data sources provide native APIs for extracting data.
- Most efficient and reliable way to extract data from the source.

2. **Data Connectors:**
- Data connectors are software tools that act as intermediaries between the ETL process and various data sources.
- They provide a standardized interface for extracting data from diverse sources, regardless of their underlying technology.

3. **Custom Scripts:**
- Scripts are typically written in programming languages like Python or Java and tailored to the specific data source's format and access methods.

4. **Web Scraping:**
- Extracting data from websites, parsing HTML code to extract specific data elements from web pages.

5. **Data Migration Tools:**
- Specialized software applications designed to extract, transform, and load data from legacy systems or complex data environments.

### **Considerations for ETL Data Extraction**

1. **Performance:**
- Data extraction should be optimized for performance to minimize the impact on source systems and overall ETL processing time.

2. **Security:**
- Data extraction processes should protect sensitive data from unauthorized access or disclosure.

3. **Error Handling:**
- Robust error-handling mechanisms should be in place to handle unexpected conditions during extraction.

4. **Data Lineage:**
- Data lineage tracking is crucial for understanding the origin and transformation of extracted data.

5. **Scalability:**
- Data extraction processes should be scalable to handle increasing data volumes and evolving data sources.
