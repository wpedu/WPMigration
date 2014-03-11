WPMigration
===========

A quick how to and screencast for migrating wordpress. [Screen Cast Video Download](http://wpedu.us/_downloads/WPMigration-opt.mov.zip)

### Prep Local Files and Database

1. zip wordpress folder
2. download zipped version of local database from phpMyAdmin

### Upload Local Files

1. connect via ftp
2. upload zipped wordpress into desired location. This will be the directory where wordpress will be accessed from the url. e.g. domainname.com/dev or just domainname.com

### Import local database

1. Create new database - youtube resource - http://www.youtube.com/watch?v=YbIn--iNmKE
2. import local database to new database - youtube resource - http://www.youtube.com/watch?v=jW5lrS6EUPM
3. update locale host domain with live domain. [example code sql-replace.sql](sql-replace.sql)

### Connect wordpress to the database

1. expand the zipped wordpress files
2. open the wp-config.php and update the following: DB\_NAME, DB\_USER, DB_PASSWORD
3. update the permalinks