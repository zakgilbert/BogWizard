## How to write a Bash script and run it Globally
In your linux terminal create a directory to hold your scripts and then a sub directory to for the hello script.
```bash
$ mkdir scripts
$ cd scripts
$ mkdir hello
$ cd hello
```
Now create a file called hello using the `touch`command this is where you write the script. You'll have to use a text editor like nano, pico, or vim.
```bash
$ touch hello
$ vim hello
```
Heres what you to type into the hello file
```bash
#!/bin/bash
echo 'HelloWorld!'
```
Exit the file, now you have to edit the permissions for the hello file. I don't know much about this, for more infor checkout `man chmod`, this is a very powerful command to be knowledgable of.
Heres what todo...
```bash
chmod 777 hello
```
Now run the command
```bash
./hello
```
