# Advanced database system

## Database models

Database Management System, contains:

* collection of interrated data.
* set of programs to access data.
* environment to use.

### Drawbacks of using file systems to store data

* multiple file formats, duplication of info in different files.
* difficulty to access data, you have to write new program to do each new task.
* hard to add new constraints/change existing ones.

### Levels of abstraction

1. physical level: describes how a record is stored.
2. logical level: describes data stored in database, and relationships among the data.
3. view level: application programs hide details of data types.

#### DBMS example

* MySQL
* PostgreSQL
* Microsoft Access

### Logical and physical data independence

It is the ability to change the schema at one level of the database without changing the schema at the next higher level.

### Database design process

1. Requirement analysis: user needs
2. Conceptual design: using E/R model
3. Logical design: translate E/R model to relational schema
4. Schema refinement: check schema for redundancies and anomalies
5. Physical design/tuning: consider typical workloads, and further optimise.

### Database model

It is a data model that determines the logical structure of a database.

#### Hierarchical model

it is model that data are organized in a tree-like structure.

each record has only one parent, whereas a parent can have more than child records.

#### Network Model

It is database model that allows multiple records to the same owner file, defined as many to many relationship because one owner file can be linked to many member files and vice versa.

### Relational database

#### advantages of relational databases

* categorizing data
* accuracy, data is stored once,eliminating data duplication
* ease of use
* collaboration, multiple users can access the same database
* security, access to db is limited to specific users.

#### disadvatages of relational databases

* structure
* maintenance issues
* inflexibility
* lack of scalability

### Factors to consider when selecting a database

* ACID(Atomicity, Consistency, Isolation, Durability) vs BASE(Basic, Availability, Soft-state, Eventual consistency) database engine.
* Availability
* Disaster recovery
* Performance
* Complementary technologies
* ETL
* Infrastructure options
* vendors
* monitoring and alerts
