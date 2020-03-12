## 12-03-2020 Thursday
I have completed task multiple image combine into single image using this command

### convert *.gif +append abc.gif
 I have changed the colour of image using this command
 
 ### convert gip4.gif -fill blue -opaque black  abc.gif
 I have half-completed sqlite tutorial from software carpentary [https://swcarpentry.github.io/sql-novice-survey/05-null/index.html]
 
--------------------------------------------------------------------------------------------------------------
## 7-03-2020 Saturday
I have given seminar on outcome based education system.
 
------- ---------------------------------------------------------------------------------------------------------
## 5-03-2020 Thursday
I have revised the django and some topic of Project.

-------------------------------------------------------------------------------------------------------------
## 4-03-2020 Wednesday
I have read about some topic in the project.

--------------------------------------------------------------------------------------------------------------
## 3-03-2020 Tuesday
 I have completed all blogs on github pages.
 
--------------------------------------------------------------------------------------------------------------
## 2-03-2020 Monday
 I have completed the synopsis of our project.
 I have made the github  page from this link [github_page](https://guides.github.com/features/pages/)
 
 ------------------------------------------------------------------------------------------------------------------
## 29-02-2020 Saturday
 I have read key points of Programming with Python from given below link.

[Key Points](http://swcarpentry.github.io/python-novice-inflammation/reference/#comma-separated-values)

------------------------------------------------------------------------------------------------------------------
## 27-02-2020 Thursday
I have prepared the synopsis of  Outcome based Education System
###  **Keypoints of Synopsis**:
- INTRODUCTION:
Outcome-based education (OBE) is an approach to education in which decisions about the curriculum are driven by the exit learning outcomes (LO) that the students should display at the end of the course. LO as being something that student can do now that they could not do previously’ are changes in people as a result of learning experience.
- OBJECTIVES
1. To increase the knowledge and skills of the learners.
2. It will automate the system and save the time and efforts of the teachers in  making question papers.
3. It will stop repetition of question papers.
- FEASIBILITY STUDY
- LITERATURE REVIEW
- METHODOLOGY & PROBLEM FORMULATION:
The LoQET’s main fuctional  requirements are illustrated in a use case Diagram. The use case diagram shows the actors (I.e Lecturer and e-SMP) that interact with LoQET functionalities. The e-SMP will provide input regarding on course teaching plan and course assessment percentage entries. This input will be informed to the lecturer when she / he wants to compose a question paper for the particular course. Lecturer should also able to export question paper, reset or reorganize the question paper and view question paper. Other basic and common functionalities, such as create, retrieve,update, and delete are also offered.

- LoQET’s component diagram:
1. LoQETui=This component should provide a user- friendly user interface design for lecturers.
2. ComponentQues=The component should provide a main feature of LoQET to compose a set of question, which aligns with learning outcomes and program outcomes. The feature includes creating, deleting or editing these questions.
3. ManagePaper=The component should allow the lecturer to add, delete and edit an examination paper details.
4.ExportPaper=The comnent should allow the lecturer to export composed  exam paper in to several formats such as pdf and txt. 
5.Authorization=The component should verify the user login.
6.DB=The component should store LoQET data onto tables.

- REQUIREMENT ANALYSIS
- FUTURE SCOPE
1. Educators should change or improve their ways of instructing and accessing the learner’s work.
2. Content is integrated and learning is relevant and connected to real- life situations.
3. Learning programmes are seen as guides that allow teachers to be innovative and creative in designing their programmes.
 
  - REFERENCES            
  [https://acadpubl.eu/hub/2018-119-17/4/442.pdf]
  [https://files.eric.ed.gov/fulltext/EJ1090186.pdf]


--------------------------------------------------------------------------------------------------------------------
## 20-02-2020 Thursday
# How to remove the last three line from multiple file.

script3.sh

#!/bin/bash

for f in *.txt

do # tail command display the last 3 line and sed is used for delete the last line of file.

   tail -3 $f | sed   -i   '$d'  $f  | sed  -i  '$d'  $f |  sed   -i  '$d'  $f ;
done

-----------------------------------------------------------------------------------------------------------------
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

------------------------------------------------------------------------------------------------------------------

## 10-2-2020 Monday
 I have Finished Install the mysql.
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
## 04-2-2020 Tuesday
# Python in 90 Minutes
 I have read the concept of Python.
 [python](https://www.slideshare.net/MattHarrison4/learn-90)
 
------------------------------------------------------------------------------------------------------------------
## 3-2-2020 Monday
I have learnt the Boolean, operaters, lists, Tuples, Sets, If---else etc.

---------------------------------------------------------------------------------------------
## 02-2-2020 Sunday
I have starting learnt to python and I have learnt the basic, Syntax, variables from this link.
 [python](https://www.w3schools.com/python/python_variables.asp)

-----------------------------------------------------------------------------------------------------------------
## 01-2-2020 Saturday
Today I Understand Linux command, script, shortcuts etc.

----------------------------------------------------------------------------------------------------------------------
## 29-1-2020---31-1-2020
# How to install the ububtu 18.04 step by step.
# [ubuntu](https://www.linuxtechi.com/ubuntu-18-04-lts-desktop-installation-guide-screenshots/)
------------------------------------------------------------------------------------------------------------------
