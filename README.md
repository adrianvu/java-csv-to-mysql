java-csv-to-mysql
=================

Motivation
=================
Needed a way to load more than 500,000 rows in a single CSV file (huge filesize of 60mb) into MySQL database. Scripted in Java to read each line of CSV file and insert into MySQL database in batches of 100 to speed things up.

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
