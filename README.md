# cybersecurity-course-notes 
(ctrl+tab= right , ctrl+shift+tab= will go left))**
notes here

$sudo apt install cmatrix  -> will install package cmatrix
APT-Advanced Package Tool

$man cmatrix
man- inshort Manual

sudo                                         # means super use do
$sudo apt remove cmatrix
$pwd                                         # means print working directory (shows current directory
$cd ..                                       # it wil turn back to previous home directory
$ls                                          # means list
$ls -l                                       # will list in detailed (to show file type and access permission)
$cp hello.txt hellonew.txt                   # this means the contents or file will copy and create new in hellonew.txt
$mousepad hello.txt                           # we can edit this text with mousepad (a platform that can edit text TEXT EDITOR FILE)
$sudo cp hello.txt superuserhello.txt         #with super user persmission
$mousepad superuserhello.txt                 #(when u edit this and hit save it will show u cantedit) you cant edit this because you only have read access you dont have the write access
#sudo mousepad superuserhello.txt            #YOU WILL HAVE NO PROBLEM EDITING THIS SINCE U COPIED THIS FILE WITH SUDO YOU WILL HAVE NO PROBLEM EDITING THIS WITH SUDO MOUSPAD
<MOVING FILE>
#mv hello.txt newfolder
<DElETING FILE>
#rm hello.txt





pwd                       # Print current directory path
ls                        # List directories
ls -a|--all               # List directories including hidden
ls -l                     # List directories in long form
ls -l -h|--human-readable # List directories in long form with human readable sizes
ls -t                     # List directories by modification time, newest first
stat foo.txt              # List size, created and modified timestamps for a file
stat foo                  # List size, created and modified timestamps for a directory
tree                      # List directory and file tree
tree -a                   # List directory and file tree including hidden
tree -d                   # List directory tree
cd foo                    # Go to foo sub-directory
cd                        # Go to home directory
cd ~                      # Go to home directory
cd -                      # Go to last directory
cd ..	                    # Move one level up
pushd foo                 # Go to foo sub-directory and add previous directory to stack
popd                      # Go back to directory in stack saved by `pushd`
