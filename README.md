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
