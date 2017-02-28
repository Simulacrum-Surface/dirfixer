# dirfixer


!WARNING!
This is made for UNIX/LINUX. Never tested this on windows. 
Pyhton3.6 used.
/!WARNING!

This is a pretty simple script i created to fix some bad downloadmanagement. The tool does nothing else than taking a target directory (by userinput) and search inside for subdirs to move all files out of them to the target DIR. 

As this may sound a little bit weird, a little showcase as example.


Your target DIR, specified by ./dir_fixer.py [PATH/TO/DIR] probably looks like this:

PATH/TO/DIR
|
|--SUBDIR001
   |- file 1
   |- file 2
   |- file 3
|
|--SUBDIR002
   |- alpha1
   |- closedsource_sux
   
   
and the output would be:

PATH/TO/DIR
|
|- file1
|- file2
|- file3
|- alpha1
|- closedsource_sux


As you may see, the subDIRs are going to be (!)deleted(!). I'll probably add some more functions to make this script more adjustable.

But it works. Greetings :)
