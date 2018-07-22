# Summary

* [Introduction](README.md)
* [Preface and Legal Notices](preface-and-legal-notices.md)
  * [1 General Information](preface-and-legal-notices/1-general-information.md)
    * 1.1 About This Manual 
    * [1.2 Typographical and Syntax Conventions](preface-and-legal-notices/1-general-information/12-typographical-and-syntax-conventions.md)
    * [1.3 Overview of the MySQL Database Management System](preface-and-legal-notices/1-general-information/13-overview-of-the-mysql-database-management-system.md)
      * 1.3.1 What is MySQL? 
      * 1.3.2 The Main Features of MySQL 
      * 1.3.3 History of MySQL 
    * 1.4 What Is New in MySQL 5.7
    * 1.5 Server and Status Variables and Options Added, Deprecated, or Removed in MySQL 5.7
    * [1.6 MySQL Information Sources](preface-and-legal-notices/1-general-information/16-mysql-information-sources.md)
      * 1.6.1 MySQL Websites
      * 1.6.2 MySQL Mailing Lists
      * 1.6.3 MySQL Community Support at the MySQL Forums
      * 1.6.4 MySQL Community Support on Internet Relay Chat \(IRC\)
      * 1.6.5 MySQL Enterprise
    * 1.7 How to Report Bugs or Problems 
    * [1.8 MySQL Standards Compliance](preface-and-legal-notices/1-general-information/18-mysql-standards-compliance.md)
      * 1.8.1 MySQL Extensions to Standard SQL
      * 1.8.2 MySQL Differences from Standard SQL
      * 1.8.3 How MySQL Deals with Constraints
    * [1.9 Credits](preface-and-legal-notices/1-general-information/19-credits.md)
      * 1.9.1 Contributors to MySQL
      * 1.9.2 Documenters and translators
      * 1.9.3 Packages that support MySQL
      * 1.9.4 Tools that were used to create MySQL
      * 1.9.5 Supporters of MySQL
  * [2 Installing and Upgrading MySQL](preface-and-legal-notices/2-installing-and-upgrading-mysql.md)
    * [2.1 General Installation Guidance](preface-and-legal-notices/2-installing-and-upgrading-mysql/21-general-installation-guidance.md)
      * 2.1.1 Which MySQL Version and Distribution to Install
      * 2.1.2 How to Get MySQL
      * 2.1.3 Verifying Package Integrity Using MD5 Checksums or GnuPG
      * 2.1.4 Installation Layouts
      * 2.1.5 Compiler-Specific Build Characteristics
    * 2.2 Installing MySQL on Unix/Linux Using Generic Binaries
    * [2.3 Installing MySQL on Microsoft Windows](preface-and-legal-notices/2-installing-and-upgrading-mysql/23-installing-mysql-on-microsoft-windows.md)
      * 2.3.1 MySQL Installation Layout on Microsoft Windows
      * [2.3.2 Choosing an Installation Package](232-choosing-an-installation-package.md)
      * 2.3.3 MySQL Installer for Windows
      * 2.3.4 MySQL Notifier
      * 2.3.5 Installing MySQL on Microsoft Windows Using a noinstall ZIP Archive
      * 2.3.6 Troubleshooting a Microsoft Windows MySQL Server Installation
      * 2.3.7 Windows Postinstallation Procedures
      * 2.3.8 Upgrading MySQL on Windows
      * 2.3.9 Deploying MySQL on Windows and Other Non-Linux Platforms
    * [2.4 Installing MySQL on macOS](preface-and-legal-notices/2-installing-and-upgrading-mysql/24-installing-mysql-on-macos.md)
      * 2.4.1 General Notes on Installing MySQL on macOS
      * 2.4.2 Installing MySQL on macOS Using Native Packages
      * 2.4.3 Installing a MySQL Launch Daemon
      * 2.4.4 Installing and Using the MySQL Preference Pane
    * [2.5 Installing MySQL on Linux](preface-and-legal-notices/2-installing-and-upgrading-mysql/25-installing-mysql-on-linux.md)
      * 2.5.1 Installing MySQL on Linux Using the MySQL Yum Repository
      * 2.5.2 Replacing a Third-Party Distribution of MySQL Using the MySQL Yum Repository
      * 2.5.3 Installing MySQL on Linux Using the MySQL APT Repository
      * 2.5.4 Installing MySQL on Linux Using the MySQL SLES Repository
      * 2.5.5 Installing MySQL on Linux Using RPM Packages from Oracle
      * 2.5.6 Installing MySQL on Linux Using Debian Packages from Oracle
      * 2.5.7 Deploying MySQL on Linux with Docker
      * 2.5.8 Installing MySQL on Linux from the Native Software Repositories
      * 2.5.9 Installing MySQL on Linux with Juju
      * 2.5.10 Managing MySQL Server with systemd
    * 2.6 Installing MySQL Using Unbreakable Linux Network \(ULN\)
    * [2.7 Installing MySQL on Solaris](preface-and-legal-notices/2-installing-and-upgrading-mysql/27-installing-mysql-on-solaris.md)
      * 2.7.1 Installing MySQL on Solaris Using a Solaris PKG
    * 2.8 Installing MySQL on FreeBSD
    * [2.9 Installing MySQL from Source](preface-and-legal-notices/2-installing-and-upgrading-mysql/29-installing-mysql-from-source.md)
      * 2.9.1 MySQL Layout for Source Installation
      * 2.9.2 Installing MySQL Using a Standard Source Distribution
      * 2.9.3 Installing MySQL Using a Development Source Tree
      * 2.9.4 MySQL Source-Configuration Options
      * 2.9.5 Dealing with Problems Compiling MySQL
      * 2.9.6 MySQL Configuration and Third-Party Tools
    * [2.10 Postinstallation Setup and Testing](preface-and-legal-notices/2-installing-and-upgrading-mysql/210-postinstallation-setup-and-testing.md)
      * [2.10.1 Initializing the Data Directory](preface-and-legal-notices/2-installing-and-upgrading-mysql/210-postinstallation-setup-and-testing/2101-initializing-the-data-directory.md)
      * 2.10.2 Starting the Server
      * 2.10.3 Testing the Server
      * 2.10.4 Securing the Initial MySQL Account
      * 2.10.5 Starting and Stopping MySQL Automatically
    * [2.11 Upgrading or Downgrading MySQL](preface-and-legal-notices/2-installing-and-upgrading-mysql/211-upgrading-or-downgrading-mysql.md)
      * 2.11.1 Upgrading MySQL
      * 2.11.2 Downgrading MySQL
      * 2.11.3 Rebuilding or Repairing Tables or Indexes
      * 2.11.4 Copying MySQL Databases to Another Machine
    * [2.12 Perl Installation Notes](preface-and-legal-notices/2-installing-and-upgrading-mysql/212-perl-installation-notes.md)
      * 2.12.1 Installing Perl on Unix
      * 2.12.2 Installing ActiveState Perl on Windows
      * 2.12.3 Problems Using the Perl DBI/DBD Interface
  * [3 Tutorial](preface-and-legal-notices/3-tutorial.md)
    * 3.1 Connecting to and Disconnecting from the Server
    * 3.2 Entering Queries
    * [3.3 Creating and Using a Database](preface-and-legal-notices/3-tutorial/33-creating-and-using-a-database.md)
      * 3.3.1 Creating and Selecting a Database
      * 3.3.2 Creating a Table
      * 3.3.3 Loading Data into a Table
      * 3.3.4 Retrieving Information from a Table
    * 3.4 Getting Information About Databases and Tables
    * 3.5 Using mysql in Batch Mode
    * [3.6 Examples of Common Queries](preface-and-legal-notices/3-tutorial/36-examples-of-common-queries.md)
      * 3.6.1 The Maximum Value for a Column
      * 3.6.2 The Row Holding the Maximum of a Certain Column
      * 3.6.3 Maximum of Column per Group
      * 3.6.4 The Rows Holding the Group-wise Maximum of a Certain Column
      * 3.6.5 Using User-Defined Variables
      * 3.6.6 Using Foreign Keys
      * 3.6.7 Searching on Two Keys
      * 3.6.8 Calculating Visits Per Day
      * 3.6.9 Using AUTO\_INCREMENT
    * 3.7 Using MySQL with Apache
  * [4 MySQL Programs](preface-and-legal-notices/4-mysql-programs.md)
    * 4.1 Overview of MySQL Programs
    * [4.2 Using MySQL Programs](preface-and-legal-notices/4-mysql-programs/42-using-mysql-programs.md)
      * 4.2.1 Invoking MySQL Programs
      * 4.2.2 Connecting to the MySQL Server
      * 4.2.3 Specifying Program Options
      * 4.2.4 Using Options on the Command Line
      * 4.2.5 Program Option Modifiers
      * 4.2.6 Using Option Files
      * 4.2.7 Command-Line Options that Affect Option-File Handling
      * 4.2.8 Using Options to Set Program Variables
      * 4.2.9 Option Defaults, Options Expecting Values, and the = Sign
      * 4.2.10 Setting Environment Variables
    * [4.3 MySQL Server and Server-Startup Programs](preface-and-legal-notices/4-mysql-programs/43-mysql-server-and-server-startup-programs.md)
      * 4.3.1 mysqld — The MySQL Server
      * 4.3.2 mysqld\_safe — MySQL Server Startup Scrip
      * 4.3.3 mysql.server — MySQL Server Startup Script
      * 4.3.4 mysqld\_multi — Manage Multiple MySQL Servers
    * [4.4 MySQL Installation-Related Programs](preface-and-legal-notices/4-mysql-programs/44-mysql-installation-related-programs.md)
      * 4.4.1 comp\_err — Compile MySQL Error Message File
      * 4.4.2 mysql\_install\_db — Initialize MySQL Data Directory
      * 4.4.3 mysql\_plugin — Configure MySQL Server Plugins
      * 4.4.4 mysql\_secure\_installation — Improve MySQL Installation Security
      * 4.4.5 mysql\_ssl\_rsa\_setup — Create SSL/RSA Files
      * 4.4.6 mysql\_tzinfo\_to\_sql — Load the Time Zone Tables
      * 4.4.7 mysql\_upgrade — Check and Upgrade MySQL Tables
    * [4.5 MySQL Client Programs](preface-and-legal-notices/4-mysql-programs/45-mysql-client-programs.md)
      * 4.5.1 mysql — The MySQL Command-Line Tool
      * 4.5.2 mysqladmin — Client for Administering a MySQL Server
      * 4.5.3 mysqlcheck — A Table Maintenance Program
      * 4.5.4 mysqldump — A Database Backup Program
      * 4.5.5 mysqlimport — A Data Import Program
      * 4.5.6 mysqlpump — A Database Backup Program
      * 4.5.7 mysqlsh — The MySQL Shell
      * 4.5.8mysqlshow—DisplayDatabase,Table,andColumnInformation
      * 4.5.9 mysqlslap — Load Emulation Client
    * [4.6 MySQL Administrative and Utility Programs](preface-and-legal-notices/4-mysql-programs/46-mysql-administrative-and-utility-programs.md)
      * 4.6.1 innochecksum — Offline InnoDB File Checksum Utility
      * 4.6.2 myisam\_ftdump — Display Full-Text Index information
      * [4.6.3 myisamchk — MyISAM Table-Maintenance Utility](preface-and-legal-notices/4-mysql-programs/46-mysql-administrative-and-utility-programs/463-myisamchk-myisam-table-maintenance-utility.md)
      * 4.6.4 myisamlog — Display MyISAM Log File Contents
      * [4.6.5 myisampack —GenerateCompressed,Read-OnlyMyISAMTables](preface-and-legal-notices/4-mysql-programs/46-mysql-administrative-and-utility-programs/465myisampackgeneratecompressedread-onlymyisamtables.md)
      * 4.6.6 mysql\_config\_editor — MySQL Configuration Utility
      * 4.6.7 mysqlbinlog — Utility for Processing Binary Log Files
      * 4.6.8 mysqldumpslow — Summarize Slow Query Log Files
    * [4.7 MySQL Program Development Utilities](preface-and-legal-notices/4-mysql-programs/47-mysql-program-development-utilities.md)
      * 4.7.1 mysql\_config — Display Options for Compiling Clients
      * 4.7.2 my\_print\_defaults — Display Options from Option Files
      * 4.7.3 resolve\_stack\_dump — Resolve Numeric Stack Trace Dump to Symbols
    * [4.8 Miscellaneous Programs](preface-and-legal-notices/4-mysql-programs/48-miscellaneous-programs.md)
      * 4.8.1 lz4\_decompress — Decompress mysqlpump LZ4-Compressed Output
      * 4.8.2 perror — Explain Error Codes
      * 4.8.3 replace — A String-Replacement Utility
      * 4.8.4 resolveip — Resolve Host name to IP Address or Vice Versa
      * 4.8.5 zlib\_decompress — Decompress mysqlpump ZLIB-Compressed Output
    * 4.9 MySQL Program Environment Variables
  * [5 MySQL Server Administration](preface-and-legal-notices/5-mysql-server-administration.md)
    * [5.1 The MySQL Server](preface-and-legal-notices/5-mysql-server-administration/51-the-mysql-server.md)
      * 5.1.1 Configuring the Server
      * 5.1.2 Server Configuration Defaults
      * 5.1.3 Server Option, System Variable, and Status Variable Reference
      * 5.1.4 Server System Variable Reference
      * 5.1.5 Server Status Variable Reference 
      * 5.1.6 Server Command Options
      * 5.1.7 Server System Variables
      * 5.1.8 Using System Variables
      * 5.1.9 Server Status Variables
      * 5.1.10 Server SQL Modes
      * 5.1.11 IPv6 Support
      * 5.1.12 MySQL Server Time Zone Support
      * 5.1.13 Server-Side Help
      * 5.1.14 Server Response to Signals
      * 5.1.15 The Server Shutdown Process
    * 5.2 The MySQL Data Directory
    * 5.3 The mysql System Database
    * [5.4 MySQL Server Logs](preface-and-legal-notices/5-mysql-server-administration/54-mysql-server-logs.md)
      * 5.4.1 Selecting General Query and Slow Query Log Output Destinations
      * 5.4.2 The Error Log
      * 5.4.3 The General Query Log
      * 5.4.4 The Binary Log
      * 5.4.5 The Slow Query Log
      * 5.4.6 The DDL Log
      * 5.4.7 Server Log Maintenance
    * [5.5 MySQL Server Plugins](preface-and-legal-notices/5-mysql-server-administration/55-mysql-server-plugins.md)
      * 5.5.1 Installing and Uninstalling Plugins
      * 5.5.2 Obtaining Server Plugin Information
      * 5.5.3 MySQL Enterprise Thread Pool
      * 5.5.4 The Rewriter Query Rewrite Plugin
      * 5.5.5 Version Tokens
    * [5.6 Running Multiple MySQL Instances on One Machine](preface-and-legal-notices/5-mysql-server-administration/56-running-multiple-mysql-instances-on-one-machine.md)
      * 5.6.1 Setting Up Multiple Data Directories
      * 5.6.2 Running Multiple MySQL Instances on Windows
      * 5.6.3 Running Multiple MySQL Instances on Unix
      * 5.6.4 Using Client Programs in a Multiple-Server Environment
    * [5.7 Tracing mysqld Using DTrace](preface-and-legal-notices/5-mysql-server-administration/57-tracing-mysqld-using-dtrace.md)
      * 5.7.1 mysqld DTrace Probe Reference
  * [6 Security](preface-and-legal-notices/6-security.md)
    * [6.1 General Security Issues](preface-and-legal-notices/6-security/61-general-security-issues.md)
      * 6.1.1 Security Guidelines
      * 6.1.2 Keeping Passwords Secure
      * 6.1.3 Making MySQL Secure Against Attackers
      * 6.1.4 Security-Related mysqld Options and Variables
      * 6.1.5 How to Run MySQL as a Normal User
      * 6.1.6 Security Issues with LOAD DATA LOCAL
      * 6.1.7 Client Programming Security Guidelines
    * [6.2 The MySQL Access Privilege System](preface-and-legal-notices/6-security/62-the-mysql-access-privilege-system.md)
      * 6.2.1 Privileges Provided by MySQL
      * 6.2.2 Grant Tables
      * 6.2.3 Specifying Account Names
      * 6.2.4 Access Control, Stage 1: Connection Verification
      * 6.2.5 Access Control, Stage 2: Request Verification
      * 6.2.6 When Privilege Changes Take Effect
      * 6.2.7 Troubleshooting Problems Connecting to MySQL
    * [6.3 MySQL User Account Management](preface-and-legal-notices/6-security/63-mysql-user-account-management.md)
      * 6.3.1 User Names and Passwords
      * 6.3.2 Adding User Accounts
      * 6.3.3 Removing User Accounts
      * 6.3.4 Reserved User Accounts
      * 6.3.5 Setting Account Resource Limits
      * 6.3.6 Assigning Account Passwords
      * 6.3.7 Password Management
      * 6.3.8 Password Expiration and Sandbox Mode
      * 6.3.9 Pluggable Authentication
      * 6.3.10 Proxy Users
      * 6.3.11 User Account Locking
      * 6.3.12 SQL-Based MySQL Account Activity Auditing
    * [6.4 Using Encrypted Connections](preface-and-legal-notices/6-security/64-using-encrypted-connections.md)
      * 6.4.1 Configuring MySQL to Use Encrypted Connections
      * 6.4.2 Command Options for Encrypted Connections
      * 6.4.3 Creating SSL and RSA Certificates and Keys
      * 6.4.4 OpenSSL Versus yaSSL
      * 6.4.5 Building MySQL with Support for Encrypted Connections
      * 6.4.6 Encrypted Connection Protocols and Ciphers
      * 6.4.7 Connecting to MySQL Remotely from Windows with SSH
    * [6.5 Security Plugins](preface-and-legal-notices/6-security/65-security-plugins.md)
      * 6.5.1 Authentication Plugins
      * 6.5.2 The Connection-Control Plugins
      * 6.5.3 The Password Validation Plugin
      * 6.5.4 The MySQL Keyring
      * 6.5.5 MySQL Enterprise Audit
      * 6.5.6 MySQL Enterprise Firewall
  * [7 Backup and Recovery](preface-and-legal-notices/7-backup-and-recovery.md)
    * 7.1 Backup and Recovery Types
    * 7.2 Database Backup Methods
    * [7.3 Example Backup and Recovery Strategy](preface-and-legal-notices/7-backup-and-recovery/73-example-backup-and-recovery-strategy.md)
      * 7.3.1 Establishing a Backup Policy
      * 7.3.2 Using Backups for Recover
      * 7.3.3 Backup Strategy Summary
    * [7.4 Using mysqldump for Backups](preface-and-legal-notices/7-backup-and-recovery/74-using-mysqldump-for-backups.md)
      * 7.4.1 Dumping Data in SQL Format with mysqldump
      * 7.4.2 Reloading SQL-Format Backups
      * 7.4.3 Dumping Data in Delimited-Text Format with mysqldump
      * 7.4.4 Reloading Delimited-Text Format Backups
      * 7.4.5 mysqldump Tips
    * [7.5 Point-in-Time \(Incremental\) Recovery Using the Binary Log](preface-and-legal-notices/7-backup-and-recovery/75-point-in-time-incremental-recovery-using-the-binary-log.md)
      * 7.5.1 Point-in-Time Recovery Using Event Times
      * 7.5.2 Point-in-Time Recovery Using Event Positions
    * [7.6 MyISAM Table Maintenance and Crash Recovery](preface-and-legal-notices/7-backup-and-recovery/76-myisam-table-maintenance-and-crash-recovery.md)
      * 7.6.1 Using myisamchk for Crash Recovery
      * 7.6.2 How to Check MyISAM Tables for Errors
      * 7.6.3 How to Repair MyISAM Tables
      * 7.6.4 MyISAM Table Optimization
      * 7.6.5 Setting Up a MyISAM Table Maintenance Schedule
  * [8 Optimization](preface-and-legal-notices/8-optimization.md)
    * 8.1 Optimization Overview
    * [8.2 Optimizing SQL Statements](preface-and-legal-notices/8-optimization/82-optimizing-sql-statements.md)
      * 8.2.1 Optimizing SELECT Statements
      * 8.2.2 Optimizing Subqueries, Derived Tables, and View References
      * 8.2.3 Optimizing INFORMATION\_SCHEMA Queries
      * 8.2.4 Optimizing Data Change Statements
      * 8.2.5 Optimizing Database Privileges
      * 8.2.6 Other Optimization Tips
    * [8.3 Optimization and Indexes](preface-and-legal-notices/8-optimization/83-optimization-and-indexes.md)
      * 8.3.1 How MySQL Uses Indexes
      * 8.3.2 Primary Key Optimization
      * 8.3.3 Foreign Key Optimization
      * 8.3.4 Column Indexes
      * 8.3.5 Multiple-Column Indexes
      * 8.3.6 Verifying Index Usage
      * 8.3.7 InnoDB and MyISAM Index Statistics Collection
      * 8.3.8 Comparison of B-Tree and Hash Indexes
      * 8.3.9 Use of Index Extensions
      * 8.3.10 Optimizer Use of Generated Column Indexes
    * [8.4 Optimizing Database Structure](preface-and-legal-notices/8-optimization/84-optimizing-database-structure.md)
      * 8.4.1 Optimizing Data Size
      * 8.4.2 Optimizing MySQL Data Types
      * 8.4.3 Optimizing for Many Tables
      * 8.4.4 Internal Temporary Table Use in MySQL
    * [8.5 Optimizing for InnoDB Tables](preface-and-legal-notices/8-optimization/85-optimizing-for-innodb-tables.md)
      * 8.5.1 Optimizing Storage Layout for InnoDB Tables
      * 8.5.2 Optimizing InnoDB Transaction Management
      * 8.5.3 Optimizing InnoDB Read-Only Transactions
      * 8.5.4 Optimizing InnoDB Redo Logging
      * 8.5.5 Bulk Data Loading for InnoDB Tables
      * 8.5.6 Optimizing InnoDB Queries
      * 8.5.7 Optimizing InnoDB DDL Operations
      * 8.5.8 Optimizing InnoDB Disk I/O
      * 8.5.9 Optimizing InnoDB Configuration Variables
      * 8.5.10 Optimizing InnoDB for Systems with Many Tables
    * [8.6 Optimizing for MyISAM Tables](preface-and-legal-notices/8-optimization/86-optimizing-for-myisam-tables.md)
      * 8.6.1 Optimizing MyISAM Queries
      * 8.6.2 Bulk Data Loading for MyISAM Tables
      * 8.6.3 Optimizing REPAIR TABLE Statements
    * 8.7 Optimizing for MEMORY Tables
    * [8.8 Understanding the Query Execution Plan](preface-and-legal-notices/8-optimization/88-understanding-the-query-execution-plan.md)
      * 8.8.1 Optimizing Queries with EXPLAIN
      * 8.8.2 EXPLAIN Output Format
      * 8.8.3 Extended EXPLAIN Output Format
      * 8.8.4 Obtaining Execution Plan Information for a Named Connection
      * 8.8.5 Estimating Query Performance
    * [8.9 Controlling the Query Optimizer](preface-and-legal-notices/8-optimization/89-controlling-the-query-optimizer.md)
      * 8.9.1 Controlling Query Plan Evaluation
      * 8.9.2 Optimizer Hints
      * 8.9.3 Switchable Optimizations
      * 8.9.4 Index Hints
      * 8.9.5 The Optimizer Cost Model
    * [8.10 Buffering and Caching](preface-and-legal-notices/8-optimization/810-buffering-and-caching.md)
      * 8.10.1 InnoDB Buffer Pool Optimization
      * 8.10.2 The MyISAM Key Cache
      * 8.10.3 The MySQL Query Cache
      * 8.10.4 Caching of Prepared Statements and Stored Programs
    * [8.11 Optimizing Locking Operations](preface-and-legal-notices/8-optimization/811-optimizing-locking-operations.md)
      * 8.11.1 Internal Locking Methods
      * 8.11.2 Table Locking Issues
      * 8.11.3 Concurrent Inserts
      * 8.11.4 Metadata Locking
      * 8.11.5 External Locking
    * [8.12 Optimizing the MySQL Server](preface-and-legal-notices/8-optimization/812-optimizing-the-mysql-server.md)
      * 8.12.1 System Factors
      * 8.12.2 Optimizing Disk I/O
      * 8.12.3 Using Symbolic Links
      * 8.12.4 Optimizing Memory Use
      * 8.12.5 Optimizing Network Use
    * [8.13 Measuring Performance \(Benchmarking\)](preface-and-legal-notices/8-optimization/813-measuring-performance-benchmarking.md)
      * 8.13.1 Measuring the Speed of Expressions and Functions
      * 8.13.2 Using Your Own Benchmarks
      * 8.13.3 Measuring Performance with performance\_schema
    * [8.14 Examining Thread Information](preface-and-legal-notices/8-optimization/814-examining-thread-information.md)
      * 8.14.1 Thread Command Values
      * 8.14.2 General Thread States
      * 8.14.3 Query Cache Thread States
      * 8.14.4 Replication Master Thread States
      * 8.14.5 Replication Slave I/O Thread States
      * 8.14.6 Replication Slave SQL Thread States
      * 8.14.7 Replication Slave Connection Thread States
      * 8.14.8 NDB Cluster Thread States
      * 8.14.9 Event Scheduler Thread States
  * [9 Language Structure](preface-and-legal-notices/9-language-structure.md)
    * [9.1 Literal Values](preface-and-legal-notices/9-language-structure/91-literal-values.md)
      * 9.1.1 String Literals
      * 9.1.2 Numeric Literals
      * 9.1.3 Date and Time Literals
      * 9.1.4 Hexadecimal Literals
      * 9.1.5 Bit-Value Literals
      * 9.1.6 Boolean Literals
      * 9.1.7 NULL Values
    * [9.2 Schema Object Names](preface-and-legal-notices/9-language-structure/92-schema-object-names.md)
      * 9.2.1 Identifier Qualifiers
      * 9.2.2 Identifier Case Sensitivity
      * 9.2.3 Mapping of Identifiers to File Names
      * 9.2.4 Function Name Parsing and Resolution
    * 9.3 Keywords and Reserved Words
    * 9.4 User-Defined Variables
    * 9.5 Expression Syntax
    * 9.6 Comment Syntax
  * [10 Character Sets, Collations, Unicode](preface-and-legal-notices/10-character-sets-collations-unicode.md)
    * 10.1 Character Sets and Collations in General
    * [10.2 Character Sets and Collations in MySQL](preface-and-legal-notices/10-character-sets-collations-unicode/102-character-sets-and-collations-in-mysql.md)
      * 10.2.1 Character Set Repertoire
      * 10.2.2 UTF-8 for Metadata
    * [10.3 Specifying Character Sets and Collations](preface-and-legal-notices/10-character-sets-collations-unicode/103-specifying-character-sets-and-collations.md)
      * 10.3.1 Collation Naming Conventions
      * 10.3.2 Server Character Set and Collation
      * 10.3.3 Database Character Set and Collation
      * 10.3.4 Table Character Set and Collation
      * 10.3.5 Column Character Set and Collation
      * 10.3.6 Character String Literal Character Set and Collation
      * 10.3.7 The National Character Set
      * 10.3.8 Character Set Introducers
      * 10.3.9 Examples of Character Set and Collation Assignment
      * 10.3.10 Compatibility with Other DBMSs
    * 10.4 Connection Character Sets and Collations
    * 10.5 Configuring Application Character Set and Collation
    * 10.6 Error Message Character Set
    * 10.7 Column Character Set Conversion
    * [10.8 Collation Issues](preface-and-legal-notices/10-character-sets-collations-unicode/108-collation-issues.md)
      * 10.8.1 Using COLLATE in SQL Statements
      * 10.8.2 COLLATE Clause Precedence
      * 10.8.3 Character Set and Collation Compatibility
      * 10.8.4 Collation Coercibility in Expressions
      * 10.8.5 The binary Collation Compared to \_bin Collations
      * 10.8.6 Examples of the Effect of Collation
      * 10.8.7 Using Collation in INFORMATION\_SCHEMA Searches
    * [10.9 Unicode Support](preface-and-legal-notices/10-character-sets-collations-unicode/109-unicode-support.md)
      * 10.9.1 The utf8mb4 Character Set \(4-Byte UTF-8 Unicode Encoding\)
      * 10.9.2 The utf8mb3 Character Set \(3-Byte UTF-8 Unicode Encoding\)
      * 10.9.3 The utf8 Character Set \(Alias for utf8mb3\)
      * 10.9.4 The ucs2 Character Set \(UCS-2 Unicode Encoding\)
      * 10.9.5 The utf16 Character Set \(UTF-16 Unicode Encoding\)
      * 10.9.6 The utf16le Character Set \(UTF-16LE Unicode Encoding\)
      * 10.9.7 The utf32 Character Set \(UTF-32 Unicode Encoding\)
      * 10.9.8 Converting Between 3-Byte and 4-Byte Unicode Character Sets
    * [10.10 Supported Character Sets and Collations](preface-and-legal-notices/10-character-sets-collations-unicode/1010-supported-character-sets-and-collations.md)
      * 10.10.1 Unicode Character Sets
      * 10.10.2 West European Character Sets
      * 10.10.3 Central European Character Sets
      * 10.10.4 South European and Middle East Character Sets
      * 10.10.5 Baltic Character Sets
      * 10.10.6 Cyrillic Character Sets
      * 10.10.7 Asian Character Sets
      * 10.10.8 The Binary Character Set
    * 10.11 Setting the Error Message Language
    * [10.12 Adding a Character Set](preface-and-legal-notices/10-character-sets-collations-unicode/1012-adding-a-character-set.md)
      * 10.12.1 Character Definition Arrays
      * 10.12.2 String Collating Support for Complex Character Sets
      * 10.12.3 Multi-Byte Character Support for Complex Character Sets
    * [10.13 Adding a Collation to a Character Set](preface-and-legal-notices/10-character-sets-collations-unicode/1013-adding-a-collation-to-a-character-set.md)
      * 10.13.1 Collation Implementation Types
      * 10.13.2 Choosing a Collation ID
      * 10.13.3 Adding a Simple Collation to an 8-Bit Character Set
      * 10.13.4 Adding a UCA Collation to a Unicode Character Set
    * 10.14 Character Set Configuration
    * 10.15 MySQL Server Locale Support
  * [11 Data Types](preface-and-legal-notices/11-data-types.md)
    * [11.1 Data Type Overview](preface-and-legal-notices/11-data-types/111-data-type-overview.md)
      * 11.1.1 Numeric Type Overview
      * 11.1.2 Date and Time Type Overview
      * 11.1.3 String Type Overview
    * [11.2 Numeric Types](preface-and-legal-notices/11-data-types/112-numeric-types.md)
      * 11.2.1 Integer Types \(Exact Value\) - INTEGER, INT, SMALLINT, TINYINT, MEDIUMINT, BIGINT
      * 11.2.2 Fixed-Point Types \(Exact Value\) - DECIMAL, NUMERIC
      * 11.2.3 Floating-Point Types \(Approximate Value\) - FLOAT, DOUBLE
      * 11.2.4 Bit-Value Type - BIT
      * 11.2.5 Numeric Type Attributes
      * 11.2.6 Out-of-Range and Overflow Handling
    * [11.3 Date and Time Types](preface-and-legal-notices/11-data-types/113-date-and-time-types.md)
      * 11.3.1 The DATE, DATETIME, and TIMESTAMP Types
      * 11.3.2 The TIME Type
      * 11.3.3 The YEAR Type
      * 11.3.4 YEAR\(2\) Limitations and Migrating to YEAR\(4\)
      * 11.3.5 Automatic Initialization and Updating for TIMESTAMP and DATETIME
      * 11.3.6 Fractional Seconds in Time Values
      * 11.3.7 Conversion Between Date and Time Types
      * 11.3.8 Two-Digit Years in Dates
    * [11.4 String Types](preface-and-legal-notices/11-data-types/114-string-types.md)
      * 11.4.1 The CHAR and VARCHAR Types
      * 11.4.2 The BINARY and VARBINARY Types
      * 11.4.3 The BLOB and TEXT Types
      * 11.4.4 The ENUM Type
      * 11.4.5 The SET Type
    * [11.5 Spatial Data Types](preface-and-legal-notices/11-data-types/115-spatial-data-types.md)
      * 11.5.1 Spatial Data Types
      * 11.5.2 The OpenGIS Geometry Model
      * 11.5.3 Supported Spatial Data Formats
      * 11.5.4 Geometry Well-Formedness and Validity
      * 11.5.5 Creating Spatial Columns
      * 11.5.6 Populating Spatial Columns
      * 11.5.7 Fetching Spatial Data
      * 11.5.8 Optimizing Spatial Analysis
      * 11.5.9 Creating Spatial Indexes
      * 11.5.10 Using Spatial Indexes
    * 11.6 The JSON Data Type
    * 11.7 Data Type Default Values
    * 11.8 Data Type Storage Requirements
    * 11.9 Choosing the Right Type for a Column
    * 11.10 Using Data Types from Other Database Engines
  * [12 Functions and Operators](preface-and-legal-notices/12-functions-and-operators.md)
    * 12.1 Function and Operator Reference
    * 12.2 Type Conversion in Expression Evaluation
    * [12.3 Operators](preface-and-legal-notices/12-functions-and-operators/123-operators.md)
      * 12.3.1 Operator Precedence
      * 12.3.2 Comparison Functions and Operators
      * 12.3.3 Logical Operators
      * 12.3.4 Assignment Operators
    * 12.4 Control Flow Functions
    * [12.5 String Functions](preface-and-legal-notices/12-functions-and-operators/125-string-functions.md)
      * 12.5.1 String Comparison Functions
      * 12.5.2 Regular Expressions
      * 12.5.3 Character Set and Collation of Function Results
    * [12.6 Numeric Functions and Operators](preface-and-legal-notices/12-functions-and-operators/126-numeric-functions-and-operators.md)
      * 12.6.1 Arithmetic Operators
      * 12.6.2 Mathematical Functions
    * 12.7 Date and Time Functions
    * 12.8 What Calendar Is Used By MySQL?
    * [12.9 Full-Text Search Functions](preface-and-legal-notices/12-functions-and-operators/129-full-text-search-functions.md)
      * 12.9.1 Natural Language Full-Text Searches
      * 12.9.2 Boolean Full-Text Searches
      * 12.9.3 Full-Text Searches with Query Expansion
      * 12.9.4 Full-Text Stopwords
      * 12.9.5 Full-Text Restrictions
      * 12.9.6 Fine-Tuning MySQL Full-Text Search
      * 12.9.7 Adding a Collation for Full-Text Indexing
      * 12.9.8 ngram Full-Text Parser
      * 12.9.9 MeCab Full-Text Parser Plugin
    * 12.10 Cast Functions and Operators
    * 12.11 XML Functions
    * 12.12 Bit Functions and Operators
    * 12.13 Encryption and Compression Functions
    * 12.14 Information Functions
    * [12.15 Spatial Analysis Functions](preface-and-legal-notices/12-functions-and-operators/1215-spatial-analysis-functions.md)
      * 12.15.1 Spatial Function Reference
      * 12.15.2 Argument Handling by Spatial Functions
      * 12.15.3 Functions That Create Geometry Values from WKT Values
      * 12.15.4 Functions That Create Geometry Values from WKB Values
      * 12.15.5 MySQL-Specific Functions That Create Geometry Values
      * 12.15.6 Geometry Format Conversion Functions
      * 12.15.7 Geometry Property Functions
      * 12.15.8 Spatial Operator Functions
      * 12.15.9 Functions That Test Spatial Relations Between Geometry Objects
      * 12.15.10 Spatial Geohash Functions
      * 12.15.11 Spatial GeoJSON Functions
      * 12.15.12 Spatial Convenience Functions
    * [12.16 JSON Functions](preface-and-legal-notices/12-functions-and-operators/1216-json-functions.md)
      * 12.16.1 JSON Function Reference
      * 12.16.3 Functions That Search JSON Values
      * 12.16.4 Functions That Modify JSON Values
      * 12.16.5 Functions That Return JSON Value Attributes
      * 12.16.6 JSON Utility Functions
      * 12.16.7 JSON Path Syntax
    * 12.17 Functions Used with Global Transaction IDs
    * [12.18 MySQL Enterprise Encryption Functions](preface-and-legal-notices/12-functions-and-operators/1218-mysql-enterprise-encryption-functions.md)
      * 12.18.1 Enterprise Encryption Installation
      * 12.18.2 Enterprise Encryption Usage and Examples
      * 12.18.3 Enterprise Encryption Function Reference
      * 12.18.4 Enterprise Encryption Function Descriptions
    * [12.19 Aggregate \(GROUP BY\) Functions](preface-and-legal-notices/12-functions-and-operators/1219-aggregate-group-by-functions.md)
      * 12.19.1 Aggregate \(GROUP BY\) Function Descriptions
      * 12.19.2 GROUP BY Modifiers
      * 12.19.3 MySQL Handling of GROUP BY
      * 12.19.4 Detection of Functional Dependence
    * 12.20 Miscellaneous Functions
    * [12.21 Precision Math](preface-and-legal-notices/12-functions-and-operators/1221-precision-math.md)
      * 12.21.1 Types of Numeric Values
      * 12.21.2 DECIMAL Data Type Characteristics
      * 12.21.3 Expression Handling
      * 12.21.4 Rounding Behavior
      * 12.21.5 Precision Math Examples
  * [13 SQL Statement Syntax](preface-and-legal-notices/13-sql-statement-syntax.md)
    * [13.1 Data Definition Statements](preface-and-legal-notices/13-sql-statement-syntax/131-data-definition-statements.md)
      * 13.1.1 ALTER DATABASE Syntax
      * 13.1.2 ALTER EVENT Syntax
      * 13.1.3 ALTER FUNCTION Syntax
      * 13.1.4 ALTER INSTANCE Syntax
      * 13.1.5 ALTER LOGFILE GROUP Syntax
      * 13.1.6 ALTER PROCEDURE Syntax
      * 13.1.7 ALTER SERVER Syntax
      * 13.1.8 ALTER TABLE Syntax
      * 13.1.9 ALTER TABLESPACE Syntax
      * 13.1.10 ALTER VIEW Syntax
      * 13.1.11 CREATE DATABASE Syntax
      * 13.1.12 CREATE EVENT Syntax
      * 13.1.13 CREATE FUNCTION Syntax
      * 13.1.14 CREATE INDEX Syntax
      * 13.1.15 CREATE LOGFILE GROUP Syntax
      * 13.1.16 CREATE PROCEDURE and CREATE FUNCTION Syntax
      * 13.1.17 CREATE SERVER Syntax
      * 13.1.18 CREATE TABLE Syntax
      * 13.1.19 CREATE TABLESPACE Syntax
      * 13.1.20 CREATE TRIGGER Syntax
      * 13.1.21 CREATE VIEW Syntax
      * 13.1.22 DROP DATABASE Syntax
      * 13.1.23 DROP EVENT Syntax
      * 13.1.24 DROP FUNCTION Syntax
      * 13.1.25 DROP INDEX Syntax
      * 13.1.26 DROP LOGFILE GROUP Syntax
      * 13.1.27 DROP PROCEDURE and DROP FUNCTION Syntax
      * 13.1.28 DROP SERVER Syntax
      * 13.1.29 DROP TABLE Syntax
      * 13.1.30 DROP TABLESPACE Syntax
      * 13.1.31 DROP TRIGGER Syntax
      * 13.1.32 DROP VIEW Syntax
      * 13.1.33 RENAME TABLE Syntax
      * 13.1.34 TRUNCATE TABLE Syntax
    * [13.2 Data Manipulation Statements](preface-and-legal-notices/13-sql-statement-syntax/132-data-manipulation-statements.md)
      * 13.2.1 CALL Syntax
      * 13.2.2 DELETE Syntax
      * 13.2.3 DO Syntax
      * 13.2.4 HANDLER Synta
      * 13.2.5 INSERT Syntax
      * 13.2.6 LOAD DATA INFILE Syntax
      * 13.2.7 LOAD XML Syntax
      * 13.2.8 REPLACE Syntax
      * 13.2.9 SELECT Syntax
      * 13.2.10 Subquery Syntax
      * 13.2.11 UPDATE Syntax
    * [13.3 Transactional and Locking Statements](preface-and-legal-notices/13-sql-statement-syntax/133-transactional-and-locking-statements.md)
      * 13.3.1 START TRANSACTION, COMMIT, and ROLLBACK Syntax
      * 13.3.2 Statements That Cannot Be Rolled Back
      * 13.3.3 Statements That Cause an Implicit Commit
      * 13.3.4 SAVEPOINT, ROLLBACK TO SAVEPOINT, and RELEASE SAVEPOINT Syntax
      * 13.3.5 LOCK TABLES and UNLOCK TABLES Syntax
      * 13.3.6 SET TRANSACTION Syntax
      * 13.3.7 XA Transactions
    * [13.4 Replication Statements](preface-and-legal-notices/13-sql-statement-syntax/134-replication-statements.md)
      * 13.4.1 SQL Statements for Controlling Master Servers
      * 13.4.2 SQL Statements for Controlling Slave Servers
      * 13.4.3 SQL Statements for Controlling Group Replication
    * [13.5 Prepared SQL Statement Syntax](preface-and-legal-notices/13-sql-statement-syntax/135-prepared-sql-statement-syntax.md)
      * 13.5.1 PREPARE Syntax
      * 13.5.2 EXECUTE Syntax
      * 13.5.3 DEALLOCATE PREPARE Syntax
    * [13.6 Compound-Statement Syntax](preface-and-legal-notices/13-sql-statement-syntax/136-compound-statement-syntax.md)
      * 13.6.1 BEGIN ... END Compound-Statement Syntax
      * 13.6.2 Statement Label Syntax
      * 13.6.3 DECLARE Syntax
      * 13.6.4 Variables in Stored Programs
      * 13.6.5 Flow Control Statements
      * 13.6.6 Cursors
      * 13.6.7 Condition Handling
    * [13.7 Database Administration Statements](preface-and-legal-notices/13-sql-statement-syntax/137-database-administration-statements.md)
      * 13.7.1 Account Management Statements
      * 13.7.2 Table Maintenance Statements
      * 13.7.3 Plugin and User-Defined Function Statements
      * 13.7.4 SET Syntax
      * 13.7.5 SHOW Syntax
      * 13.7.6 Other Administrative Statements
    * [13.8 Utility Statements](preface-and-legal-notices/13-sql-statement-syntax/138-utility-statements.md)
      * 13.8.1 DESCRIBE Syntax
      * 13.8.2 EXPLAIN Syntax
      * 13.8.3 HELP Syntax
      * 13.8.4 USE Syntax
  * [14 The InnoDB Storage Engine](preface-and-legal-notices/14-the-innodb-storage-engine.md)
    * [14.1 Introduction to InnoDB](preface-and-legal-notices/14-the-innodb-storage-engine/141-introduction-to-innodb.md)
      * 14.1.1 Benefits of Using InnoDB Tables
      * 14.1.2 Best Practices for InnoDB Tables
      * 14.1.3 Verifying that InnoDB is the Default Storage Engine
      * 14.1.4 Testing and Benchmarking with InnoDB
      * 14.1.5 Turning Off InnoDB
    * 14.2 InnoDB and the ACID Model
    * 14.3 InnoDB Multi-Versioning
    * [14.4 InnoDB Architecture](preface-and-legal-notices/14-the-innodb-storage-engine/144-innodb-architecture.md)
      * 14.4.1 Buffer Pool
      * 14.4.2 Change Buffer
      * 14.4.3 Adaptive Hash Index
      * 14.4.4 Redo Log Buffer
      * 14.4.5 System Tablespace
      * 14.4.6 InnoDB Data Dictionary
      * 14.4.7 Doublewrite Buffer
      * 14.4.8 Undo Logs
      * 14.4.9 File-Per-Table Tablespaces
      * 14.4.10 General Tablespaces
      * 14.4.11 Undo Tablespace
      * 14.4.12 Temporary Tablespace
      * 14.4.13 Redo Log
    * [14.5 InnoDB Locking and Transaction Model](preface-and-legal-notices/14-the-innodb-storage-engine/145-innodb-locking-and-transaction-model.md)
      * 14.5.1 InnoDB Locking
      * 14.5.2 InnoDB Transaction Model
      * 14.5.3 Locks Set by Different SQL Statements in InnoDB
      * 14.5.4 Phantom Rows
      * 14.5.5 Deadlocks in InnoDB
    * [14.6 InnoDB Configuration](preface-and-legal-notices/14-the-innodb-storage-engine/146-innodb-configuration.md)
      * 14.6.1 InnoDB Startup Configuration
      * 14.6.2 Configuring InnoDB for Read-Only Operation
      * 14.6.3 InnoDB Buffer Pool Configuration
      * 14.6.4 Configuring the Memory Allocator for InnoDB
      * 14.6.5 Configuring InnoDB Change Buffering
      * 14.6.6 Configuring Thread Concurrency for InnoDB
      * 14.6.7 Configuring the Number of Background InnoDB I/O Threads
      * 14.6.8 Using Asynchronous I/O on Linux
      * 14.6.9 Configuring the InnoDB Master Thread I/O Rate
      * 14.6.10 Configuring Spin Lock Polling
      * 14.6.11 Configuring InnoDB Purge Scheduling
      * 14.6.12 Configuring Optimizer Statistics for InnoDB
      * 14.6.13 Configuring the Merge Threshold for Index Pages
    * [14.7 InnoDB Tablespaces](preface-and-legal-notices/14-the-innodb-storage-engine/147-innodb-tablespaces.md)
      * 14.7.1 Resizing the InnoDB System Tablespace
      * 14.7.2 Changing the Number or Size of InnoDB Redo Log Files
      * 14.7.3 Using Raw Disk Partitions for the System Tablespace
      * 14.7.4 InnoDB File-Per-Table Tablespaces
      * 14.7.5 Creating File-Per-Table Tablespaces Outside the Data Directory
      * 14.7.6 Copying File-Per-Table Tablespaces to Another Instance
      * 14.7.7 Configuring Undo Tablespaces
      * 14.7.8 Truncating Undo Tablespaces
      * 14.7.9 InnoDB General Tablespaces
      * 14.7.10 InnoDB Tablespace Encryption
    * [14.8 InnoDB Tables and Indexes](preface-and-legal-notices/14-the-innodb-storage-engine/148-innodb-tables-and-indexes.md)
      * 14.8.1 InnoDB Tables
      * 14.8.2 InnoDB Indexes
    * [14.9 InnoDB Table and Page Compression](preface-and-legal-notices/14-the-innodb-storage-engine/149-innodb-table-and-page-compression.md)
      * 14.9.1 InnoDB Table Compression
      * 14.9.2 InnoDB Page Compression
    * [14.10 InnoDB File-Format Management](preface-and-legal-notices/14-the-innodb-storage-engine/1410-innodb-file-format-management.md)
      * 14.10.1 Enabling File Formats
      * 14.10.2 Verifying File Format Compatibility
      * 14.10.3 Identifying the File Format in Use
      * 14.10.4 Modifying the File Format
    * [14.11 InnoDB Row Storage and Row Formats](preface-and-legal-notices/14-the-innodb-storage-engine/1411-innodb-row-storage-and-row-formats.md)
      * 14.11.1 Overview of InnoDB Row Storage
      * 14.11.2 Specifying the Row Format for a Table
      * 14.11.3 DYNAMIC and COMPRESSED Row Formats
      * 14.11.4 COMPACT and REDUNDANT Row Formats
    * [14.12 InnoDB Disk I/O and File Space Management](preface-and-legal-notices/14-the-innodb-storage-engine/1412-innodb-disk-io-and-file-space-management.md)
      * 14.12.1 InnoDB Disk I/O
      * 14.12.2 File Space Management
      * 14.12.3 InnoDB Checkpoints
      * 14.12.4 Defragmenting a Table
      * 14.12.5 Reclaiming Disk Space with TRUNCATE TABLE
    * [14.13 InnoDB and Online DDL](preface-and-legal-notices/14-the-innodb-storage-engine/1413-innodb-and-online-ddl.md)
      * 14.13.1 Online DDL Operations
      * 14.13.2 Online DDL Performance and Concurrency
      * 14.13.3 Online DDL Space Requirements
      * 14.13.4 Simplifying DDL Statements with Online DDL
      * 14.13.5 Online DDL Failure Conditions
      * 14.13.6 Online DDL Limitations
    * 14.14 InnoDB Startup Options and System Variables
    * [14.15 InnoDB INFORMATION\_SCHEMA Tables](preface-and-legal-notices/14-the-innodb-storage-engine/1415-innodb-informationschema-tables.md)
      * 14.15.1 InnoDB INFORMATION\_SCHEMA Tables about Compression
      * 14.15.2 InnoDB INFORMATION\_SCHEMA Transaction and Locking Information
      * 14.15.3 InnoDB INFORMATION\_SCHEMA System Tables
      * 14.15.4 InnoDB INFORMATION\_SCHEMA FULLTEXT Index Tables
      * 14.15.5 InnoDB INFORMATION\_SCHEMA Buffer Pool Tables
      * 14.15.6 InnoDB INFORMATION\_SCHEMA Metrics Table
      * 14.15.7 InnoDB INFORMATION\_SCHEMA Temporary Table Info Table
      * 14.15.8 Retrieving InnoDB Tablespace Metadata from INFORMATION\_SCHEMA.FILES
    * [14.16 InnoDB Integration with MySQL Performance Schema](preface-and-legal-notices/14-the-innodb-storage-engine/1416-innodb-integration-with-mysql-performance-schema.md)
      * 14.16.1 Monitoring ALTER TABLE Progress for InnoDB Tables Using Performance Schema
      * 14.16.2 Monitoring InnoDB Mutex Waits Using Performance Schema
    * [14.17 InnoDB Monitors](preface-and-legal-notices/14-the-innodb-storage-engine/1417-innodb-monitors.md)
      * 14.17.1 InnoDB Monitor Types
      * 14.17.2 Enabling InnoDB Monitors
      * 14.17.3 InnoDB Standard Monitor and Lock Monitor Output
    * [14.18 InnoDB Backup and Recovery](preface-and-legal-notices/14-the-innodb-storage-engine/1418-innodb-backup-and-recovery.md)
      * 14.18.1 InnoDB Backup
      * 14.18.2 InnoDB Recover
    * 14.19 InnoDB and MySQL Replication
    * [14.20 InnoDB memcached Plugin](preface-and-legal-notices/14-the-innodb-storage-engine/1420-innodb-memcached-plugin.md)
      * 14.20.1 Benefits of the InnoDB memcached Plugin
      * 14.20.2 InnoDB memcached Architecture
      * 14.20.3 Setting Up the InnoDB memcached Plugin
      * 14.20.4 Security Considerations for the InnoDB memcached Plugin
      * 14.20.5 Writing Applications for the InnoDB memcached Plugin
      * 14.20.6 The InnoDB memcached Plugin and Replication
      * 14.20.7 InnoDB memcached Plugin Internals
      * 14.20.8 Troubleshooting the InnoDB memcached Plugin
    * [14.21 InnoDB Troubleshooting](preface-and-legal-notices/14-the-innodb-storage-engine/1421-innodb-troubleshooting.md)
      * 14.21.1 Troubleshooting InnoDB I/O Problems
      * 14.21.2 Forcing InnoDB Recovery
      * 14.21.3 Troubleshooting InnoDB Data Dictionary Operations
      * 14.21.4 InnoDB Error Handling
  * [15 Alternative Storage Engines](preface-and-legal-notices/15-alternative-storage-engines.md)
    * [15.1 Setting the Storage Engine](preface-and-legal-notices/15-alternative-storage-engines/151-setting-the-storage-engine.md)
    * [15.2 The MyISAM Storage Engine](preface-and-legal-notices/15-alternative-storage-engines/152-the-myisam-storage-engine.md)
      * 15.2.1 MyISAM Startup Options
      * 15.2.2 Space Needed for Keys
      * 15.2.3 MyISAM Table Storage Formats
      * 15.2.4 MyISAM Table Problems
    * 15.3 The MEMORY Storage Engine
    * [15.4 The CSV Storage Engine](preface-and-legal-notices/15-alternative-storage-engines/154-the-csv-storage-engine.md)
      * 15.4.1 Repairing and Checking CSV Tables
      * 15.4.2 CSV Limitations
    * 15.5 The ARCHIVE Storage Engine
    * 15.6 The BLACKHOLE Storage Engine
    * [15.7 The MERGE Storage Engine](preface-and-legal-notices/15-alternative-storage-engines/157-the-merge-storage-engine.md)
      * 15.7.1 MERGE Table Advantages and Disadvantages
      * 15.7.2 MERGE Table Problems
    * [15.8 The FEDERATED Storage Engine](preface-and-legal-notices/15-alternative-storage-engines/158-the-federated-storage-engine.md)
      * 15.8.1 FEDERATED Storage Engine Overview
      * 15.8.2 How to Create FEDERATED Tables
      * 15.8.3 FEDERATED Storage Engine Notes and Tips
      * 15.8.4 FEDERATED Storage Engine Resources
    * 15.9 The EXAMPLE Storage Engine
    * 15.10 Other Storage Engines
    * [15.11 Overview of MySQL Storage Engine Architecture](preface-and-legal-notices/15-alternative-storage-engines/1511-overview-of-mysql-storage-engine-architecture.md)
      * 15.11.1 Pluggable Storage Engine Architecture
      * 15.11.2 The Common Database Server Layer
  * [16 Replication](preface-and-legal-notices/16-replication.md)
    * [16.1 Configuring Replication](preface-and-legal-notices/16-replication/161-configuring-replication.md)
      * 16.1.1 Binary Log File Position Based Replication Configuration Overview
      * 16.1.2 Setting Up Binary Log File Position Based Replication
      * 16.1.3 Replication with Global Transaction Identifiers
      * 16.1.4 MySQL Multi-Source Replication
      * 16.1.5 Changing Replication Modes on Online Servers
      * 16.1.6 Replication and Binary Logging Options and Variables
      * 16.1.7 Common Replication Administration Tasks
    * [16.2 Replication Implementation](preface-and-legal-notices/16-replication/162-replication-implementation.md)
      * 16.2.1 Replication Formats
      * 16.2.2 Replication Implementation Details
      * 16.2.3 Replication Channels
      * 16.2.4 Replication Relay and Status Logs
      * 16.2.5 How Servers Evaluate Replication Filtering Rules
    * [16.3 Replication Solutions](preface-and-legal-notices/16-replication/163-replication-solutions.md)
      * 16.3.1 Using Replication for Backups
      * 16.3.2 Handling an Unexpected Halt of a Replication Slave
      * 16.3.3 Using Replication with Different Master and Slave Storage Engines
      * 16.3.4 Using Replication for Scale-Out
      * 16.3.5 Replicating Different Databases to Different Slaves
      * 16.3.6 Improving Replication Performance
      * 16.3.7 Switching Masters During Failover
      * 16.3.8 Setting Up Replication to Use Encrypted Connections
      * 16.3.9 Semisynchronous Replication
      * 16.3.10 Delayed Replication
    * [16.4 Replication Notes and Tips](preface-and-legal-notices/16-replication/164-replication-notes-and-tips.md)
      * 16.4.1 Replication Features and Issues
      * 16.4.2 Replication Compatibility Between MySQL Versions
      * 16.4.3 Upgrading a Replication Setup
      * 16.4.4 Troubleshooting Replication
      * 16.4.5 How to Report Replication Bugs or Problems
  * [17 Group Replication](preface-and-legal-notices/17-group-replication.md)
    * [17.1 Group Replication Background](preface-and-legal-notices/17-group-replication/171-group-replication-background.md)
      * 17.1.1 Replication Technologies
      * 17.1.2 Group Replication Use Cases
      * 17.1.3 Group Replication Details
    * [17.2 Getting Started](preface-and-legal-notices/17-group-replication/172-getting-started.md)
      * 17.2.1 Deploying Group Replication in Single-Primary Mode
    * [17.3 Monitoring Group Replication](preface-and-legal-notices/17-group-replication/173-monitoring-group-replication.md)
      * 17.3.1 Replication\_group\_member\_stats
      * 17.3.2 Replication\_group\_members
      * 17.3.3 Replication\_connection\_status
      * 17.3.4 Replication\_applier\_status
      * 17.3.5 Group Replication Server States
    * [17.4 Group Replication Operations](preface-and-legal-notices/17-group-replication/174-group-replication-operations.md)
      * 17.4.1 Deploying in Multi-Primary or Single-Primary Mode
      * 17.4.2 Tuning Recovery
      * 17.4.3 Network Partitioning
      * 17.4.4 Using MySQL Enterprise Backup with Group Replication
    * [17.5 Group Replication Security](preface-and-legal-notices/17-group-replication/175-group-replication-security.md)
      * 17.5.1 IP Address Whitelisting
      * 17.5.2 Secure Socket Layer Support \(SSL\)
      * 17.5.3 Virtual Private Networks \(VPN\)
    * 17.6 Group Replication System Variables
    * [17.7 Requirements and Limitations](preface-and-legal-notices/17-group-replication/177-requirements-and-limitations.md)
      * 17.7.1 Group Replication Requirements
      * 17.7.2 Group Replication Limitations
    * 17.8 Frequently Asked Questions
    * [17.9 Group Replication Technical Details](preface-and-legal-notices/17-group-replication/179-group-replication-technical-details.md)
      * 17.9.1 Group Replication Plugin Architecture
      * 17.9.2 The Group
      * 17.9.3 Data Manipulation Statements
      * 17.9.4 Data Definition Statements
      * 17.9.5 Distributed Recovery
      * 17.9.6 Observability
      * 17.9.7 Group Replication Performance
  * [18 MySQL Shell User Guide](preface-and-legal-notices/18-mysql-shell-user-guide.md)
    * 18.1 MySQL Shell Features
    * [18.2 Getting Started with MySQL Shell](preface-and-legal-notices/18-mysql-shell-user-guide/182-getting-started-with-mysql-shell.md)
      * 18.2.1 MySQL Shell Connections
      * 18.2.2 MySQL Shell Sessions
      * 18.2.3 MySQL Shell Global Variables
    * [18.3 MySQL Shell Code Execution](preface-and-legal-notices/18-mysql-shell-user-guide/183-mysql-shell-code-execution.md)
      * 18.3.1 Interactive Code Execution
      * 18.3.2 Batch Code Execution
      * 18.3.3 Output Formats
      * 18.3.4 Active Language
      * 18.3.5 Batch Mode Made Interactive
    * [18.4 Configuring MySQL Shell](preface-and-legal-notices/18-mysql-shell-user-guide/184-configuring-mysql-shell.md)
      * 18.4.1 MySQL Shell Commands
    * 18.5 MySQL Shell Application Log
    * [18.6 Customizing MySQL Shell](preface-and-legal-notices/18-mysql-shell-user-guide/186-customizing-mysql-shell.md)
      * 18.6.1 Working With Start-Up Scripts
      * 18.6.2 Adding Module Search Paths
      * 18.6.3 Overriding the Default Prompt
  * [19 Using MySQL as a Document Store](preface-and-legal-notices/19-using-mysql-as-a-document-store.md)
    * 19.1 Preproduction Status — Legal Notice
    * 19.2 Key Concepts
    * [19.3 Setting Up MySQL as a Document Store](preface-and-legal-notices/19-using-mysql-as-a-document-store/193-setting-up-mysql-as-a-document-store.md)
      * 19.3.1 Installing MySQL Shell
      * 19.3.2 Starting MySQL Shell
    * [19.4 Quick-Start Guide: MySQL Shell for JavaScript](preface-and-legal-notices/19-using-mysql-as-a-document-store/194-quick-start-guide-mysql-shell-for-javascript.md)
      * 19.4.1 Introduction
      * 19.4.2 Import Database Sample
      * 19.4.3 MySQL Shell
      * 19.4.4 Documents and Collections
      * 19.4.5 Relational Tables
      * 19.4.6 Documents in Tables
    * [19.5 Quick-Start Guide: MySQL Shell for Python](preface-and-legal-notices/19-using-mysql-as-a-document-store/195-quick-start-guide-mysql-shell-for-python.md)
      * 19.5.1 Introduction
      * 19.5.2 Import Database Sample
      * 19.5.3 MySQL Shell
      * 19.5.4 Documents and Collections
      * 19.5.5 Relational Tables
      * 19.5.6 Documents in Tables
    * 19.6 Quick-Start Guide: MySQL for Visual Studio
    * [19.7 X Plugin](preface-and-legal-notices/19-using-mysql-as-a-document-store/197-x-plugin.md)
      * 19.7.1 Using Secure Connections with X Plugin
      * 19.7.2 X Plugin Options and Variables
      * 19.7.3 Monitoring X Plugin
  * [20 InnoDB Cluster](preface-and-legal-notices/20-innodb-cluster.md)
    * 20.1 Introducing InnoDB Cluster
    * [20.2 Creating an InnoDB Cluster](preface-and-legal-notices/20-innodb-cluster/202-creating-an-innodb-cluster.md)
      * 20.2.1 Deployment Scenarios
      * 20.2.2 InnoDB Cluster Requirements
      * 20.2.3 Methods of Installing
      * 20.2.4 Sandbox Deployment of InnoDB Cluster
      * 20.2.5 Production Deployment of InnoDB Cluster
      * 20.2.6 Adopting a Group Replication Deployment
    * 20.3 Using MySQL Router with InnoDB Cluster
    * 20.4 Working with InnoDB Cluster
    * 20.5 Known Limitations
  * 21 MySQL NDB Cluster 7.5 and NDB Cluster 7.6
  * [22 Partitioning](preface-and-legal-notices/22-partitioning.md)
    * 22.1 Overview of Partitioning in MySQL
    * [22.2 Partitioning Types](preface-and-legal-notices/22-partitioning/222-partitioning-types.md)
      * 22.2.1 RANGE Partitioning
      * 22.2.2 LIST Partitioning
      * 22.2.3 COLUMNS Partitioning
      * 22.2.4 HASH Partitioning
      * 22.2.5 KEY Partitioning
      * 22.2.6 Subpartitioning
      * 22.2.7 How MySQL Partitioning Handles NULL
    * [22.3 Partition Management](preface-and-legal-notices/22-partitioning/223-partition-management.md)
      * 22.3.1 Management of RANGE and LIST Partitions
      * 22.3.2 Management of HASH and KEY Partitions
      * 22.3.3 Exchanging Partitions and Subpartitions with Tables
      * 22.3.4 Maintenance of Partitions
      * 22.3.5 Obtaining Information About Partitions
    * 22.4 Partition Pruning
    * 22.5 Partition Selection
    * [22.6 Restrictions and Limitations on Partitioning](preface-and-legal-notices/22-partitioning/226-restrictions-and-limitations-on-partitioning.md)
      * 22.6.1 Partitioning Keys, Primary Keys, and Unique Keys
      * 22.6.2 Partitioning Limitations Relating to Storage Engines
      * 22.6.3 Partitioning Limitations Relating to Functions
      * 22.6.4 Partitioning and Locking
  * 23 Stored Programs and Views
  * 24 INFORMATION\_SCHEMA Tables
  * [25 MySQL Performance Schema](preface-and-legal-notices/25-mysql-performance-schema.md)
    * 25.1 Performance Schema Quick Start
    * 25.2 Performance Schema Build Configuration
    * 25.3 Performance Schema Startup Configuration
    * [25.4 Performance Schema Runtime Configuration](preface-and-legal-notices/25-mysql-performance-schema/254-performance-schema-runtime-configuration.md)
      * 25.4.1 Performance Schema Event Timing
      * 25.4.2 Performance Schema Event Filtering
      * 25.4.3 Event Pre-Filtering
      * 25.4.4 Pre-Filtering by Instrument
      * 25.4.5 Pre-Filtering by Object
      * 25.4.6 Pre-Filtering by Thread
      * 25.4.7 Pre-Filtering by Consumer
      * 25.4.8 Example Consumer Configurations
      * 25.4.9 Naming Instruments or Consumers for Filtering Operations
      * 25.4.10 Determining What Is Instrumented
    * 25.5 Performance Schema Queries
    * 25.6 Performance Schema Instrument Naming Conventions
    * 25.7 Performance Schema Status Monitoring
    * 25.8 Performance Schema Atom and Molecule Events
    * 25.9 Performance Schema Statement Digests
    * 25.10 Performance Schema General Table Characteristics
    * [25.11 Performance Schema Table Descriptions](preface-and-legal-notices/25-mysql-performance-schema/2511-performance-schema-table-descriptions.md)
      * 25.11.1 Performance Schema Table Index
      * 25.11.2 Performance Schema Setup Tables
      * 25.11.3 Performance Schema Instance Tables
      * 25.11.4 Performance Schema Wait Event Tables
      * 25.11.5 Performance Schema Stage Event Tables
      * 25.11.6 Performance Schema Statement Event Tables
      * 25.11.7 Performance Schema Transaction Tables
      * 25.11.8 Performance Schema Connection Tables
      * 25.11.9 Performance Schema Connection Attribute Tables
      * 25.11.10 Performance Schema User Variable Tables
      * 25.11.11 Performance Schema Replication Tables
      * 25.11.12 Performance Schema Lock Tables
      * 25.11.13 Performance Schema System Variable Tables
      * 25.11.14 Performance Schema Status Variable Tables
      * 25.11.15 Performance Schema Summary Tables
      * 25.11.16 Performance Schema Miscellaneous Tables
    * 25.12 Performance Schema Option and Variable Reference
    * 25.13 Performance Schema Command Options
    * 25.14 Performance Schema System Variables
    * 25.15 Performance Schema Status Variables
    * 25.16 The Performance Schema Memory-Allocation Model
    * 25.17 Performance Schema and Plugins
    * [25.18 Using the Performance Schema to Diagnose Problems](preface-and-legal-notices/25-mysql-performance-schema/2518-using-the-performance-schema-to-diagnose-problems.md)
      * 25.18.1 Query Profiling Using Performance Schema
    * 25.19 Migrating to Performance Schema System and Status Variable Tables
  * [26 MySQL sys Schema](preface-and-legal-notices/26-mysql-sys-schema.md)
    * 26.1 Prerequisites for Using the sys Schema
    * 26.2 Using the sys Schema
    * 26.3 sys Schema Progress Reporting
    * [26.4 sys Schema Object Reference](preface-and-legal-notices/26-mysql-sys-schema/264-sys-schema-object-reference.md)
      * 26.4.1 sys Schema Object Index
      * 26.4.2 sys Schema Tables and Triggers
      * 26.4.3 sys Schema Views
      * 26.4.4 sys Schema Stored Procedures
      * 26.4.5 sys Schema Stored Functions
  * [27 Connectors and APIs](preface-and-legal-notices/27-connectors-and-apis.md)
    * 27.1 MySQL Connector/C
    * 27.2 MySQL Connector/C++
    * 27.3 MySQL Connector/J
    * 27.4 MySQL Connector/Net
    * 27.5 MySQL Connector/ODBC
    * 27.6 MySQL Connector/Python
    * [27.7 libmysqld, the Embedded MySQL Server Library](preface-and-legal-notices/27-connectors-and-apis/277-libmysqld-the-embedded-mysql-server-library.md)
      * 27.7.1 Compiling Programs with libmysqld
      * 27.7.2 Restrictions When Using the Embedded MySQL Server
      * 27.7.3 Options with the Embedded Server
      * 27.7.4 Embedded Server Examples
    * [27.8 MySQL C API](preface-and-legal-notices/27-connectors-and-apis/278-mysql-c-api.md)
      * 27.8.1 MySQL C API Implementations
      * 27.8.2 Simultaneous MySQL Server and Connector/C Installations
      * 27.8.3 Example C API Client Programs
      * 27.8.4 Building and Running C API Client Programs
      * 27.8.5 C API Data Structures
      * 27.8.6 C API Function Overview
      * 27.8.7 C API Function Descriptions
      * 27.8.8 C API Prepared Statements
      * 27.8.9 C API Prepared Statement Data Structures
      * 27.8.10 C API Prepared Statement Function Overview
      * 27.8.11 C API Prepared Statement Function Descriptions
      * 27.8.12 C API Threaded Function Descriptions
      * 27.8.13 C API Embedded Server Function Descriptions
      * 27.8.14 C API Client Plugin Functions
      * 27.8.15 C API Encrypted Connection Support
      * 27.8.16 C API Multiple Statement Execution Support
      * 27.8.17 C API Prepared Statement Handling of Date and Time Values
      * 27.8.18 C API Prepared CALL Statement Support
      * 27.8.19 C API Prepared Statement Problems
      * 27.8.20 C API Automatic Reconnection Control
      * 27.8.21 C API Common Issues
    * 27.9 MySQL PHP API
    * 27.10 MySQL Perl API
    * 27.11 MySQL Python API
    * [27.12 MySQL Ruby APIs](preface-and-legal-notices/27-connectors-and-apis/2712-mysql-ruby-apis.md)
      * 27.12.1 The MySQL/Ruby API
      * 27.12.2 The Ruby/MySQL API
    * 27.13 MySQL Tcl API
    * 27.14 MySQL Eiffel Wrapper
  * [28 Extending MySQL](preface-and-legal-notices/28-extending-mysql.md)
    * [28.1 MySQL Internals](preface-and-legal-notices/28-extending-mysql/281-mysql-internals.md)
      * 28.1.1 MySQL Threads
      * 28.1.2 The MySQL Test Suite
    * [28.2 The MySQL Plugin API](preface-and-legal-notices/28-extending-mysql/282-the-mysql-plugin-api.md)
      * 28.2.1 Types of Plugins
      * 28.2.2 Plugin API Characteristics
      * 28.2.3 Plugin API Components
      * 28.2.4 Writing Plugins
    * [28.3 MySQL Services for Plugins](preface-and-legal-notices/28-extending-mysql/283-mysql-services-for-plugins.md)
      * 28.3.1 The Locking Service
      * 28.3.2 The Keyring Service
    * [28.4 Adding New Functions to MySQL](preface-and-legal-notices/28-extending-mysql/284-adding-new-functions-to-mysql.md)
      * 28.4.1 Features of the User-Defined Function Interface
      * 28.4.2 Adding a New User-Defined Function
      * 28.4.3 Adding a New Native Function
    * [28.5 Debugging and Porting MySQL](preface-and-legal-notices/28-extending-mysql/285-debugging-and-porting-mysql.md)
      * 28.5.1 Debugging a MySQL Serve
      * 28.5.2 Debugging a MySQL Client
      * 28.5.3 The DBUG Package
  * [29 MySQL Enterprise Edition](preface-and-legal-notices/29-mysql-enterprise-edition.md)
    * 29.1 MySQL Enterprise Monitor Overview
    * 29.2 MySQL Enterprise Backup Overview
    * 29.3 MySQL Enterprise Security Overview
    * 29.4 MySQL Enterprise Encryption Overview
    * 29.5 MySQL Enterprise Audit Overview
    * 29.6 MySQL Enterprise Firewall Overview
    * 29.7 MySQL Enterprise Thread Pool Overview
  * 30 MySQL Workbench
  * [A MySQL 5.7 Frequently Asked Questions](preface-and-legal-notices/a-mysql-57-frequently-asked-questions.md)
    * A.1 MySQL 5.7 FAQ: General
    * A.2 MySQL 5.7 FAQ: Storage Engines
    * A.3 MySQL 5.7 FAQ: Server SQL Mode
    * A.4 MySQL 5.7 FAQ: Stored Procedures and Functions
    * A.5 MySQL 5.7 FAQ: Triggers
    * A.6 MySQL 5.7 FAQ: Views
    * A.7 MySQL 5.7 FAQ: INFORMATION\_SCHEMA
    * A.8 MySQL 5.7 FAQ: Migration
    * A.9 MySQL 5.7 FAQ: Security
    * A.10 MySQL 5.7 FAQ: NDB Cluster
    * A.11 MySQL 5.7 FAQ: MySQL Chinese, Japanese, and Korean Character Sets
    * A.12 MySQL 5.7 FAQ: Connectors & APIs
    * A.13 MySQL 5.7 FAQ: Replication
    * A.14 MySQL 5.7 FAQ: MySQL Enterprise Thread Pool
    * A.15 MySQL 5.7 FAQ: InnoDB Change Buffer
    * A.16 MySQL 5.7 FAQ: InnoDB Tablespace Encryption
    * A.17 MySQL 5.7 FAQ: Virtualization Support
  * [B Errors, Error Codes, and Common Problems](preface-and-legal-notices/b-errors-error-codes-and-common-problems.md)
    * B.1 Sources of Error Information
    * B.2 Types of Error Values
    * B.3 Server Error Codes and Messages
    * B.4 Client Error Codes and Messages
    * [B.5 Problems and Common Errors](preface-and-legal-notices/b-errors-error-codes-and-common-problems/b5-problems-and-common-errors.md)
      * B.5.1 How to Determine What Is Causing a Problem
      * B.5.2 Common Errors When Using MySQL Programs
      * B.5.3 Administration-Related Issues
      * B.5.4 Query-Related Issues
      * B.5.5 Optimizer-Related Issues
      * B.5.6 Table Definition-Related Issues
      * B.5.7 Known Issues in MySQL
  * [C Restrictions and Limits](preface-and-legal-notices/c-restrictions-and-limits.md)
    * C.1 Restrictions on Stored Programs
    * C.2 Restrictions on Condition Handling
    * C.3 Restrictions on Server-Side Cursors
    * C.4 Restrictions on Subqueries
    * C.5 Restrictions on Views
    * C.6 Restrictions on XA Transactions
    * C.7 Restrictions on Character Sets
    * C.8 Restrictions on Performance Schema
    * C.9 Restrictions on Pluggable Authentication
    * [C.10 Limits in MySQL](preface-and-legal-notices/c-restrictions-and-limits/c10-limits-in-mysql.md)
      * C.10.1 Limits on Joins
      * C.10.2 Limits on Number of Databases and Tables
      * C.10.3 Limits on Table Size
      * C.10.4 Limits on Table Column Count and Row Size
      * C.10.5 Limits Imposed by .frm File Structure
      * C.10.6 Windows Platform Limitations
  * D Indexes
  * MySQL Glossary

