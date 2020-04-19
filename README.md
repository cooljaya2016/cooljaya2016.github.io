## 18-04-2020 Saturday
 -I have learnt the [Php Forms](https://www.w3schools.com/PHP/php_forms.asp) and [Php Advanced](https://www.w3schools.com/PHP/php_date.asp) from w3 School.
  
  -Php Forms:
  
       1.PHP Form Handling:
       
            -The PHP superglobals $_GET and $_POST are used to collect form-data.
            
        2. PHP Form Validation:
        
             -Text Fields
             -Radio Buttons
             -The Form Element
             
             
    -Php Advanced:
          1. PHP Date and Time:
               -The PHP date() function is used to format a date and/or a time.
           2. PHP File Handling:
               -File handling is an important part of any web application. You often need to open and process a file for different tasks.
     -PHP Cookies:
          1. Create Cookies With PHP:
               A cookie is created with the setcookie() function.

              Syntax:
             setcookie(name, value, expire, path, domain, secure, httponly);
 -----------------------------------------------------------------------------------------------------------------------
               
## 17-04-2020 Friday
- I have read about moodle from this link [moodle](https://docs.moodle.org/dev/Tutorial).
- I have learnt the php from w3 school.
------------------------------------------------------------------------------------------------------------------
## 15-04-2020 Wednesday
 I was working on project.
 some error occuring on Login page Detail such as all things are blank on  the page.
 - I Designed generate Question paper in which many options such as:
 1. Subject
 2. Branch
 3. Exam Type
 4. Subject Code
 5. Semester
 6. Year
 7. Duration
 8. Total Marks

 -------------------------------------------------------------------------------------------------------------------------
## 14-04-2020 Tuesday
- I watched a lot of videos related to own project from youtube.
- I read the all concept of virtualization.
[virtualization](https://en.wikipedia.org/wiki/Virtualization)
- I read the 5 email message in GD group.

------------------------------------------------------------------------------------------------------------------------
## 13-04-2020 Monday
 I have completed jquery, Ajax from W3 school
 [jquery](https://www.w3schools.com/xml/ajax_intro.asp)
 
 - I Designed login Detail page in which have many options such as:
 1. Faculty name
 2. Faculty ID
 3. Subject
 4. Branch
 5. Contact no
 6. Email ID
 ---------------------------------------------------------------------------------------------------------------

## 12-04-2020 Sunday
 I have completed Bootstrap from w3 school
 [Bootstrap](https://www.w3schools.com/bootstrap/)
 
 -----------------------------------------------------------------------------------------------------------------
 
## 11-04-2020 Saturday
 I Designed new page In which have many options such as:
  1. Add Question
  2. Show Question
  3. Delete Question
  4. Generate Question Paper
  5. Logout
  6. login Detail
 
------------------------------------------------------------------------------------------------------------------
## 10-04-2020 Friday
 I designed my project on login pages In which my login page has username and password and two option like login and cancel.
 
 -----------------------------------------------------------------------------------------------------------------------

## 9-04-2020 Thursday
 I Read about my project Today.
 I Learned a little bit about LDAP.
 
 --------------------------------------------------------------------------------------------------------------------

## 13-03-2020 Friday
I have completed Sqlite tutorial from software carpentry
[sqlite](https://swcarpentry.github.io/sql-novice-survey/)

---------------------------------------------------------------------------------------------------------------
## 12-03-2020 Thursday
I have completed task multiple image combine into single image using this command

### convert  *.gif +append abc.gif
 I have changed the colour of image using this command
 
### convert gip4.gif -fill blue -opaque black  abc.gif
 
I have completed half sqlite tutorial from software carpentry 
[sqlite](https://swcarpentry.github.io/sql-novice-survey/05-null/index.html)
 
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
