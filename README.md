# IMAP Brute Force
A Python Program that uses **imaplib** module to brute force IMAP (Internet Messaging Access Protocol).
## Requirements
Language Used = Python3<br />
Modules/Packages used:
* imaplib
* datetime
* optparse
* colorama
* multiprocessing
* time
<!-- -->
## Arguments
* '-s', "--server" : Target IMAP Server
* '-p', "--port" : Port of Target IMAP Server (Default=143)
* '-S', "--ssl" : Use SSL for Connection (True/False, Default=True)
* '-u', "--users" : Target Users (seperated by ',') or File containing List of Users
* '-P', "--password" : Passwords (seperated by ',') or File containing List of Passwords
* '-c', "--credentials" : Name of File containing Credentials in format ({user}:{password})
* '-w', "--write" : CSV File to Dump Successful Logins (default=current data and time)