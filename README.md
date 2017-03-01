# dirfixer
</br>
</br>
!WARNING!</br>
This is made for UNIX/LINUX. Never tested this on windows. </br>
Python 3.6 used.</br>
/!WARNING!</br>
</br>
This is a pretty simple script i created to fix some bad downloadmanagement. The tool does nothing else than taking a target directory (by userinput) and search inside for subdirs to move all files out of them to the target DIR. 
</br>
As this may sound a little bit weird, a little showcase as example.</br>
</br>
</br>
Your target DIR, specified by ./dir_fixer.py [PATH/TO/DIR] probably looks like this:</br>
</br>
PATH/TO/DIR</br>
|</br>
|--SUBDIR001 </br>
   |- file 1 </br>
   |- file 2</br>
   |- file 3</br>
|</br>
|--SUBDIR002</br>
   |- alpha1</br>
   |- closedsource_sux</br>
   </br>
   </br>
and the output would be:</br>
</br>
PATH/TO/DIR</br>
|</br>
|- file1</br>
|- file2</br>
|- file3</br>
|- alpha1</br>
|- closedsource_sux</br>
</br>
</br>
As you may see, the subDIRs are going to be (!)deleted(!). I'll probably add some more functions to make this script more adjustable.</br>
</br>
But it works. Greetings :)</br></br></br></br></br>KnownBugs:</br></br>- Script stops when a filename is already existing. Going to add a exception for that.
