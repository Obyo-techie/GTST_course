
# File structure in detail
1) / ( root ) 

2) ○ Every single ﬁle and directory starts from the root directory 

3) ○ The only root user has the right to write under this directory 

4) ○ /root is the root user’s home directory, which is not the same as /


# File structure in detail
2) bin - Binary executables

○ Essential command binaries that need to be available in single-user mode; for all 
users i) e.g) cat, ls, cp,pwd 

# File structure in detail
3) /boot - Boot loader ﬁles

○ Kernel initrd, vmlinux, grub ﬁles are located under /boot 

○ Example: initrd.img-2.6.32-24-generic, vmlinuz-2.6.32-24-generic

# File structure in detail
4) /etc - et cetera

○ Contains conﬁguration ﬁles required by all programs. 

○ This also contains startup and shutdown shell scripts used to start/stop individual programs. 

○ Example: /etc/resolv.conf, /etc/logrotate.conf.


# File structure in detail
5) /home - Home directory

○ Home directories for all users to store their personal ﬁles. 

○ example: /home/nathan, /home/rexder

# File structure in detail
6) /lib - Libraries essential for the binaries in /bin & /sbin

○ Library ﬁlenames are either ld* or lib*.so.* 

○ Example: ld-2.11.1.so, libncurses.so.5.7
# File structure in detail

7) /media - Mount points for removable media such as CD-ROMs

○ Temporary mount directory for removable devices. 

○ Examples, /media/cdrom for CD-ROM; /media/ﬂoppy for ﬂoppy drives; /media/cd recorder for CD writer

# File structure in detail
8) /mnt - Temporarily mounted ﬁle

○ Temporary mount directory where sysadmins can mount ﬁlesystems.

# File structure in detail
9) /opt - Optional application software packages

○ Contains add-on applications from individual vendors. 

○ Add-on applications should be installed under either /opt/ or /opt/ sub-directory.

# File structure in detail
10) /sbin - Essential system binaries

○ Just like /bin, /sbin also contains binary executables. 

○ The linux commands located under this directory are used typically by system administrator, for system maintenance purpose.
# File structure in detail
11) /tmp - Temporary Files

○ Directory that contains temporary ﬁles created by system and users. 

○ Files under this directory are deleted when system is rebooted.

# File structure in detail
13) /usr - User Utilities

○ -  Contains binaries, libraries, documentation, and source-code for second level programs. 

○ - /usr/bin contains binary ﬁles for user programs. If you can’t ﬁnd a user binary under /bin, look under /usr/bin. For example: at, awk, cc, less, scp 

○ - /usr/sbin contains binary ﬁles for system administrators. If you can’t ﬁnd a system binary under /sbin, look under /usr/sbin. For example: atd, cron, sshd, useradd, userdel 

○ - /usr/lib contains libraries for /usr/bin and /usr/sbin 

○ /usr/src holds the Linux kernel sources, header-ﬁles and documentation.

# VIM

● Before vi the primary editor used on Unix was the line editor 

○ User was able to see/edit only one line of the text at a time 

● Then then vi editor improved and developed VIM. ( VI iMproved) 

● The vim editor is: 

○ a very powerful 

○ but at the same time it is cryptic

○ It is hard to learn, specially for windows users 

● It have mainly to modes 

○ Command mode -> where you can do commands 

○ Input mode -> where you can write 

# To get on insert mode you have to type
# (‘i’)

# Command mode
To get back to command mode 
you press (‘esc’)
# ● Inside Command mode you can 
○ Save 
○ Save & quit 
○ Force Quit & Save 
○ Undo 
○ Execute bash commands
# Save
Type :w + enter
# Quit
Type :q + enter

# Quit
Type :wq! + enter Force = !
# Undo
Type :undo + enter Or :u
# Type
:%!yourcommand
*the is no space between them
# Starting nano
Syntax
nano ﬁlename
Then start typing.

# Saving Exiting & Undo_redo

Ctrl + S - save

Alt + U - Undo 

the ^ is equal to ‘Ctrl’

Alt + E - Redo

Ctrl + X - Exit

Paste,Copy & paste all over the linux is

Ctrl+shift+C - copy

Ctrl+shift+X - Cut

Ctrl+shift+V - Paste   
# To access root user
Command
"sudo su"



