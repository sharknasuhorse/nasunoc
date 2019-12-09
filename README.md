# nasunoc


## noc

### docker-compose

- nginx
    - https proxy

- zabbix
    - snmp trap

- grafana
    - zabbix dash

- kibana
    - elastiflow dash

- elasticsearch
    - elastiflow
    - syslog

- logstash
    - elastiflow
    - syslog

- unbound
    - internal record

- influxdb
    - telegraf db

### host
- telegraf
- zabbix-agent


## usage

```
mkdir volumes
chmod 777 volumes/elastiflow_es
chmod 777 volumes/grafana
```


if use ubuntu 18
```
sudo systemctl stop systemd-resolved
sudo systemctl disalbe systemd-resolved
```



self sign
```
mkdir nginx/ssl-key
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ./nginx/ssl-key/nginx-selfsigned.key -out ./nginx/ssl-key/nginx-selfsigned.crt
```


