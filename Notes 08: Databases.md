## Notes 08: Database

**Key Points**
+ A database is a repository for data
+ database management system (DBMS): a collection of programs that enables users to create and maintain databases and control all access to them
+ concurrency control strategies: features of a database that allow several users access to the same data item at the same time
+ NoSQL is an approach to databases that represents a shift away from traditional relational database management systems (RDBMS). To define NoSQL, it is helpful to start by describing SQL, which is a query language used by RDBMS. Relational databases rely on tables, columns, rows, or schemas to organize and retrieve data. In contrast, NoSQL databases do not rely on these structures and use more flexible data models
+ NoSQL databases are better for scalability, performance, high availability and Flexible Data Modeling
+  SQL databases have there own launguage to slect or manipulate data
+ There a multiple comapnys that use Amazon RDS airbnb to bandai namco a gaiming company
+ On-Demand Instances – Pay by the hour for the DB instance hours that you use. Pricing is listed on a per-hour basis, but bills are calculated down to the second and show times in decimal form. RDS usage is now billed in one second increments, with a minimum of 10 minutes.
  
**Identify 2 Quotes that are intresting**
+ One quote i actually found very intresting is the fact how they talk about SQL can do more than slecting and deleting "The most common language used in relational databases for queries is the Structured Query Language or SQL for short. SQL is a standard language for selecting, inserting, updating, and deleting data in a relational database. It can do more but the majority of the work in a system is done using SELECT, INSERT, UPDATE, and DELETE."(10.05, Query for Data). The reason i really like this quote is actually because you can do a lot of things with sql and even use its own launguage against itself like sql injections
+ Another quote i would like to point out is "To address the challenges of running an unmanaged, standalone relational database, AWS provides a service that sets up, operates, and scales the relational database without any ongoing administration. Amazon RDS provides cost-efficient and resizable capacity, while automating time-consuming administrative tasks"(10.09,Amazonn RDS as a managed service). The reason i like this quote is due to the fact that they take care oof mostly everything for you so all you have to worry about is setting up the structure of the dataabse and input data without having to worry about the backups and tedious work

**Outline new facts that i learned from this section**
Some new facts i have ended up learning from this section are noSQL databases i have heard of them before bvut i have never knew that they actually have there advantages and excel quite a bit over traditional databases. Another fact i would to outline is how easy it is to set up databases in AWS and how much they excel of making the DEVOPS team a lot easier but taking care of the nitty grity


**What question remain after reading the section**
A question i have is how many types of sql and nosql databases do they provide in there services like postgres sql or sqlite3?
