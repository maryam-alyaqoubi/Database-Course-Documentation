# Database Course Documentation

---

## 1. Flat File Systems vs. Relational Databases

Flat file systems store data in plain files, usually in a simple tabular or text format. They are easy to create and understand, but they often suffer from problems like data redundancy, since the same information may be repeated multiple times. Relationships between data are not supported in flat files, which makes it difficult to handle complex data connections. These systems are usually used for small applications or simple storage needs.

On the other hand, relational databases organize data into structured tables with defined relationships. This approach reduces redundancy by normalizing data, improves data integrity, and allows for powerful querying using SQL. Relational databases are widely used in business applications, financial systems, and web applications because they handle large and complex datasets effectively. However, they require more setup and administration compared to flat files.

---

## 2. Advantages of Database Management Systems (DBMS)

A Database Management System (DBMS) offers many advantages that make it essential for modern applications. It provides strong security by controlling access to data, ensuring only authorized users can view or modify it. DBMS also ensures data integrity, maintaining accuracy and consistency across records. Regular backups can be scheduled to prevent data loss, while built-in features help reduce redundancy by organizing data efficiently.

Another key advantage is concurrency, allowing multiple users to access and modify the database at the same time without conflicts. Finally, DBMS enables data sharing across different applications and teams, improving collaboration and efficiency. These features make DBMS a reliable and scalable solution for organizations of all sizes.

### DBMS Advantages Mind Map

![DBMS Advantages Mind Map](./map.png)

---

## 3. Roles in a Database System

Several roles work together to design, develop, and manage a database system. A **System Analyst** studies business needs and defines what the database should achieve. The **Database Designer** creates the structure of the database, including tables, relationships, and constraints. A **Database Developer** builds the database using the design, implementing queries, procedures, and other components.

The **Database Administrator (DBA)** manages the database, ensuring it runs smoothly, performs well, and remains secure. An **Application Developer** creates software that interacts with the database, providing interfaces for users. Finally, a **Business Intelligence (BI) Developer** uses database data to build reports and dashboards, helping organizations make informed decisions.

Each role is essential for creating a functional and useful database system.

---

## 4. Types of Databases

Databases come in different types based on their structure and purpose. **Relational databases** use structured tables and relationships, making them ideal for applications that need consistent and organized data.

**Non-relational databases**, such as MongoDB and Cassandra, are more flexible, storing data as documents, key-value pairs, or graphs, and are commonly used for big data and real-time applications.

Databases can also be categorized by their deployment:  
- **Centralized databases** are stored in one location.  
- **Distributed databases** spread data across multiple servers for better performance and reliability.  
- **Cloud databases** are hosted online, offering scalability and easy access.

Each type has its own use cases, from traditional business systems to large-scale web applications.

---

## 5. Cloud Storage and Databases

Cloud storage provides a way to store and access data over the internet, making it an important component for cloud-based databases. Cloud databases, such as Azure SQL, Amazon RDS, and Google Cloud Spanner, combine the benefits of database systems with the flexibility of the cloud.

They offer scalability, allowing organizations to expand storage and processing power as needed, and cost efficiency, since they reduce the need for physical hardware. Additionally, cloud-based databases provide automatic backups and disaster recovery options.

However, there are challenges, such as dependency on internet connectivity, potential security risks, and ongoing subscription costs. Despite these challenges, cloud databases are widely used due to their convenience and efficiency.

---

