# Sublime-
Here are the basic steps required to run C++ and C programs in Sublime text 3 in Windows

Step 1- Adding path in environment variable
For this step I recommend you to first download MinGW,it is a gcc compiler.Copy the path of the bin of the gcc compiler.
e.g.C:\MinGW\bin
Now open the properties of My comuter or This PC > Advanced System Settings > Advanced > Environment Variables(in the bottom right corner)
Double click on path > New > Paste the path of the gcc compiler > Press all the OKs to save all the changes
You can change the sequence of the path by using move up and move down.

Step 2- Configuring Sublime Text
Open sublime text and go to Tools > Build System > New Build System and then paste the code available in the file name cppbuild for C++ and cbuild for C in this repsitory.
Then save it with the file name new_build
For running a program go to Tools>Build With and then select cppbuild or cbuild according to the language you are using.
