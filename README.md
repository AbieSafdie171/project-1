# UO CS 322 - Project 1


Abie Safdie

asafdie11@gmail.com

Project 1 - A simple web server


# What this project is

This project creates a simple web server that displays a page if a specific file 
is found in the directory that is specified in the credentials file. 
The directory is saved in the variable docroot.


If a url request contains a file that does not exist the page will display a 404
error: file not found. If the request contains forbidden characters it will 
display a 403 error: forbidden characters. 

This server only accepts GET requests and if it receives anything else it will 
throw a status not implemented error.


