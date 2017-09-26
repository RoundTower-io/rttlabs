SNOW Demo Config
=========
Info on the vRA/SNOW integration demo  
# Snow Config
### MID Server
dlab-snowmid-01.rtt.lab  
10.200.254.130  

MID Server Name: dlabmid  
SNOW Instance: https://dev40987.service-now.com  
SNOW username: mid-integrate  
SNOW password: VMware1!

### SNOW LDAP
Server: dc-rttlab-01.rtt.lab  

Login distinguished name: svc_snow  
Login password: ThisIsSn0w!  
Starting search directory: dc=rtt,dc=lab  
MID Server: dlabmid

### vRA Plugin Basic Config
MIDServer Name: dlabmid  
Hostname: https://dlab-vra-01.rtt.lab  
Tenant Name: vsphere.local  
Integration User Username: snowadmin@vsphere.local  
Password: (...........)  

Client integration username: snowadmin  
Client integration password: (...........)  
Client ID: snowadmin-client  
Client Secret: intpassword  
