# WordPress inc. Microsoft SQL PHP Extension
Simply the [WordPress docker image](https://hub.docker.com/_/wordpress/) with 
the addition of compiled PECL MSSQL libraries included. This fufils the 
requirements needed for Microsoft SQL database communication plugins.

Adds the following to the regular WordPress Docker installation:
* Unix ODBC.
* Microsoft ODBC.
* Microsoft SQL extension for PHP (including PDO).

[Available on the Docker Hub](https://hub.docker.com/r/soupbowl/wordpress-mssql/).