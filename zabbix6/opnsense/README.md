Opnsense zabbix template based on API

Easy to use:
import a template in zabbix
in opnsense web GUI: system/Access/user
select your active admin user
click + to generate a KEY file

import a template in a host
set this macro:
{$APIKEY}  : key in a download file
{$APISECRET}   : secrete in a download file
{$BASEURL}    : firewall url like http://127.0.0.1:8443

BUG: 

TO DO:


changelog:
2024-02-15: Template atualizado e implementado o monitoramento via API do OPNSense.
2024-03-10: repositório novo sem herdar código legado do rbicelli.


