# autoGenHTML
program to automatically generate an HTML file with 
the "boiler plate" 

There are a couple files that can be used for this, but
the main one to focus on it the makeHTML.sh file.
This is a bash script.

To use, simply add makeHTML.shto your path.
To generate the html, run the command makeHTML.sh

Alternatively, you can specify the relative path to wherever
the makeHTML file is saved from the working directory. 
The html file will be created in the working directory.

For example, if the working directory is c:/chutes/ladders
and makeHTML.sh is in c:/chutes you would run the command
../makeHTML.sh [fileName] and the html file would be generated
in c:/chutes/ladders

One argument can be passed in for what the file will be named.
No need to add .html to the end of the file, the script will 
do that automatically. Nothing is done to handle the situation
where you do.