      # Topics

  

● Script Installation

  

● Errors on package managers

  

● Help on linux

  

● Linux Services

  

● Symbolic linking

  

● alias

  

● tmux

  

● Wget

  

● find

  

     # Python installation

  

● If pip is not found there will be an error

● It will install

● If the package is already installed:

  
  

        # Go package installation

  

● Go scripts are scripts made with go-lang(go programming language).

● There are 2 installation methods.

a. Old version

b. New version

● Old version

a.

● New version

a. Downloading the package

b. Moving the file to /usr/bin( the default download place is)

  
  
  

        # Errors you may encounter

  

● Don’t close apt while installation

● Repository errors, if this happened you can fix it using

○ sudo apt edit-sources

● And more…

➔ For those kinds of errors what you have to do is

google/youtube { detail we will see this while we

learn Footprinting }

  

      #   Cont...

         ● Help

○ Some Commands have help

option.

■ <yourcommand> -h

■ <yourcommand> -help

■ <yourcommand> - -help

  

       # Linux Processes & Services

  

● As we interact with Linux, we create numbered

instances of running programs called

“processes”

● To get the processes:

○ ps [options]

● More commands

○ ps -> for process running on my shell

○ ps -A -> view all running process

○ ps -u username -> view users process

● PID - Process ID

  
  

       #  Cont…

  

● To stop process

○ Kill [options] [PID]

● More on kill

○ kill -19 PID -> to stop the process

○ kill -18 PID -> to resume the process we stopped

○ kill -9 PID -> to Stop a process immediately

○ … there are 31 options.

  
  

      # Foreground / background

  

● Thus far, we have run commands at the prompt and waited for them to complete. We

call this running in the “foreground.”

● Use the “&” operator, to run programs in the “background” or press ^Z

● To get the background process back to foreground

○ Fg

To stop a process going inside your shell just press ^C

  
  
  

       #  alias

  

● Used to give a name to some bunch of

commands.

● Example: if i wanted to name ls -la ‘rex so

any time i want to get output of ls -la i just

type rex

○ alias rex=’ls -la’

● But this doesn’t work after you closed the

terminal

● If you want to make it work…

○ You will add it to your shell config file

● Example for bash and fish, zsh…

  
  

       # Tmux - Terminal Multiplexer

  

● Tmux is used to classify our terminal work.

● You can install it using apt. On kali it is built-in

● Then to start it just type ‘tmux’\

● To Create config file type

○ nano .tmux.conf

○ Type this

■ unbind C-b

■ unbind l

■ set -g prefix C-a

■ unbind %

■ bind e split-window -h

■ bind o split-window -v

■ set -g base-index 1

■ setw -g pane-base-index 1

○ Save it | exit tmux and open again

  
  

      # Cont…

● To split horizontally

○ ^A then o

● To split vertically

○ ^A then e

● To exit

○ ^A then x or

○ just type ‘exit’

● To create tab

○ ^A then c

● To rename the tab

○ ^A then ,(comma)

● To switch tabs

○ ^A then <numbers>

○ TO switch partitions

■ ^A then <arrow>

● … for more you can google but be aware of our super key is ^A

  
  

    #  Wget

  

● Is a tool used to download files from websites/servers

● Syntax

○ wget [options] [link]

● wget https://tldp.org/LDP/intro-linux/intro-linux.pdf

  
  

     # find

  

● ON terminal if you want to search for files/folders/musics/videos,

we can use find command.

● It is very essential tool

● Syntax:

○ find [search path] [options] [search word]

- More commands

- find / -name “linux”

- find /home -perm 777

- find -type f | find -type d

  

                                                      