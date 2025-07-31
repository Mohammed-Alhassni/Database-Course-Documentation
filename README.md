# Database-Course-Documentation

## Task 1-Comparison:  Flat File Systems vs. Relational Databases: 
| **Aspect**          | **Flat File Systems**                                                        | **Relational Databases**                                                                                 |
| ------------------- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Structure**       | Data is stored in plain text or CSV format with no formal schema.            | Organized in tables with rows and columns, and follows a defined schema (data types, constraints, keys). |
| **Data Redundancy** | High redundancy – the same data may be repeated in multiple files.           | Low redundancy – normalization reduces duplicate data using keys and relations.                          |
| **Relationships**   | No built-in support for relationships between data.                          | Supports complex relationships using primary and foreign keys.                                           |
| **Example Usage**   | Simple storage like log files, configuration files, or small personal lists. | Business systems like customer management, inventory tracking, banking, etc.                             |
| **Drawbacks**       | - Poor scalability and data integrity                                        |   Difficult to query and maintain, - Requires database software and administration, More complex setup and maintenance                                                                                                        |

## Task 2 Mind Map:  DBMS Advantages: 

<img width="912" height="613" alt="Screenshot 2025-07-31 at 10 18 54 AM" src="https://github.com/user-attachments/assets/2f9103da-a591-4a51-8915-3e3c9e94cf72" />

## Task 3:  Roles in a Database System:


**• 🧩 System Analyst**
Gathers user requirements, analyzes business needs, and defines system specifications for the database solution.

**• 🗂 Database Designer**
Creates the logical and physical database models (tables, relationships, keys) based on requirements.

**• 💻 Database Developer**
Writes SQL code, stored procedures, and implements the database design to build the actual database system.

**• 🛠️ Database Administrator (DBA)**
Manages, secures, monitors, and maintains the database environment; handles backups and performance tuning.

**• 📱 Application Developer**
Builds the front-end or back-end application that interacts with the database (e.g., websites, mobile apps).

**• 📊 BI (Business Intelligence) Developer**
Develops reports, dashboards, and data analysis tools to help organizations make data-driven decisions.


## Task 4:  Types of Databases:

🔗 **Relational vs. Non-Relational Databases**

| **Aspect**         | **Relational**                    | **Non-Relational**                          |
| ------------------ | --------------------------------- | ------------------------------------------- |
| **Structure**      | Table-based with rows and columns | Document, key-value, graph, or wide-column  |
| **Schema**         | Fixed schema                      | Flexible schema                             |
| **Scalability**    | Vertical scaling (scale up)       | Horizontal scaling (scale out)              |
| **Query Language** | SQL                               | Varies (e.g., MongoDB uses BSON queries)    |
| **Examples**       | MySQL, PostgreSQL, Oracle         | MongoDB (document), Cassandra (wide-column) |
| **Best For**       | Structured data, transactions     | Unstructured or semi-structured data        |

📌 Use Cases:

Relational: Banking systems, ERP, Inventory

Non-Relational: Social media feeds, IoT data, real-time analytics


🧭 **Centralized vs. Distributed vs. Cloud Databases**

| **Type**        | **Description**                                                            | **Use Case Examples**                                 |
| --------------- | -------------------------------------------------------------------------- | ----------------------------------------------------- |
| **Centralized** | All data stored and managed in a single location/server                    | Small companies, single-location apps, legacy systems |
| **Distributed** | Data spread across multiple servers or locations, often with replication   | Global applications, e-commerce platforms             |
| **Cloud**       | Hosted on cloud platforms (e.g., AWS, Azure), accessible over the internet | Scalable web apps, mobile apps, data-driven SaaS      |

📌 Examples:

Centralized: MS Access, early Oracle setups

Distributed: Apache Cassandra, Google Spanner

Cloud: Amazon RDS, Google Cloud Firestore, MongoDB Atlas

## Task 5:  Types of Databases:

**📦 What is Cloud Storage and How Does It Support Databases?**
Cloud Storage refers to storing data on remote servers accessed via the internet, rather than local hardware.

It provides scalable, durable, and accessible storage.
Cloud storage supports databases by:
Hosting the physical data files of cloud-based databases.
Enabling backup, replication, and disaster recovery.
Providing infrastructure for database-as-a-service (DBaaS) platforms like Amazon RDS or Azure SQL.

**✅ Advantages of Cloud-Based Databases**

Scalability
Easily scale storage and computing power as demand grows.
High Availability
Redundant storage and automated failover ensure minimal downtime.
Managed Services
Cloud providers handle patching, backups, and maintenance.
Accessibility
Access databases from anywhere with internet connectivity.
Cost Efficiency
Pay-as-you-go pricing—no need for expensive hardware.
Security
Enterprise-level encryption, identity access management (IAM), and compliance features.

**Examples:**

Azure SQL Database – fully managed SQL engine on Microsoft cloud.
Amazon RDS – supports multiple database engines (MySQL, PostgreSQL, Oracle).
Google Cloud Spanner – globally distributed SQL database with high consistency.

**⚠️ Disadvantages or Challenges**

Internet Dependency
Requires stable internet connectivity for access.
Latency Issues
Data transfer times may be slower than local access in high-speed apps.
Vendor Lock-In
Migrating between cloud platforms can be complex and costly.
Security and Compliance Risks
Sensitive data in the cloud may face regulatory or legal concerns.
Cost Overruns
Uncontrolled usage or poor configuration can lead to high costs.

