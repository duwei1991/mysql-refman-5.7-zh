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
    * 11.6 The JSON Data Type
    * 11.7 Data Type Default Values
    * 11.8 Data Type Storage Requirements
    * 11.9 Choosing the Right Type for a Column
    * 11.10 Using Data Types from Other Database Engines
  * 12 Functions and Operators
  * 13 SQL Statement Syntax
  * 14 The InnoDB Storage Engine
  * 15 Alternative Storage Engines
  * 16 Replication
  * 17 Group Replication
  * 18 MySQL Shell User Guide
  * 19 Using MySQL as a Document Store
  * 20 InnoDB Cluster
  * 21 MySQL NDB Cluster 7.5 and NDB Cluster 7.6
  * 22 Partitioning
  * 23 Stored Programs and Views
  * 24 INFORMATION\_SCHEMA Tables
  * 25 MySQL Performance Schema
  * 26 MySQL sys Schema
  * 27 Connectors and APIs
  * 28 Extending MySQL
  * 29 MySQL Enterprise Edition
  * 30 MySQL Workbench
  * A MySQL 5.7 Frequently Asked Questions
  * B Errors, Error Codes, and Common Problems
  * C Restrictions and Limits
  * D Indexes
  * MySQL Glossary

