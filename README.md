# Frankencoding

<img alt="https://twitter.com/hughcards/status/423952995240648704" src="https://pbs.twimg.com/media/Bq8s4gsCAAAdr18.jpg" width="256">

You're busted! -  and just with Bubble Gum And Baling Wire... ok and some Duct Tape is also used. 

### About

This repository houses a list of open-source tools, libraries, projects, etc that can be used to build awesome security stacks.

### Contents

## Packet capture and intrusion detection

* [Suricata IDS](https://github.com/OISF/suricata) - Suricata is a network IDS, IPS and NSM engine.
  * [Documentation](https://suricata-update.readthedocs.io/en/latest/)
  * [CCDCOE course materials](https://github.com/ccdcoe/CDMCS/tree/master/Suricata)
  * [Suricata update](https://suricata-update.readthedocs.io/en/latest/)
  * [Detect newly created TLS certificates](https://gist.github.com/markuskont/87e545c8b82fa00caf091ed6a2fedc8f)
* [Moloch](https://github.com/aol/moloch) - Moloch is an open source, large scale, full packet capturing, indexing, and database system.
  * [Wiki](https://github.com/aol/moloch/wiki) *deprecated*
  * [Official documentation](https://molo.ch/learn)
  * [API endpoints](https://molo.ch/api)
  * [CCDCOE course materials](https://github.com/ccdcoe/CDMCS/tree/master/Moloch), [example WISE plugin](https://github.com/markuskont/moloch/blob/custom/wisePlugins/wiseService/source.ls19.js), [writing a wise plugin](https://github.com/ccdcoe/CDMCS/tree/master/Moloch/wise#writing-a-wise-plugin)
* [Zeek](https://github.com/zeek/zeek) - Zeek is a powerful network analysis framework that is much different from the typical IDS you may know. 
  * [Documentation](https://www.zeek.org/documentation/index.html)
  * [Scripts for detecting cobal strike](https://github.com/ccdcoe/zeeky)

## Logging

### Sources

* [Snoopy is a tiny library that logs all executed commands + arguments on your system.](https://github.com/a2o/snoopy)

### Collecting and shipping

* [RSYSLOG is the rocket-fast system for log processing.](https://github.com/rsyslog/rsyslog)
* [With syslog-ng, you can collect logs from any source, process them in near real-time and deliver them to a wide variety of destinations](https://www.balabit.com/documents/syslog-ng-ose-latest-guides/en/syslog-ng-ose-guide-admin/html/index.html)

### Correlation

* [SEC is an event correlation tool for event log monitoring, network and security management](https://simple-evcorr.github.io/)

## Databases

### Graph
* [Neo4j is the Graph Database.](https://github.com/neo4j/neo4j)

### NoSQL

* [Elasticsearch - A Distributed RESTful Search Engine](https://github.com/elastic/elasticsearch)
* [InfluxDB is scalable datastore for metrics, events, and real-time analytics](https://github.com/influxdata/influxdb)

## Web interfaces and API-s

### Alerts

* [Scirius is a web application for Suricata ruleset management.](https://github.com/StamusNetworks/scirius)
* [Web Based Event Viewer (GUI) for Suricata EVE Events in Elastic Search](https://github.com/jasonish/evebox)
* [The alerta monitoring system is a tool used to consolidate and de-duplicate alerts from multiple sources for quick ‘at-a-glance’ visualisation. ](https://github.com/guardian/alerta)

### Generic Viz

* [Kibana is a data visualization and query interface for Elasticsearch.](https://github.com/elastic/kibana)
* [Grafana - Gorgeous metric viz, dashboards & editors](https://github.com/grafana/grafana)

## Programming languages

### Libraries

* [py-idstools is a collection of Python libraries for working with IDS systems](https://github.com/jasonish/py-idstools)

## Data science

* [LogCluster is an experimental Perl-based tool for log file clustering and mining line patterns from log files](https://github.com/ristov/ristov.github.io/tree/master/logcluster)
* [scikit-learn: machine learning in Python](https://github.com/scikit-learn/scikit-learn)
* [TensorFlow is an open source software library for numerical computation using data flow graphs.](https://github.com/tensorflow/tensorflow)
* [Ngraph is a set of graph related algorithms.](https://github.com/anvaka/ngraph)
* [ngraph.pixel is fast graph renderer based on low level ShaderMaterial from three.js](https://github.com/anvaka/ngraph.pixel)
* [Cayley is an open-source graph to be a part of the developer's toolbox](https://github.com/cayleygraph/cayley)

## Message queue and data pipelining
* [Heka is a tool for collecting and collating data from a number of different sources, performing "in-flight" processing of collected data, and delivering the results to any number of destinations for further analysis.](https://github.com/mozilla-services/heka/)
* [Hindsight is lighter weight and faster data pipeline with delivery guarantees to replace Heka](https://github.com/mozilla-services/hindsight)
* [The nanomsg library is a simple high-performance implementation of several "scalability protocols". ](https://github.com/nanomsg/nanomsg)
* [package mangos is an implementation in pure Go of the SP ("Scalable Protocols") protocols.](https://github.com/go-mangos/mangos)
* [Kapacitor is a framework for processing, monitoring, and alerting on time series data](https://github.com/influxdata/kapacitor)

## Threat intel
* [MISP is Malware Information Sharing Platform and Threat Sharing.](https://github.com/MISP/MISP)

## Metrics and alerting
* [Telegraf is an plugin-driven agent for collecting & reporting metrics.](https://github.com/influxdata/telegraf)

## Reading materials

* [Left-Leaning Red-Black Trees Considered Harmful](http://www.read.seas.harvard.edu/~kohler/notes/llrb.html)
* [Stratosphere IPS. Generation of the Behavioral Models](https://stratosphereips.org/stratosphere-ips-generation-of-the-behavioral-models.html)
* ...

----

[<img alt="https://random-blather.com/2014/04/28/information-isnt-power/" src="https://randomblatherdotcom.files.wordpress.com/2014/04/bmust7rcuaa6ueo-jpg-large.jpeg" width="512">](Data2Info2Knowledge.md)

## see also

* [Cyber Defence Monitoring Course Suite](https://github.com/ccdcoe/CDMCS)
* [Technical Courses](https://ccdcoe.org/event/technical-courses.html)
* [Cyber Defence Exercises](https://ccdcoe.org/event/cyber-defence-exercises.html)
