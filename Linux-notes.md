# Linux Notes
## Commands
pwd = show current directory.
ls = list files.
cd = change directory.
mkdir = create directory.
DIRB- Website Scanning.
whoami- shows who you are on the system.
echo- will output text that you have entered.
Cat- Displays the contents of a file in the terminal.
Touch- Creates a new empty file.
Rm- Remove File.
Rmdir- Remove an Empty Directory.
Find - Searches the Desktop for Files and Directories.
Cd .. - Leave directory

# # Practical Example: Using Kali Linux

# # I Created a Folder:
Used the command mkdir to create the folder in this case mkdir linux2

# Checked my current location: pwd
I used pwd to check which directory I was currently working in.
pwd
This showed that I was inside:
~/Desktop/linux2
This is useful because it lets me know exactly where I am in the Linux filesystem before running other commands.

# Checked the contents in the directory
I used ls to see what was inside my current directory.
ls
The directory was empty, so nothing was displayed.
I then used:
ls -la
This showed:
.
..
The . represents the current directory.
while .. represents the parent directory.

# Creating a file: Touch
I used touch to create a new file called
linuxTest.txt.
linuxTest.txt
This created an empty file that I could then write information into.

# Adding Text Into the File: Echo
I used echo together with > to write text into linuxTest.txt.
what I wrote is echo Testing123 > LinuxTest.txt. This put the text Testing123 into the file linuxTest.txt. > directs it into the file.

# Checking what's in the File: cat
I used the cat command to check what is in the file. 
cat LinuxTest.txt ---> it printed Testing123 Which is what I put into it with the command before.

# Checking the Contents: ls -l
using the ls -l command I checked the content of the directory this is what I got.
└─$ ls -la
total 12
drwxrwxr-x 2 mhassan mhassan 4096 Sep  8 18:24 .
drwxr-xr-x 3 mhassan mhassan 4096 Sep  8 18:21 ..
-rw-rw-r-- 1 mhassan mhassan    0 Sep  8 18:24 linuxTest.txt
-rw-rw-r-- 1 mhassan mhassan   11 Sep  8 18:24 LinuxTest.txt

# PERMISSIONS  LINKS  OWNER   GROUP   SIZE  DATE/TIME       NAME
     ↓          ↓      ↓       ↓      ↓        ↓              ↓
# -rw-rw-r--    1    mhassan mhassan  11   Sep 8 18:24   LinuxTest.txt

# OWNER | GROUP | OTHERS
# rw.     rw.      r--

# d = directory
# - = regular file

# r = read
# w = write
# x = execute

# .  = current directory
# .. = parent directory


