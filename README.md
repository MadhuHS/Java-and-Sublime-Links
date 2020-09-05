jdk link : https://www.oracle.com/java/technologies/javase-downloads.html

sublime text link : http://sublimetext.com/


Changing Build System in Sublime Text

Step 1 :  click on tool

Step 2 :  select Build Sytem

Step 3 :  Select New Build System

Step 4 :  Copy and Paste below code 

{
    "shell_cmd": "javac $file && java $file_base_name"
}

Step 5 : Save file with the name JavaRun

Step 6 :  click on tool

Step 7 :  select Build Sytem

Step 8 :  Select JavaRun

Step 9 : Select Build

You should see the output of your program below.






