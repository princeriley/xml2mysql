# Background #
The project was initially developed to convert XML to CSV quickly. But later with QT platform it enabled us to extend the project scope and implement XML to MySQL data migration features in the project.

## Platform support and XQuery Language ##
We have tested this on various platforms and with the support of QT4 SDK we have able to run it on Linux, MacOS, Windows platforms with QTXmlPattern Library, it enables XQuery language support in our project. XQuery is a extensible language similar to SQL and the full documentation is available online on w3.org (http://www.w3.org/TR/xquery/)

## Features ##
  * XML File can be described using basic XQuery Languge
  * Allows only two inputs (XML Data file, XQuery input) and generate the SQL Bulk Insert statements.
  * Can format output to suit your need, SQL Bulk Insert, CSV, etc.
  * Fast enough to process a complex 30MB XML file in 20 Seconds using Intel Celeron DualCore 1.5MHz, 2GB computer
  * Runs on Unix,Linux, MacOS, Windows Platforms (Completely written in QT Framework)