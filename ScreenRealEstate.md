# Screen real estate

* 4 x HD
* 1 x 'average' projector

```

alerta -[alert]-> projector(custom_viz)

kapacitor -[warnings]-> HD(alerta)
influx -[metrix]->HD(grafana)
suricata -[ids alerts]-> HD(evebox?)
.. -[]-> HD(..?)

```
