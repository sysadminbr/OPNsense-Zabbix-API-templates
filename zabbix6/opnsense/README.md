# Zabbix Template for OPNsense leveraging it's API  

Easy to use:  
- import this template into zabbix  
- in opnsense web GUI access System/Access/User  
- create a new user (no admin rights needed)  
- click + to generate a KEY file  
- associate this template to a zabbix host
- set the following macros:
```
{$APIKEY}    : key from the downloaded file
{$APISECRET} : secret from the downloaded file
{$BASEURL}   : firewall url like https://127.0.0.1:8443 - no leading '/'
```


changelog:  
2024-02-15: updated template to leverate the api.  
2024-03-10: no more dependency on legacy plugin from rbicelli to pfsense.   


Remember: Open Source is free as in speech, not as in beer.


