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
