### Troubleshooting

#### Диски

du  
df  
smartctl  
/proc/mdstat  

#### Процессор и память

iostat  
iotop  
top  
atop  
vmstat  
free  
/proc/meminfo  

#### Процессы  

ps -efl | -aux  
strace  
systemctl status nginx  
kill -9 pid  

#### Сеть  

netstat | ss  
ip a | ifconfig  
netstat -rm | route | ip r  
ping  
traceroute  
mtr  
dig  
nslookup  
curl  
curl telnet  
tcpdump  

#### Логи  

/var/log  
/var/log/syslog  
dmesg  
journalctl  