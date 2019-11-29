# Read this for information about how to create and run python programs

We've covered some very basic Command Prompt commands at meetings, to create and run python programs. Below are some key commands that you can use in the command prompt to get things going. 

Command Prompt is also called the terminal, or command line.

** PC (windows 10) **

Type: 
cmd
into the search field at the bottom left of your taskbar (it has a little magnifying glass and the prompt 'Type here to search'). 
You'll see a Best match showing Command Prompt App. Click this one. 

It will open a window probably black and white, with a cursor flashing next to a few lines of text saying something like: 
C:\Users\someonesname>_
This is your root directory. The directory will always show like this. 

The way your computer is set up might be different but generally there will be a documents folder. To move into a sub directory (for example 'Documents') use the command:
C:\Users\someonesname> cd documents

This will move you into the documents directory
C:\Users\someonesname\Documents>

To move out of that directory into the parent directory type: 
C:\Users\someonesname\Documents> cd ..

To create a new directory such as 'my_code_projects' type: 
C:\Users\someonesname\Documents> mkdir my_code_projects

If you now type 
C:\Users\someonesname\Documents> dir

You'll see a list of files in that directory. 

To create a new file type: 
C:\Users\someonesname\Documents> type nul > new_file_name.extention

If we're creating a python file type:

C:\Users\someonesname\Documents> type nul > my_new_file.py 

Obviously, you name it whatever it needs to be called (not necessarily my_new_file)

** Linux / Mac **

To move into and out of directories, see above (cd directory_name, cd ..)

To create a new file, use the command 'touch', for example type :
C:\Users\someonesname\Documents> touch new_file_name.py (of whatever extention you need)

To view files in a directory type: 
C:\Users\someonesname\Documents> ls 

To see everything in that directory add the -a flag: 
C:\Users\someonesname\Documents> ls -a 



** Alternatives**

You don't need to use the Command Prompt to run python files.

You can also use the built in Python IDLE editor that comes with it when you install the language.
Check in the Python folder in Applications. 
From this program you can create a new file (under file on the menu bar) and run it from that window (you'll see Run in the menu bar).

You can also double click on a python file from file explorer and it will run, you just won't be able to see all the helpful error messages you get when you run it in command prompt.
