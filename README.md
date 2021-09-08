# Awesome Q [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/StephenTaylor-Kx/awesome-q)

A curated list of awesome q frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).


Repositories at [KxSystems](https://github.com/KxSystems) are maintained and supported by KX. Other repositories are maintained by their owners.

## :fireworks: Fusion interfaces

The [Fusion interface libraries](https://code.kx.com/q/interfaces/fusion/) are maintained and supported by KX.

to     | source | note
-------|--------|-----
Arrow<br>Parquet | [arrowkdb](https://github.com/KxSystems/arrowkdb) | [Using Apache Arrow/Parquet data with kdb+](https://code.kx.com/q/interfaces/arrow/)
FFI | [ffi](https://github.com/kxsystems/ffi) | [Use foreign functions in q](https://code.kx.com/q/interfaces/ffi/)
HDF5 | [hdf5](https://github.com/KxSystems/hdf5) | [Hierarchical Data Format 5](https://code.kx.com/q/interfaces/hdf5/)
Java | [javakdb](https://github.com/KxSystems/javakdb) | [Java client for kdb+](https://code.kx.com/q/interfaces/java-client-for-q/)
Jupyter | [jupyterq](https://github.com/kxsystems/jupyterq) | [Jupyter kernel for kdb+](https://code.kx.com/q/ml/jupyterq/)
Kafka | [kafka](https://github.com/KxSystems/kafka) | q client for [Apache Kafka](https://kafka.apache.org)
LDAP | [ldap](https://github.com/KxSystems/ldap) | [Solace pub/sub brokers](https://code.kx.com/q/interfaces/ldap/)
MQTT | [mqtt](https://github.com/KxSystems/mqtt) | [Message Queuing Telemetry Transport](https://code.kx.com/q/interfaces/mqtt/)
Prometheus | [prometheus-kdb-exporter](https://github.com/KxSystems/prometheus-kdb-exporter) | [Expose metrics to Prometheus](https://code.kx.com/q/interfaces/prom/exporter/)
Protocol Buffers | [protobuf](https://github.com/KxSystems/protobufkdb) | [Protobuf](https://code.kx.com/q/interfaces/protobuf/)
Python | [embedPy](https://github.com/KxSystems/embedPy) | [call Python from q](https://code.kx.com/q/ml/embedpy/)
Python | [pyq](https://github.com/KxSystems/pyq) | [call Python from q](https://code.kx.com/q/interfaces/pyq/)
R | [rkdb](https://github.com/KxSystems/rkdb) | [R client for q](https://code.kx.com/q/interfaces/r/)
Reuters | [kdb/c](https://github.com/KxSystems/kdb/blob/master/c/feed/rfa.zip)
Solace | [solace](https://github.com/KxSystems/solace) | [Solace pub/sub brokers](https://code.kx.com/q/interfaces/solace/)


## Other interfaces 

to     | source | note
-------|--------|-----
C | | [C client for kdb+](https://code.kx.com/q/interfaces/c-client-for-q/)
Excel | [excelrtd](https://github.com/CharlesSkelton/excelrtd) | [Microsoft Excel™ client for kdb+](https://code.kx.com/q/interfaces/excel-client-for-q/)
Java | [jshow](https://github.com/CharlesSkelton/jshow) 
JavaScript | | [WebSockets](https://code.kx.com/q/kb/websockets/)
JDBC | [babel](https://github.com/CharlesSkelton/babel) | query other databases via JDBC
Lua | [qlua](https://github.com/geocar/qlua) | q client for Lua
Mathematica | [KxSystems/kdb](https://github.com/KxSystems/kdb/blob/master/c/other/qmathematica.txt) | Mathematica5 -> Q interface
ODBC |  | [ODBC](https://code.kx.com/q/interfaces/q-client-for-odbc/)
NaCL | [qsalt](https://github.com/geocar/qsalt) | NaCL bindings for q/kdb
NodeJS | [qnode](https://github.com/geocar/qnode) | kdb+ client in NodeJS
ODBC | | [kdb+ server for ODBC3](https://code.kx.com/q/interfaces/q-server-for-odbc3/)
PHP | [qphp](https://github.com/geocar/qphp) | kdb+ IPC implementation for PHP


## Editor integrations

editor | source | note
-------|--------|-----
Emacs  | [kq-mode](https://github.com/geocar/kq-mode) | q major mode for emacs; supports tramp and babel
Emacs  | [q-mode](https://github.com/psaris/q-mode) | major mode for editing q
Evolved  | [Syntaxhighlighter-for-q](https://github.com/simongarland/Syntaxhighlighter-for-q)
TextMate  | [KX.tmbundle](https://github.com/psaris/KX.tmbundle) | q language support for TextMate 2
vim  | [vim](https://github.com/simongarland/vim) | vim support for q
WordPress  | [Syntaxhighlighter-for-q](https://github.com/simongarland/Syntaxhighlighter-for-q)


## Frameworks

* [kdb-taq](https://github.com/KxSystems/kdb-taq) – Process trade-and-quote data
* [kdb-tick](https://github.com/KxSystems/kdb-tick) – [tickerplant](kb/kdb-tick.md)


## Cloud deployment

KX Insights provides tools for deploying kdb+ systems in the cloud.

* [kdb+ Cloud Edition](https://code.kx.com/insights/cloud-edition/): 
    * packaging
    * orchestration
    * REST interfaces
    * logging
    * object storage
    * Google BigQuery
* [Microservices](https://code.kx.com/insights/microservices/): an ecosystem of cloud-native microservices, built with kdb+ Cloud Edition, all with OpenAPI specifications
    * service discovery
    * data access
    * service gateway
    * storage manager
    * stream processor
    * dashboards


## Developer tools

* [dpy](https://github.com/LeslieGoldsmith/dpy) – General object display with type and structure
* [help](https://github.com/KxSystems/help) – Online help for q
* [kdb](https://github.com/KxSystems/kdb) – Companion files to the kdb+ product
* [man](https://github.com/KxSystems/man) – [man-style reference](https://code.kx.com/q/about/man.md) 
* [qprof](https://github.com/LeslieGoldsmith/qprof) – Code profiler 
* [studio](https://github.com/CharlesSkelton/studio) – A rapid-development environment for q
* [ws](https://github.com/LeslieGoldsmith/ws) – Workspace utilities


## Miscellaneous
<!-- Divide as it grows -->

* [amcharts](https://github.com/kxcontrib/cburke/tree/master/amcharts/) – A set of flash charts designed for Web applications
* [hypertree](https://github.com/stevanapter/hypertree) – Recursive aggregating treetable and 3-D pivot table for hypergrid
* [Kdb+stuff](https://github.com/MdSalih/Kdb-stuff) – ServerChecker: how to execute commands on a remote box via SSH from within a q process and parse Linux system info (cpuinfo/meminfo/df)
* [ml](https://github.com/KxSystems/ml) – [Machine-Learning Toolkit](https://code.kx.com/q/ml/toolkit/)


## Training 

* [analyst-training](https://github.com/kxsystems/analyst-training) – Training for [KX Analyst](https://code.kx.com/analyst/) and [KX Developer](https://code.kx.com/developer/) 
* [cookbook](https://github.com/KxSystems/cookbook) – Companion files to the Knowledge Base
* [mlnotebooks](https://github.com/KxSystems/mlnotebooks) – [Machine-Learning notebooks](https://code.kx.com/q/ml/notebooks/)
* [nlp](https://github.com/KxSystems/nlp) – Demonstration notebook for [natural-language processing](https://code.kx.com/q/ml/nlp/)
* [phrases](https://github.com/kxcontrib/phrases) – The Q Phrasebook

