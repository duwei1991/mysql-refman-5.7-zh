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
    * 6.2 The MySQL Access Privilege System
    * 6.3 MySQL User Account Management
    * 6.4 Using Encrypted Connections
    * 6.5 Security Plugins
  * 7 Backup and Recovery
  * 8 Optimization
  * 9 Language Structure
  * 10 Character Sets, Collations, Unicode
  * 11 Data Types
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

