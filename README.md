# Simple UNIX Shell

## What is shell ?

The shell is a [Command Line Interface(CLI)](https://en.wikipedia.org/wiki/Command-line_interface) that can be used to interact with the kernel of an Operating System OS
specifically for linux. It can basically do any task that a GUI file explorer
or file manager can do like navigating through folder deleting and creating files.
but with more flexable features like scripting. with scripting you can automate tasks
that are done frequently through out the day without the interfirence of humans
and many many more you can read more about shells here.

* [Unix shell wikipedia](https://en.wikipedia.org/wiki/Unix_shell)
* [What is shell tutorialspoint](https://www.tutorialspoint.com/unix/unix-shell.htm)

## About

This is a simple UNIX shell that performs some tasks that a standard UNIX shell
can perform. It was assignment project form our school [@HolbertonALX](https://www.alxafrica.com)

## Installation

To preceed with the installation process you will need the following tools.

* A machine that is running Linux distro.
* [Gcc compiler](https://gcc.gnu.org/)

If you got this two installed we can preceed
```
gcc -std=gnu89 *.c -o hsh
./hsh
```
Example input output:
```
SHELL> gcc -std=gnu89 *.c -o hsh
SHELL> ls
a.out  AUTHORS  DEV  hsh  lenv.c  lenv.h  lmemory.h  lstring.h  main.h  memory.c  README.md  shell.c  string_2.c  string.c  text
SHELL> ./hsh 
#cisfun$ ls
a.out  AUTHORS  DEV  hsh  lenv.c  lenv.h  lmemory.h  lstring.h  main.h  memory.c  README.md  shell.c  string_2.c  string.c  text

#cisfun$ ls
a.out  AUTHORS  DEV  hsh  lenv.c  lenv.h  lmemory.h  lstring.h  main.h  memory.c  README.md  shell.c  string_2.c  string.c  text

#cisfun$ ls
a.out  AUTHORS  DEV  hsh  lenv.c  lenv.h  lmemory.h  lstring.h  main.h  memory.c  README.md  shell.c  string_2.c  string.c  text

#cisfun$ test 

#cisfun$ test

#cisfun$ file
Usage: file [-bcCdEhikLlNnprsSvzZ0] [--apple] [--extension] [--mime-encoding]
            [--mime-type] [-e <testname>] [-F <separator>]  [-f <namefile>]
            [-m <magicfiles>] [-P <parameter=value>] [--exclude-quiet]
            <file> ...
       file -C [-m <magicfiles>]
       file [--help]

#cisfun$ jl   
./hsh : No such file or directory
#cisfun$ 
````

Now you are good to go.

### Feature supported for the moument
* Command execution
* Getting information about the envirnoment
* Others comming soon.

## Authors

* Nebiyu Samuel [nebiyuhiyabu@gmail.com]
* Mikias Abiy [mikiasabiy16@gmail.com]
