# Awesome Q 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/StephenTaylor-Kx/awesome-q) ![Maintenance](https://img.shields.io/maintenance/yes/2022)

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
Python | [pyq](https://github.com/KxSystems/pyq) | [call q from Python](https://code.kx.com/q/interfaces/pyq/)
R | [rkdb](https://github.com/KxSystems/rkdb) | [R client for q](https://code.kx.com/q/interfaces/r/)
Reuters | [kdb/c](https://github.com/KxSystems/kdb/blob/master/c/feed/rfa.zip)
Solace | [solace](https://github.com/KxSystems/solace) | [Solace pub/sub brokers](https://code.kx.com/q/interfaces/solace/)


## Other interfaces 

to     | source | note
-------|--------|-----
C | [KxSystems/kdb](https://github.com/KxSystems/kdb) | [C client for kdb+](https://code.kx.com/q/interfaces/c-client-for-q/)
C# | [kxcontrib/csharpgui](https://github.com/kxcontrib/csharpgui) | C# GUI
Excel | [CharlesSkelton/excelrtd](https://github.com/CharlesSkelton/excelrtd) | [Microsoft Excel™ client for kdb+](https://code.kx.com/q/interfaces/excel-client-for-q/)
FITS | [jpneill/fitsToKdb](https://github.com/jpneill/fitsToKdb) | access tables in NASA FITS files
Java | [CharlesSkelton/jshow](https://github.com/CharlesSkelton/jshow) 
JavaScript | | [WebSockets](https://code.kx.com/q/kb/websockets/)
JDBC | [CharlesSkelton/babel](https://github.com/CharlesSkelton/babel) | query other databases via JDBC
Lua | [geocar/qlua](https://github.com/geocar/qlua) | q client for Lua
Mathematica | [KxSystems/kdb](https://github.com/KxSystems/kdb/blob/master/c/other/qmathematica.txt) | Mathematica5 -> Q interface
ODBC |  | [client for ODBC](https://code.kx.com/q/interfaces/q-client-for-odbc/)
Python | [PyKX](https://code.kx.com/pykx/)<br>[qPython](https://qpython.readthedocs.io/en/latest/)
NaCL | [geocar/qsalt](https://github.com/geocar/qsalt) | NaCL bindings for q/kdb
NodeJS | [geocar/qnode](https://github.com/geocar/qnode) | kdb+ client in NodeJS
ODBC | | [server for ODBC3](https://code.kx.com/q/interfaces/q-server-for-odbc3/)
PHP | [geocar/qphp](https://github.com/geocar/qphp) | kdb+ IPC implementation for PHP
WebSockets | [kxcontrib/websocket](https://github.com/kxcontrib/websocket)


## Editor integrations

editor | source | note
-------|--------|-----
Emacs  | [geocar/kq-mode](https://github.com/geocar/kq-mode) | major mode for Emacs; supports Tramp and Babel<br>[psaris/q-mode](https://github.com/psaris/q-mode)
Evolved  | [simongarland/Syntaxhighlighter-for-q](https://github.com/simongarland/Syntaxhighlighter-for-q)
TextMate  | [psaris/KX.tmbundle](https://github.com/psaris/KX.tmbundle)
vim  | [simongarland/vim](https://github.com/simongarland/vim)
Visual Studio Code | [jshinonome/vscode-q](https://github.com/jshinonome/vscode-q)
WordPress  | [Syntaxhighlighter-for-q](https://github.com/simongarland/Syntaxhighlighter-for-q)


## Frameworks

* [kdb-taq](https://github.com/KxSystems/kdb-taq) – Process trade-and-quote data
* [kdb-tick](https://github.com/KxSystems/kdb-tick) – [tickerplant](kb/kdb-tick.md)


## Cloud deployment

KX Insights provides tools for deploying kdb+ systems in the cloud.

* [KX Insights Core](https://code.kx.com/insights/core/): 
    * packaging
    * orchestration
    * REST interfaces
    * logging
    * object storage
    * Google BigQuery
* [KX Insights Microservices](https://code.kx.com/insights/microservices/): an ecosystem of cloud-native microservices, built with kdb+ Cloud Edition, all with OpenAPI specifications
    * service discovery
    * data access
    * service gateway
    * storage manager
    * stream processor
    * dashboards
* [kxcontrib/cloud-autoscaling](https://github.com/kxcontrib/cloud-autoscaling) – cloud autoscaling


## Database admin and devops

* [kxcontrib/BigQueryKdbInteroperability](https://github.com/kxcontrib/BigQueryKdbInteroperability) – Transferring data to and from BigQuery
* [kxcontrib/kdbAlertTP](https://github.com/kxcontrib/kdbAlertTP) – Tickerplant set-up to test Alert Monitor
* [MdSalih/Kdb-stuff](https://github.com/MdSalih/Kdb-stuff) – ServerChecker: how to execute commands on a remote box via SSH from within a q process and parse Linux system info (cpuinfo/meminfo/df)
* [kxcontrib/massIngestionDataloader](https://github.com/kxcontrib/massIngestionDataloader) – Mass data ingestion
* [jfealy/q](https://github.com/jfealy/q) – Database and log utilities
* [gyorokpeter/qbinparse](https://github.com/gyorokpeter/qbinparse) – Customizable binary data parser


## Developer tools

* [LeslieGoldsmith/dpy](https://github.com/LeslieGoldsmith/dpy) – General object display with type and structure
* [KxSystems/help](https://github.com/KxSystems/help) – Online help for q
* [KxSystems/kdb](https://github.com/KxSystems/kdb) – Companion files to the kdb+ product
* [KxSystems/man](https://github.com/KxSystems/man) – [man-style reference](https://code.kx.com/q/about/man.md) 
* [gitrj95/q-memo](https://github.com/gitrj95/q-memo) – memoize functions that are expensive to compute
* [LeslieGoldsmith/qprof](https://github.com/LeslieGoldsmith/qprof) – Code profiler 
* [CillianReilly/qtools](https://github.com/CillianReilly/qtools) – Development tools
* [Charles/Skelton/studio](https://github.com/CharlesSkelton/studio) – A rapid-development environment for q
* [LeslieGoldsmith/ws](https://github.com/LeslieGoldsmith/ws) – Workspace utilities


## FinTech

* [BrianOSu/qlibs](https://github.com/BrianOSu/qlibs) – [Binance](https://www.binance.com/en) interface
* [finos/kdb](https://github.com/finos/kdb) – Common standards, tools, and libraries to facilitate collaborative development, ease artifact reuse, and improve usability and administration of kdb+ software in enterprise deployments
* [kxcontrib/market-fragmentation](https://github.com/kxcontrib/market-fragmentation) – Analyse market fragmentation
* [dmorgankx/optionpricing](https://github.com/dmorgankx/optionpricing) – Option pricing


## Machine learning

* [kxcontrib/wp-knn](https://github.com/kxcontrib/wp-knn) – K Nearest Neighbors
* [KxSystems/ml](https://github.com/KxSystems/ml) – [Machine-Learning Toolkit](https://code.kx.com/q/ml/toolkit/)


## Miscellaneous
<!-- Divide as it grows -->
* [cburke/amcharts](https://github.com/kxcontrib/cburke/tree/master/amcharts/) – A set of flash charts designed for Web applications
* [quintanar401/DCoQ](https://github.com/quintanar401/DCoQ) – ‘Dark corners’ of q
* [skeevey/fb.q](https://github.com/skeevey/fb.q) – Flappy birds clone in q for Linux
* [stevanapter/hypertree](https://github.com/stevanapter/hypertree) – Recursive aggregating treetable and 3-D pivot table for hypergrid
* [BuaBook/kdb-common](https://github.com/BuaBook/kdb-common) – Miscellaneous production libraries
* [kxcontrib/oauth2](https://github.com/kxcontrib/oauth2) – OAuth2
* [rianoc/qCam](https://github.com/rianoc/qCam) – Image capture and manipulation on a Raspberry Pi 
* [emc211/qGames](https://github.com/emc211/qGames) – Games: Battleship, chess, Minesweeper, poker
* [kxcontrib/q-signals](https://github.com/kxcontrib/q-signals) – Signal processing
* [gyorokpeter/qx86](https://github.com/gyorokpeter/qx86) – x86 assembler, disassembler and emulator
* [kxcontrib/trend-indicators](https://github.com/kxcontrib/trend-indicators) – Trend indicators
* [AngusWilson/whatStats](https://github.com/AngusWilson/whatStats) – Analyse WhatsApp chat logs
* [gyorokpeter/qtcp](https://github.com/gyorokpeter/qtcp) – Open raw TCP connections in-process for q to communicate through


## Training 

* [KxSystems/analyst-training](https://github.com/kxsystems/analyst-training) – Training for [KX Analyst](https://code.kx.com/analyst/) and [KX Developer](https://code.kx.com/developer/) 
* [KxSystems/cookbook](https://github.com/KxSystems/cookbook) – Companion files to the Knowledge Base
* [KxSystems/mlnotebooks](https://github.com/KxSystems/mlnotebooks) – [Machine-Learning notebooks](https://code.kx.com/q/ml/notebooks/)
* [KxSystems/nlp](https://github.com/KxSystems/nlp) – Demonstration notebook for [natural-language processing](https://code.kx.com/q/ml/nlp/)
* [kxcontrib/phrases](https://github.com/kxcontrib/phrases) – The Q Phrasebook

