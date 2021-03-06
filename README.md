# friendsChat

An lightweight web chat application made for private chatting

## About

A sample web chat application with the folling features

* Registration with invite link
* chat storage in database
* abillity to change your own account details

when it is fully done it can be used for educational purposes, since it covers the the following topics

* setting up an api
* responsive design
* database handling
* basic security

### Prerequisites

* recent php
* recent mysql / mariadb
* recent apache2 server

The database is designed with staruml and generated with the DDL plugin available for staruml

### Installing

## with database creation rights
* copy the content of the html folder to the server main folder
* configure the database and the connection type on functions.php line 1-5
* configure the connection type in js/chat.js on line 1 (boolean)
* visit the website and make the admin account
* editing a few html tags in info.php to present the info you want to show

## without database creation rights

* run sql.sql in your database
* copy the content of the html folder to the server main folder
* configure the database and the connection type on functions.php line 1-5
* configure the connection type in js/chat.js on line 1 (boolean)
* visit the website and make the admin account
* editing a few html tags in info.php to present the info you want to show

## using

In the admin panel you can create links to share with people you know. those links are valid for 24 hours and can only be used once.

## Contributing

all Contributions to the project are welcome. You can help the project forward by making an issue or pull request

## Authors

* **Ard van der Marel** - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
