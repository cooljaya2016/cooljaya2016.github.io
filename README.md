## 29-1-2020 Wednesday
# How to install the ububtu 18.04 step by step.
# [ubuntu](https://www.linuxtechi.com/ubuntu-18-04-lts-desktop-installation-guide-screenshots/)

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

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cooljaya2016/cooljaya2016.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
