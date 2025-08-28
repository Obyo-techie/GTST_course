# kali linux 
### one type of os that is Debian based 
_**What is command “Small programs that do one task well”**_
# ls / List Directory
List information about the FILEs (the current directory by default).
# cd / Change Directory
It is used to change current working directory.
# Pwd / print working directory
It prints the path of the working directory, starting from the root.
# echo
echo command in linux is used to display line of text/string that are passed as an argument
● You can write texts into ﬁles. **○ echo text > ﬁle.txt** **● You can add texts(append)** **○ echo text >> ﬁle.txt**

# cat / head / tail /less
Used to show the content of a ﬁle

# touch
Creates any kind of Files with the name you gave it. With empty inside
# Mkdir / make directory
Creates Folder with the name u gave it
# rm / remove
SYNOPSIS -rm [FILE1] [FILE2] [FILE3] DESCRIPTION -Remove ﬁle.
# cont…

● rm -r => recursive(4 folders) ● rm -i => for prompt(ask) ● rm -f => force delete
# Cp| mv / copy,move
SYNOPSIS cp [oldFILEplace] [newﬁlePlace] Mv [oldFILEplace] [newﬁlePlace] DESCRIPTION Copy/move ﬁles & folders.
# awk
awk '{print $0}' gtst.txt

awk '{print NR,$0}' gtst.txt

awk '/something/ {print}' gtst.txt

NR(Number Record)

**For Example.**

_1 microsoft saler account 100,000,000_

_2 linux buyer account 200,000,000_

_3 apple marketer 300,000,000_

awk 'NR==3 {print NR,$0} ' gtst.txt

**output =** _2 linux buyer account 200.000.000_

**OR** awk 'NR= =3(-end of the line) {print NR,$0}'

**output =** _2 linux buyer account 200,000,000_ _3 apple marketer 300,000,000_
# sed
_sed 's/FIND/REPLACE/' gtst.txt_

**for all replacing type "g"**

_sed 's/FIND/REPLACE/g' gtst.txt_ **deleting type "d"**

_sed '/apple/d' gtst.txt_ **sed G gtst.txt**

_adding space type "G"_ **deleting new lines**

_sed '/^$/d' gtst.txt_
# awk
awk '{print $0}' gtst.txt awk '{print NR,$0}' gtst.txt awk '/something/ {print}' gtst.txt NR(Number Record) *For Example. 1 microsoft saler account 100,000,000 2 linux buyer account 200,000,000 3 apple marketer 300,000,000 **awk 'NR= =3 {print NR,$0} ' gtst.txt

**output =** 3 linux buyer account 200.000.000 **OR** awk 'NR= =3(-end of the line) {print NR,$0}' **output =** 2 linux buyer account 200,000,000 3 apple marketer 300,000,000

# sed
_sed 's/FIND/REPLACE/' gtst.txt **for all replacing type "g"** sed 's/FIND/REPLACE/g' gtst.txt **deleting type "d"** sed '/apple/d' gtst.txt **sed G gtst.txt** adding space type "G" **deleting new lines** sed '/^$/d' gtst.txt_
# grep - global search for regular expression

● grep -i “search” ﬁle

○ - case insensitive

● grep -c “search” ﬁle

○ - count numbers

● grep -l “search”

○ - displays ﬁlename

● grep -R “search” foldername

○ - search text in folders

● grep -v ‘term’ ﬁlename

○ To display without this term

● grep -n “term” ﬁle

○ To display the term ﬁnd number

# Wc - word count

It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments. **Line(-l) word(-w) byte(-c)
# Piping ( | )
On pipe, will help you run commands by using the output of the 1st command as the input for the next one