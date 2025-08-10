# zabbix-templates
Zabbix Custom Templates from https://github.com/sysadminbr/zabbix-templates

Templates for monitoring opnSense by api

## set macros
 - {$APIKEY} System: Access: Users: Api key
 - {$APISECRET} System: Access: Users: Api secret
 - {$BASEURL} Full url like https://my.opnsense.com

 - {$FIREWALL.CHANGE.THRESHOLD} default is 50 (percent), used by trigger which notifies if significant change

 make sure that the user has to right diagnostic permissions on opnSense 
 
