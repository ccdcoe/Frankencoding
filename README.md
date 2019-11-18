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

* [Snoopy](https://github.com/a2o/snoopy) - Log every executed command to syslog (a.k.a. Snoopy Logger).
  * [Improve logging format](https://github.com/ccdcoe/frankenstack/blob/master/states/blue/snoopy/config/config.ini), [normalize snoopy messages using liblognorm](https://github.com/ccdcoe/frankenstack/blob/master/states/yellow/logserver/config-rsyslog/snoopy.rulebase)
* [Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) - Make Windows logging great again
  * [SwiftOnSecurity configs](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing 
  * [Olaf Hartong configs](https://github.com/olafhartong/sysmon-configs) - Enhanced sysmon configs with MITRE ID-s

### Collecting, shipping, stream processing

* [Rsyslog](https://github.com/rsyslog/rsyslog) - https://github.com/rsyslog/rsyslog
  * [Documentation](https://rsyslog.readthedocs.io/en/latest/index.html)
  * [liblognorm](https://github.com/rsyslog/liblognorm) - A fast samples-based log normalization library. 
* [Syslog-ng](https://github.com/syslog-ng/syslog-ng)
* [Fever](https://github.com/DCSO/fever) - fast, extensible, versatile event router for Suricata's EVE-JSON format 

### Correlation

* [Simple Event Correlator](https://github.com/simple-evcorr/sec) - SEC is an event correlation tool for advanced event processing.

## Databases

### Search engines

* [Visibility Across Space and Time (VAST)](https://github.com/tenzir/vast) - is a scalable foundation for a security operations center (SOC): a rich data model for security data, high-throughput ingestion of telemetry, low-latency search, and flexible export in various formats.

### Graph
* [Neo4j](https://github.com/neo4j/neo4j) - Neo4j is the world’s leading Graph Database.

### SQL

* [SQLite](https://github.com/sqlite/sqlite) - SQLite is a relational database management system contained in a C library. In contrast to many other database management systems, SQLite is not a client–server database engine. Rather, it is embedded into the end program.
* [MariaDB](https://github.com/MariaDB/server) - MariaDB server is a community developed fork of MySQL server. 
* [CockroachDB](https://github.com/cockroachdb/cockroach) - the open source, cloud-native SQL database. 

### NoSQL

* [Cassandra](https://github.com/apache/cassandra) - Apache Cassandra is a highly-scalable partitioned row store.
* [Elasticsearch](https://github.com/elastic/elasticsearch) - Open Source, Distributed, RESTful Search Engine.
  * [Install elastic with docker](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html)
* [InfluxDB](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [Prometheus](https://github.com/prometheus/prometheus) - The Prometheus monitoring system and time series database. 

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
