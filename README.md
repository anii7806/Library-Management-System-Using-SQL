# Library-Management-System-Using-SQL
In this project, I applied my skills in SQL and database design to develop a structured and scalable schema for a Library Management System. The goal was to design a relational database that could efficiently manage users, books, authors, publishers, and the circulation process within a library environment.

I began by creating a new schema called library_management to logically separate and organize all related tables. I followed the principles of normalization to avoid data redundancy and ensure data integrity. Each table was carefully designed with appropriate primary keys, data types, and foreign key constraints to model real-world relationships accurately.

For instance, the books table includes foreign keys referencing the author and publisher tables to maintain consistent linkages between books and their creators. The readers table stores user-specific information, including registration details, issue history, and fines. The books_issue table tracks book circulation, associating each issued book with a reader, and managing due dates and fines.

I also implemented a settings table to store configurable rules such as the number of books a reader can issue, fine per day, and allowed return period. This design provides flexibility for library administrators to update policies without modifying the database structure.

Furthermore, the schema includes dedicated tables for staff and user_login to manage administrative access and user authentication. Data types were chosen to align with the expected inputs—for example, BOOLEAN for availability and activity status, and DATE and TIME for tracking temporal data.

Overall, this project demonstrated my ability to apply relational database design, data modeling, and SQL skills to build a functional system tailored to real-world requirements, laying the foundation for further development of a complete library management application.
