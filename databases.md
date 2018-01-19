## **Databases**

### **Database**

is a collection of information stored and used by the software, organized in a way that can be easily managed. Traditional databases are organized by fields, records, and files.

### **Relational Database**

is a database organized with the relational model. Relationships are a logical connection between different tables established on the basis of interaction among these tables. All relational databases use SQL \(Structured Query Language\) to operate on data \(insert, update, load\). Looks like a spreadsheet. Examples: Oracle, MySQL, Postgres, SQL Server. Read more:[ Wikipedia](https://en.wikipedia.org/wiki/Relational_database)

### **NoSQL Database**

non relational or non SQL database. Unlike relational databases it uses other forms than tabular data like key-value collections, multi-level structures, graphs, etc. Such databases are usually chosen for their performance, scalability and flexibility in schema design.

### **CAP theorem**

states that it is impossible for a distributed data store to simultaneously provide more than two out of the following three guarantees: consistency \(every read receives the most recent write or an error\), availability \(every request receives a non-error response without guarantee that it contains the most recent write\) and partition tolerance \(the system continues to operate despite an arbitrary number of messages being dropped or delayed by the network between nodes\). In other words, CAP theorem states that in the presence of a network partition, one has to choose between consistency and availability. Read more: [Wikipedia](https://en.wikipedia.org/wiki/CAP_theorem)

### **ACID**

Atomicity, Consistency, Isolation, Durability. A set of properties related to the database engines guaranteeing after finishing modification data will be consistent. Read more: [Wikipedia](https://en.wikipedia.org/wiki/ACID)

