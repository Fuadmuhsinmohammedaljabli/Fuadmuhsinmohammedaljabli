    NET.py
import  socket
import  sys
 print ('ENTER YOUR DNS OR TARGET:')
 hostname=input()
 ip=socket.gethostbyname(hostname)
 print ('host name is :',hostname ,'\n' 'Target ip is:',ip)
