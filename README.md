# zabbix-docker
Simple setup (All in one)

1) Git clone repo


2) Run from the project folder
```
docker compose -f zabbix.yml up --build -d
```

The configuration will launch a ready-made zabbix project with pgsql timecaledb
