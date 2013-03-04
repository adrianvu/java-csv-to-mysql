java-csv-to-mysql
=================

Motivation
=================
Script in Java to load huge data from CSV file into MySQL database. Needed a way to load more than 500,000 rows in a single CSV file (filesize: 60mb).

Libraries used
=================
  - OpenCSV (http://opencsv.sourceforge.net/)
  - JDBC Connector (http://dev.mysql.com/downloads/connector/j/)

Usage:
=================
Compile:
javac App.java

Run (make sure to have the jdbc.jar file in the same directory):
java -cp .;jdbc.jar App
