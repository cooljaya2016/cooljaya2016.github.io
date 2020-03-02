## 29-1-2020 Wednesday
# How to install the ububtu 18.04 step by step.
# [ubuntu](https://www.linuxtechi.com/ubuntu-18-04-lts-desktop-installation-guide-screenshots/)
---------------------------------------------------------------------------------------------

## 30-1-2020 Thursday
Today I have Finished Install the mysql.
# How to mysql install from command line step by step
- Install the MySQL database server package.
You can use the Yum tool to install MySQL on Oracle Linux: sudo yum install mysql-community-server.

- Start the MySQL service:
sudo service mysql start

- Launch the MySQL Command-Line Client:
mysql -u root -p
The -p option is needed only if a root password is defined for MySQL. Enter the password when prompted.

- Create a user (for example, amc2) and a strong password:
mysql> create user 'amc2' identified by 'amc2';

To restrict the access to a machine (for example, to localhost for a user) create the user as follows:

- mysql> create user 'amc2'@'localhost' identified by 'amc2';

Create the database (for example, amc2) and grant all access to the user, for example, amc2 as follows:
- mysql> create database amc2;

- mysql> grant all on amc2.* to 'amc2';

Configure your MySQL installation to handle large BLOB entries, such as MSI binaries. To handle BLOB entries, edit the my.cnf file.
You can find the my.cnf file in one of the following locations:

/etc/my.cnf

/etc/mysql/my.cnf

$MYSQL_HOME/my.cnf

[datadir]/my.cnf

Set the options max_allowed_packet and innodb_log_file-size in the [mysqld] section to the values shown:
[mysqld]
max_allowed_packet=300M
innodb_log_file_size=768M

------------------------------------------------------------------------------------------------------------------
## 19-02-2020 Wednesday
# How to change the multiple file extension?
script1.sh

#!/bin/bash

srcpath=$1

dstpath=$2

echo $1 #print source directory name when user pass first the arugement

echo $2 #print destination directory name when user pass the second argument.

mkdir -p "$dstpath" # make a destination directory.

cp -r $srcpath/* $dstpath # copy source file into destinaton file.

for srcpath # check the source directory.

do

 for file in $(ls $dstpath/*.*)                 # check the all file  with extension in destination directory. 

  do

 echo $(mv -v $file  ${file%.*}.txt)               # remove the different-2 extension into single extension.

  done
done
## 2-03-2020 Monday
 Today I have completed the synopsis of our project.
 I have made the github  page from this link [github_page](https://guides.github.com/features/pages/)
 
 ------------------------------------------------------------------------------------------------------------------
