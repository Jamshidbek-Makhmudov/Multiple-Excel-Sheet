# Split and Export into Multiple Excel Sheet Files using PHP

When we are dealing with huge volume of records export into excel or CSV, we cannot blindly export them into a file. Imagine we have a million records, what would happen if we export those records into a single excel file! In this kind of situation, we should group the records and split them into multiple files so that it will be easy to handle them.

Exporting a database records via program can be done in various ways. For example, we can do by using web interface with export action control or by requesting REST API providing export services. With the relevant necessity, people will also create the CRON job to take automatic backup by export periodically.

In this article, I have created a web interface with the Export button control. The MySQL database results are retrieved and listed in a web page with an Export option. While triggering the export action, the database results will be separated by a limit constant. By applying the limit barrier, the results are split and downloaded into multiple excel files.
