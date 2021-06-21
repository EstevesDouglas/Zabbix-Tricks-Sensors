# Procedimento manuais para instalação do do Agent Zabbix no Raspberry PI

```
$ wget https://repo.zabbix.com/zabbix/4.4/raspbian/pool/main/z/zabbix-release/zabbix-release_4.4-1+buster_all.deb

```


```
$ dpkg -i zabbix-release_4.4-1+buster_all.deb
```

```
$ apt update
```

```
$ apt-get install zabbix-agent
```

```
$ vim /etc/zabbix/zabbix_agentd.conf
```

```
$ systemctl enable zabbix-agent
```

```
$ systemctl restart zabbix-agent
```


# Data
28/07/2020 - Criação da documentação com os passos

[Site ZABBIX - Instalação[1]](https://www.zabbix.com/download?zabbix=5.0&os_distribution=raspbian&os_version=10_buster&db=mysql&ws=apache)