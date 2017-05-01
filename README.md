# ElevatedThirdProject
Download Bitnami drupal using a username and password to download drupal 

Go to the host and login and get to the server

In the backend Create a database, add new database (give some name to the database)

Now add a new database user give this database a new username and password

Go to phpmyadmin from the host and go to the databse just created and import the files given which can be found here (https://drive.google.com/file/d/0B9Cs9jcsuHJLNUpXZ2RZQVdNRFk/view?usp=sharing) .

Now uncompress the Drupal file directories and move them to the server using FTP.

Go to '/sites/default/settings.php' of your drupal installation and change the database connection details on line 250 with the new database,username and password (and port number is necessary)as given while creating new database user on the host.

This is to ensure that they are pointing to the new database, with the right user.

Here is the username and password I used

USERNAME: user 

PASSWORD: abcdefgh

Site name : Pooja

Database: bitnami_drupal7


Comments:
I have used Sunrise theme for this project, The website made is not exactly like it was told but similar to that and as per the given conditions. Let me know if I missed out on something or there is any thing not done properly. With the code and file I have also uploaded an image of the website as how it looks (screencapture.png). 
