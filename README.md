# Linux
Linux Upskill Challenge

Day 1

Connect and login to your server, preferably using a SSH client
ssh user@<ip address>

Run a few simple commands to check the status of your server

"general info"
lsb_release -a
cat /etc/os-release
uname -a
uptime
whoami
who
w
"hardware info"
lshw
lscpu
lsblk
lspci
lsusb
"memory and cpu usage"
free -h
vmstat
"disk usage"
df -h
du -h
"network usage"
ifconfig
ipaddress
netstat "static"
ifstat "continuous
sudo ifstat -i eth0


Day 2

print working directory
change directory
~ - ..
~ honme
- back to the point before
.. back to the previous directory

environment variables
printenv
$HOME
$PWD
$OLDPWD
$USER

list files
ls

-l as a list
-lh as a human readable list
-a list with hidden files

customize prompt
export PS1="\$"

creating file and directories

mkdir <name>
touch <name>
mv <name> <name>
cp <name>
rm <name>
rmdir <name> (only empty directory)

rtfm 
man cp
apropos <name>
tldr

Day 3
3 types of users
root
sudoers
normal

changing passwords
visudo
passwd

change hostname
hostnamectl set-hostname
preserve_hostname: true

change timezone
sudo timedatectl list-timezones
sudo timedatectl set-timezone <timezone>

Day 4

installing software
apt search "midnight commander"
sudo apt install mc
