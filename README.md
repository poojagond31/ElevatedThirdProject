# ElevatedThirdProject
Download Bitnami drupal using a username and password to download drupal. 
Using phpmyadmin on the localhost (localhost/phpmyadmin).
Create a new database connection for drupal and give it a new username and password and database name if required. 
Import the database file in your laptop with phpmyadmin (which can be found here   ).
Go to '/sites/default/settings.php' of your drupal imstallation and change the database connection details on line 250 with the new databse,username and password (and port number is necessary)as given on the phpmyadmin.
Make changes to the “Database settings” section of the settings.php file, to ensure that they are pointing to the new database, with the right user.

USERNAME: user
PASSWORD: abcdefgh

Site name : Pooja
Database: bitnami_drupal7
