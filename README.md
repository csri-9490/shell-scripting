# Topics

1. She-Bang & Comments 
2. Print 
3. Variables 
4. Inputs
5. Re-directors (> , <) , Exit Status, Quotes
6. Functions 
7. Conditions 
8. Loops
9. SED command 

Scripts we usually end with type of scripting language we are using.
1. Bourne Shell - .sh 
2. Korn Shell - .ksh 
3. C Shell - .csh 
4. Z Shell - .zsh 

Scripting we are learning here is Bash shell scripting.
5. Bourne Again shell - .bash 

Bash is default in all the enterprise Linux OS (redhat, ubuntu, suse)

In Redhat , SH & BASH are same.

Thats why even for  bash we are giving an extention of .sh 


-----------

Script can be executed with interpreter directly

sh 02-print.sh 

NOTE: Assume the script is having she-bang and the above method of executing the script will override the she-bangs interpreter

Or we can provide executable permission and then execute it 
chmod ugo+x 02-print.sh
chmod +x 02-print.sh

./02-print.sh

