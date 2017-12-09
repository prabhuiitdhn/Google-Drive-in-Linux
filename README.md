This is about how we can access the google drive in linux operating system as a driectory. 
If you prefer the command line, there are tools such as Grive2 and the incredibly easy to use FUSE-based system written in Ocaml.

This system features:
1. Full read/write access to ordinary files/folders
2. Read-only access to Google Docs, sheets, and slides
3. Access to your Drive's Trash (.trash) Directory
4. Duplicate file handling
5. Support for multiple accounts

Installation
1. Open terminal using ctrl+alt+T
2. Add the neccessary PPA with command
   sudo add-apt-repository ppa:alessandro-strada/ppa
3. Update the apt-get using sudo apt-get update
4. Now, Install google-drive-ocamlfuse
   sudo apt-get install google-drive-ocamfuse
  
Now, It's confirmed that you have installed driver successfully now for authentication
Open terminal
Type the following command and press Enter
>> google-drive-ocamlfuse
You'll get opened browser for authentication for accessing the google drive in Linux-operating-system.

Now, makedir in linux os
>>mkdir ~/google-drive
>> google-drive-ocamlfuse ~/google-drive // for mount your Google Drive to the google-drive folder.

When you want to unmount the google-drive folder, issue the command
>> fusermount -u ~/google-drive.




