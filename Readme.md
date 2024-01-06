#Pre-requistes:
https://www.youtube.com/watch?v=Wvf0mBNGjXY


#Networking:
https://www.youtube.com/watch?v=0uflG0SemyM

Networking tier1 companies:
atst
level3
sprint
comcast
telstra
tata
sintel
ntt

submarine cables


layers:
TCP/IP layers:
application : the software which interact one human to another works in app layer
http/https (access website) smtp/pop/imap(send email or receive email)  ftp(file transfer) telnet/ssh(access router in usa)

presentation: format of data, encryption and decryption

session layer is timeframe high lrvrl dats

transport layer :
convrt thrdatsb 
•	Experience in designing and implementation of continuous integration, continuous delivery, continuous deployments through Jenkins.
 create and maintsin 
transport: 
network
data link
physical

switch is store the mac address initially it will do the broadcast and next it will do the unicast
hub is not store the data its a broadcast signals

bridge is known as switch
less no of ports

router:
it is a network device which is used to connect different networks each other
ASR
ISR (integrated serbice router)
csr (casrre desggregation router)
used by service providers

Application: software.apps
presentation: format od data
session: create and maiantain timeframes

transport:
retransmission, segmentation, sequenving  TCP

TCP vs UDP
Reliable, retransmit, connection oriented, 

from data-> transport segments port number
            network layer routers
			psckets ip
packets sourceip/destination ip -> datalink layer switches
             frmae sorcemac and destination mac
physical layer encoding
all process is called encapsulation

application human intercation software apps
presentaion format of data
session crating maintaing session
trsnport segments port number d
network pacekt ip
datalink frame mac addresses	
physical encoding
encapsulation


subnetting: to summerixe
it represents the network bits
divide network into smaller parts

class A:n.h.h.h
 8.8.8.8= 2 power of 24= 2 poer of 34 sddresses
 B:
 N.N.H.H
 2 power of 16
 C:N.H.H.H.H 2 poer of 8 =256 addresses
 
 network bits always remains same
 
 Private Ips:
 These all are completely free
 10.0.0.0     10.255.255.255
 172.16.0.0    172.16.255.255
 192.168.0.0    192.168.255.255
 
 Ststic ip is access anytging from internet it is public ip 
 
 Examples:
 200.1.1.0/24   it is 32 bits
 inthis netwrok bits are 24 and host are 8 bits so total 256
 N.N.N.H
 If we want to devide into 4 locations
 24            8
 +2			  -2
 26 		   6 
 
 in 4 locations we have to start from 0 to 255
 
 gateway:
 exit point of lan is gateway
 router:
 to connect different networks
 
 port forwarding:
 Allows computer over the internet to connect a specifc computer or service within a private network
 
 forward proxy:
 the all the goto proxy servers and then going to internet and coming bak aslo proxy is mediator and the signls into a servers
 reverse proxy:
 it regulates traffic coming into a network
 
 VPN:
 virtual private network allows on computer networks allows each other securely over the internet
 when hackers are inthat vpns are drop in connection and recreate it
 
 



# Linux
https://www.youtube.com/watch?v=V1y-mbWM3B8
https://www.youtube.com/watch?v=8usykf7J30g
https://www.youtube.com/watch?v=ROjZy1WbCIA

Linux:  

****echo $PATH
echo $USER
unset value remove the variable permanently
unset NEWVARIABLE
top
ps ux ps PID
Kill PID
df
pdiof firefox (eg)**

The lower the niceness index the higher would be the priority given to the task




For eg:
sudo apt install mail
after that
mail abc@gmail.com
pr -x
pr -h
pr -n
lp -nc

**

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











