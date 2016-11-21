# Data flow

```
host -[metrix]-> influxdb
host -[(sys)log]-> rsyslog
switch -[rspan]-> tcpdump
router -[netflow]-> nfcapd

```
