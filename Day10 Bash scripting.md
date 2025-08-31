 ## What is BASH
BASH  >> *Bourne Again Shell*
- it is a shell, that used to interact with your **kernel**
##  What is script?
- script is a file that contain shell commands in a simple and clear algorithm.
- The original is SH - bourne shell 
## Uses of bash 
- script development 
- Automation  task
- simplify ypur linux ability
- m
## Starting with Bash
- Bash file can have ".sh" extension but you can have it without sh too
- The file have to have excutable permission
- You can use any text editor u need: VIM, Nano, Vscode, gedit, cherrytree
**tmux can help** for handling when using Nano or Vim.
## Dispalying  output 
-  To start every bash script use **shebang**
*shebang used to tell the shell which interpreter is used  to execute the script.
     #!/bin/bash
     #!/bin/sh

- To display output on bash you just do 
      -  echo  "Your text here"
 - To run your project your project you can do:
        - /bin/bash hello.sh
        - ./hello.sh -> need x
        - hello -> need x
if u need to add new line on your code just add echo 
## Variable
- Bash Variable are same with python variable , with some exceptions.
- syntax
     - Variable_name=value
- Exeptions:
     - No space between the equal sign(=)
         - NAME="nathan" -> correct
         - NAME= "nathan" -> error
         - Never starts with numbers 
         - use double quotes only.
 - To use the variable we will use the Dollar sign $ before the variable name 
 - if u want to display the variable sticked with other text use ${variable name}
 - Bash variable are string by default.
## System variable
 - Are variable those are declared by the system
     - Ex >> $BASH, $BASH_VERSION, $PWD, $HOME, $PATH.
 - there are so many : LANG, TERM, MAIL, EDITOR, USER, SHELL
 - User display computer owner(host)
## Variable & Data Types
- As we saw, the previous method they create string only.
- So to create other data type we use declare.
- ### Arrays
     - a)  Arrays are lists or tuples on pyhton.
     - b)Syntax
        - i) var=("list1"  "list2"  "list3")
        - ii) to display echo 
             (1) ${var[0]}
        - iii) to get all the elements
              (1) ${var[@]}
         (i> To get the indexes
              (1)${!var[@]}
        ii) to get the length
              (1)${#var[@]}
          iii) to add element to the array
             1) var[4]='list5"
        iv)t to reove from the array
          (1)unset var[3]

## Bash input
## - On Bash we have 2 methods
   - 1 read finction
   -  2 Arguments
##  Bash read
- read used to accept inputs while the script is running
- syntax
    -  read -p "text to display " var
    - read -sp(silent prompt) "password:" var=> used to accept hidden text like password
         - ex : the pasword is unseen on linux, do u notice it?
     - read -a var => for accepting arrays(lists)
## Argument
- these haelps to get input before the script starts
- syntax 
    -  just use $0-$9 while u want to work with input
## comments 
- on bash the comments are    
     -  for mulit line we start with -;   << comment 
                                     afca
                                     efef
                        commnet    . we close with this



## Bash sleep 
- Sleep used to make a good waiting on  oru script
- syntax 
     -   sleep< number >  "minute by"




## Operation
- to mathematical operation you have to $((expressions))tion )
- we will use let key word for assigning variable 
# A arthimatic operation
- addition $((a+b))
- subtraction $((a-b))
- multiplication $((a*b))
- division $(a/b)
- exponential$((a**b))
- modulo $((a%b))
# B Assignment operation 
increment "let a+=3"
decrement "let a-=b"
multiply "let a*= 3"
divide  "let a/=3"
#  C Comparison operator
- Alphabetic comparison 
- Grater than => -gt
- less than => -lt
- Greater than and equal to => -le
- Equal => -eq
- Note equal =< -ne
  
  # if else condition
- on bash we don't have indentation like python but if u finished writing the body you type "fi"
- if you used [condition] => u will use alphabetic comparison 
- but for string you can use sign too
- if you used ((condition)) => you will use numeric comparison.


if [condition]
then 


if ( condition)


if [condition]
then 

if [condition]
then 
echo "true"
else
echo "false"
fi


echo "ABcd"


## Nested if



