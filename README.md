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

### Libraries
* [py-idstools](https://github.com/jasonish/py-idstools) - idstools: Snort and Suricata Rule and Event Utilities in Python (Including a Rule Update Tool) 
* [Go NIDS](https://github.com/google/gonids) - gonids is a library to parse IDS rules, with a focus primarily on Suricata rule compatibility.
* [Gopacket](https://github.com/google/gopacket) - Provides packet processing capabilities for Go 

## Logging

### Sources

* [Snoopy](https://github.com/a2o/snoopy) - Log every executed command to syslog (a.k.a. Snoopy Logger).
  * [Improve logging format](https://github.com/ccdcoe/frankenstack/blob/master/states/blue/snoopy/config/config.ini), [normalize snoopy messages using liblognorm](https://github.com/ccdcoe/frankenstack/blob/master/states/yellow/logserver/config-rsyslog/snoopy.rulebase)
* [Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) - Make Windows logging great again
  * [SwiftOnSecurity configs](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing 
  * [Sysmon modular](https://github.com/olafhartong/sysmon-modular) - A repository of sysmon configuration modules

### Collecting, shipping, stream processing

* [Rsyslog](https://github.com/rsyslog/rsyslog) - RSYSLOG is the rocket-fast system for log processing.
  * [Documentation](https://rsyslog.readthedocs.io/en/latest/index.html)
  * [liblognorm](https://github.com/rsyslog/liblognorm) - A fast samples-based log normalization library. 
* [Syslog-ng](https://github.com/syslog-ng/syslog-ng) - free and open-source implementation of the syslog protocol for Unix and Unix-like systems.
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

* [Scirius](https://github.com/StamusNetworks/scirius) - Scirius is a web application for Suricata ruleset management.
  * [scirius-docker](https://github.com/StamusNetworks/scirius-docker)
* [Evebox](https://github.com/jasonish/evebox) - Web Based Event Viewer (GUI) for Suricata EVE Events in Elastic Search
* [Alerta](https://github.com/alerta/alerta) - Alerta monitoring system
  * [Alerta web UI](https://github.com/alerta/alerta-webui) - Alerta Web UI 7.0

### Generic Viz

* [Kibana](https://github.com/elastic/kibana) - Your window into the Elastic Stack
* [Grafana](https://github.com/grafana/grafana) - The tool for beautiful monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More

## Programming languages and dev tools

* [Rust](https://rustup.rs/) - Rust’s rich type system and ownership model guarantee memory-safety and thread-safety — and enable you to eliminate many classes of bugs at compile-time. 
  * [Learn](https://doc.rust-lang.org/book/index.html)
  * [Dark arts](https://doc.rust-lang.org/nomicon/)
* [Golang](https://golang.org/) - Go is an open source programming language that makes it easy to build simple, reliable, and efficient software. 
  * [Learn](https://learn.go.dev/)
* [Julia](https://julialang.org/) - Julia is a high-level, high-performance dynamic language for technical computing. 
* [R](https://www.r-project.org/) - R is a free software environment for statistical computing and graphics.
  * [nvim-r](https://github.com/jalvesaq/Nvim-R) - Vim plugin to work with R 

### Editors

* [neovim](https://github.com/neovim/neovim) - Vim-fork focused on extensibility and usability
  * [Conquer of Completion](https://github.com/neoclide/coc.nvim) - Intellisense engine for vim8 & neovim, full language server protocol support as VSCode 
    * [coc-rls](https://github.com/neoclide/coc-rls) - Rust language server support for coc.nvim 
    * [coc-python](https://github.com/neoclide/coc-python) - Python extension for coc.nvim
  * [plug](https://github.com/junegunn/vim-plug) - Minimalist Vim Plugin Manager 
  * [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim
* [vscode](https://github.com/microsoft/vscode) - Visual Studio Code is a streamlined code editor with support for development operations like debugging, task running, and version control.
* [juno](https://github.com/JunoLab) - Juno is a powerful, free environment for the Julia language. 
* [Jupyter lab](https://github.com/jupyterlab/jupyterlab) - An extensible environment for interactive and reproducible computing, based on the Jupyter Notebook and Architecture. 
  * [IJulia](https://github.com/JuliaLang/IJulia.jl) - IJulia is a Julia-language backend combined with the Jupyter interactive environment (also used by IPython).
  * [gophernotes](https://github.com/gopherdata/gophernotes) - The Go kernel for Jupyter notebooks and nteract. 

### Libraries

* [Pandas](https://pandas.pydata.org/pandas-docs/stable/) - powerful Python data analysis toolkit
* [matplotlob](https://github.com/matplotlib/matplotlib) - plotting with Python

## Data science

### Tools

* [LogCluster](https://github.com/ristov/ristov.github.io/tree/master/logcluster) - experimental Perl-based tool for log file clustering and mining line patterns from log files

### Libraries

* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - machine learning in Python
* [TensorFlow](https://github.com/tensorflow/tensorflow) - An Open Source Machine Learning Framework for Everyone
  * [TensorFlow-Examples](https://github.com/aymericdamien/TensorFlow-Examples) - TensorFlow Tutorial and Examples for Beginners (support TF v1 & v2)
* [Ngraph](https://github.com/anvaka/ngraph) - a set of graph related algorithms.
  * [ngraph.pixel](https://github.com/anvaka/ngraph.pixel) - fast graph renderer based on low level ShaderMaterial from three.js
* [Cayley](https://github.com/cayleygraph/cayley) - an open-source graph to be a part of the developer's toolbox

## Message queue and data pipelining

* [Heka](https://github.com/mozilla-services/heka/) - Heka is a tool for collecting and collating data from a number of different sources, performing "in-flight" processing of collected data, and delivering the results to any number of destinations for further analysis.
* [Hindsight](https://github.com/mozilla-services/hindsight) - Hindsight is lighter weight and faster data pipeline with delivery guarantees to replace Heka.
* [nanomsg](https://github.com/nanomsg/nanomsg) - The nanomsg library is a simple high-performance implementation of several "scalability protocols". 
* [mangos](https://github.com/go-mangos/mangos) - Package mangos is an implementation in pure Go of the SP ("Scalable Protocols") protocols.
* [Kapacitor](https://github.com/influxdata/kapacitor) - Framework for processing, monitoring, and alerting on time series data.
* [Kafka](https://github.com/apache/kafka) - A distributed streaming platform.
* [Apache Pulsar](https://github.com/apache/pulsar) - Distributed pub-sub messaging system.

## Hunting

### Intelligence platforms

* [Malware Information Sharing Platform and Threat Sharing (MISP)](https://github.com/MISP/MISP) - Open Source Threat Intelligence and Sharing Platform
* [Semi-Automated Cyber Threat Intelligence - ACT](https://github.com/mnemonic-no/act) - The main objective of the ACT project is to develop a platform for cyber threat intelligence to uncover cyber attacks, cyber espionage and sabotage. 
* [MITRE ATT&CK](https://mitre-attack.github.io/attack-navigator/enterprise/) -  Globally-accessible knowledge base of adversary tactics and techniques based on real-world observations.

### Playbooks

* [Threat hunters playbook](https://github.com/hunters-forge/ThreatHunter-Playbook) - A Threat hunter's playbook to aid the development of techniques and hypothesis for hunting campaigns.

## Metrics and alerting

* [Telegraf](https://github.com/influxdata/telegraf) - Telegraf is an plugin-driven agent for collecting & reporting metrics.

## Reading materials

----

[<img alt="https://random-blather.com/2014/04/28/information-isnt-power/" src="https://randomblatherdotcom.files.wordpress.com/2014/04/bmust7rcuaa6ueo-jpg-large.jpeg" width="512">](Data2Info2Knowledge.md)

## see also

* [Cyber Defence Monitoring Course Suite](https://github.com/ccdcoe/CDMCS)
* [Technical Courses](https://ccdcoe.org/event/technical-courses.html)
* [Cyber Defence Exercises](https://ccdcoe.org/event/cyber-defence-exercises.html)
