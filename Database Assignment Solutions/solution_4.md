## Explain 5 challenges of file-based storage system which was tackled by DBMS.

Here are five challenges of file-based storage systems that were effectively addressed by Database Management Systems (DBMS):

1. **Data Redundancy and Inconsistency**:
   - Challenge: In file-based systems, data redundancy is common as the same data may be stored in multiple files or locations, leading to inconsistency and wasted storage space.
   - Solution with DBMS: DBMS employs normalization techniques to eliminate redundancy and ensure data consistency. By organizing data into tables and enforcing relationships between them, DBMS reduces redundancy and maintains data integrity.

2. **Data Dependency and Lack of Data Independence**:
   - Challenge: In file-based systems, application programs are tightly coupled with the underlying data storage format and structure. Any changes to the data structure require corresponding modifications to application code, leading to maintenance difficulties and potential errors.
   - Solution with DBMS: DBMS provides data independence by separating the logical schema (conceptual schema) from the physical storage schema (internal schema). This allows changes to the database schema without affecting the applications that access it, improving flexibility and ease of maintenance.

3. **Limited Data Retrieval and Querying Capabilities**:
   - Challenge: File-based systems offer limited querying capabilities, making it challenging to retrieve specific data or perform complex queries.
   - Solution with DBMS: DBMS provides powerful querying capabilities through query languages such as SQL (Structured Query Language). Users can write queries to retrieve, filter, sort, and aggregate data from the database, enabling efficient data retrieval and analysis.

4. **Concurrency and Data Integrity Issues**:
   - Challenge: In multi-user environments, file-based systems may encounter concurrency issues when multiple users attempt to access or modify the same data simultaneously, leading to data inconsistency or corruption.
   - Solution with DBMS: DBMS implements concurrency control mechanisms such as locking and transaction management to ensure data consistency and integrity. It allows multiple users to access and modify data concurrently while preventing conflicts and maintaining data consistency.

5. **Limited Security and Access Control**:
   - Challenge: File-based systems often lack robust security features, making it difficult to control access to sensitive data and protect against unauthorized access or breaches.
   - Solution with DBMS: DBMS provides comprehensive security features such as user authentication, access control, encryption, and auditing mechanisms to safeguard data from unauthorized access and ensure compliance with security regulations.

Overall, DBMS addresses these challenges by providing a centralized, structured, and secure environment for storing, managing, and accessing data, making it an essential tool for modern data management in various industries and applications.