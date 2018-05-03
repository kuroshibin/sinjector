SInjector v.2.3

#Fitur Repaired: detect local ip address (experimentation)

# *. First hp python interpreter must be installed and should be able to run its py file from TE
# *. Author wear python 2.7

Extract all files into one folder.
Extract to folder: / sdcard / si /

then run its TE
type: cd / sdcard / si /
si.py file run it:
python si.py [enter]

Payload Support Keyword:
[Raw], [crlf], [lfcr], [host_port], [host] [port], [protocol], [ssh], [realData], [netData], [cr] [lf], [ua ], [split], [crlf * n]

#Special Payload keyword: [crlf * n]: replace n with a number, for example: [crlf * 2] then later will be: \ r \ n \ r \ n or [crlf] [crlf]

#note: New Payload Keyword: [ua]
# to change the user agent, please edit the file ua.ini

Future #new Added: 0
#Bug Fixed:
#menampilkan ip address (FIX), disable debugging, auto replace 200 (by confirmation)

How to create a payload:
create a new file, and write like this:

eg file named: payload.ini:
remote port
payload

then save ..
remote replace with a remote server, replace port with the port, and write with payloadnya payload.

Example:
10.19.19.19 8080
[Raw] Connection: Keep-Alive [crlf] [crlf]

save, and run his si.py, if already completed ..
went straight to ssh tunnel and set like this:

Host section type the host name/ip of ssh
type the port section 443 or 22
section type the user account's username of ssh
password section type the account password of ssh
Use Sock Proxy section unchecked 
local port may be changed or leave it alone
auto connect tick when needed
auto reconnect also check if necessary
Enable GFW List jgn let it go unchecked
Global Proxy tick (root)
Enable Upstream Proxy unchecked
then input the address: 127.0.0.1:9000
9000 figures replace the existing port numbers in server / is displayed in the terminal
when confused, for example in the terminal to perform: Listening 127.0.0.1:8000
nah, 8000 it was the port :)
for example DNS other reply is checked on no nothing
Direct ok just click Tunnel Switch and wait for it to be connected ...
if already connected means you've successfully used: D

or through Ki4a:
open application Ki4a
click the settings icon in the top right corner
edit address with its host ssh
edit its port with ssh port (eg: 443)
edit ssh username with the user name his
edit his password with ssh
Enable HTTP Proxy enabled
the contents of the address to 127.0.0.1
fill port to port (eg 9000)
use iptables enabled
others leave it blank
then back icon and click the red button
wait until connected (later there was a notice: connected)

# Cheers ~

# FA2AS_Facebook_Group
#Author: Redfox