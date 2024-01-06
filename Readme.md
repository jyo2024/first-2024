# Linux

Linux:  
Linux version is ubuntu or debian
OS:
memory management
manging multi tasking
		multiple users
process management
device
error handling and logging

For testing purpose we are using centOs

linux is opensource os
Redhat enterprise linux server redhat8.4 or 8.5
centos is testing os
centos using for product os

Architecure:
hardware
kernel : talk to hardware
shell : check the user is typing explain to kernel
what is command it is a pice of code return in a file

we will not give executable 
will will give the ource code

ls -l

permissions and ownership are the level1 security
ls -l
ls -ld

of we want to change the localhost ise nmtui
bash
touch we wil creat efile

Linux directories:
/usr
/etc
/var
/run
/home
/root
/tmp
/boot
/dev

uname -a
it shows the kernel 

If we want to add user
useradd

grep:
we can find string by using this

grep -i  it returns for case intesitive strings
grep -n matching strings along withtheir line number
grep -v results lines not matching 	the search string
grep -c lines inwhich the result matches searh string
grep -o  donot comletd the line show wherever ot is\

cp -r dir1 /tmp
it will copy the all directories

ls -lh
we will human readable so will use this command

alias lh= 'ls -ltrh'
lh

alias
when we enter above command alias we will get all the details

ls --help


/usr/bin/ls
/usr/bin/ls --color=auto

$:
If we want to know the variable we will use $PATH i.e ., $PATH
we want assign value to varible use PATH   PATH

bash(shell will try to find the location of ls command using info saved in $PATH)
bash will read the command file
translate to kernel
kernel will talk to hardware to get the output


kernel will be the bridge between hardware and os

.file1 is called hidden file
mv .file1 file

env
we will see the environmental variables

su - rohit
we will see the env variables

Vi editor:
we can count the lines by using wc -l file2

if we want to connect from windows to linux use xrdp

useradd abcd
id abcd
passwd bcd


When we are adding without root password it will ask the 8 characters short likethat
thats why we will add in root user

which useradd
userdel -r abcd
usermod -G wheel ancd

grep mohit /etc/passwd
passwd mohit

chage command can be used to congigure and view pasword expiration setting for users
chage -l mohit    #password aging list details
chage mohit   # we want to change the details

permissions:
- normal/regular file
d directory
c character file
b block file
l link or shortcut


users  groupowner  others
r       w       x		rwx
4		2		1		7

owner    groupowner    others   all
u 			g 			o 		a 

grep staff /etc/group
vi /etc/group
cat /etc/passwd

Change permissions:
chmod u=rwx, g=---, o=---- testdir1
chmod ugo filename
chmod 700 testdir1
chmod 644 
chmod 750

Change Ownership:
chown student:staff testdir1

ps:
all running process can be tracked

disk space:df

chmod +x ourfile.tf
chmod 755 ourfile.tf

chmod +x *  
ececute all


https://efds.fa.em5.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/my-profile











