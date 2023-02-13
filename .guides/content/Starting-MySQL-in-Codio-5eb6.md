----------

## Introduction

This guide is designed to provide examples for practicing writing stored procedures in MySQL.  The basics of how to write a stored procedure have been introduced in class and the hand-on experience with these exercises will, hopefully, help you to better understand and retain skills with stored procedures. 

## Getting Started with this Codio Guide

You must first sign into the MySQL instance that is running in conjunction with this guide.  To do so, navigate to the window in the left pane with the heading that begins with  <code>gurusaturn-...</code> and sign into MySQL, as show in the first image below, and click on the instance to open it.  Next, enter the password (<code>codio</code>) where indicated in the second image below.  This window provides the same MySQL Workbench user interface with which you are already familiar and it permits you to navigate through the databases as well as view the administrative options.

![MySQL Login](.guides/img/jb/mysql_login1.jpg)
![MySQL Login](.guides/img/jb/mysql_login2.jpg)


This guide uses a MySQL database called <code>sales</code>.  In order to load it, please click on the button below, and then <code>Refresh All</code> in the database navigation area, if necessary, to see the <code>sales</code> database.  If the database crashes or you would like to start defining your stored procedures from scratch, you can click on the button below again.  Be aware, however, that the stored procedures you define with be _persistent_ unless you click on this button.  Clicking on this button returns the <code>sales</code> database to it original state.

  {Reset Database}(sh .guides/restart.sh) 











