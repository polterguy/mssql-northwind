# SQL Server Northwind database

Northwind SQL Server database script plugin for Magic that installs the Northwind database into
your _"/etc/mssql/templates/"_ folder for you. Notice, this plugin does _not_ create
the database for you, or execute the SQL script in any ways, since that requires a valid
SQL Server connection, which we cannot determine with certainty that you actually have.

## Installation

Install this module in your Magic backend, open up SQL Studio, load the northwind script,
and execute it towards a valid database SQL Server connection.
