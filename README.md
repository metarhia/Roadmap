# Metarhia subsystems

| Subsystem / Task              | Priority | Maintainer        | Comments                    |
| ----------------------------- | -------- | ----------------- | --------------------------- |
| Application server            | High     | Timur Shemsedinov | worker restart & stability  |
| Core modules                  | Medium   | Timur Shemsedinov | support                     |
| Ultra-thin isolation (metavm) | High     | Timur Shemsedinov | dependencies access control |
| Lowcode runtime (lowscript)   | High     | Timur Shemsedinov | `md`, `petri`               |
| Scheduling                    | Medium   | Timur Shemsedinov | `0 5 * ? * * *`             |
| Schemas (metaschema)          | Critical | Georg Oldenburger | custom types, refactoring   |
| OAuth 2.0                     | Critical |                   | prerequisite for ESB        |
| Enterprise bus                | Critical | Timur Shemsedinov | declarative integration     |
| Storage multitenancy          | Critical | Georg Oldenburger | sharding key, tenant id     |
| Application multitenancy      | Critical | Timur Shemsedinov | impress as virtual hosting  |
| Deploy automation             | Medium   |                   | `git pull` and restart      |
| Health monitoring             | Medium   |                   | Logs, profiling, metrics    |
| Payment integration           | Medium   |                   | Paypal, Stripe              |
| Green threads                 | Medium   | Timur Shemsedinov | `noroutine`                 |
| File storage                  | Medium   |                   | `S3`, `MinIO`               |
| Mail subsystem                | Medium   |                   | `metamail`                  |
| Report generator              | Medium   |                   | `LaTeX` or `pdfmake`        |
| Message queue                 | Medium   | Timur Shemsedinov | Redis BULL, `metacom` + MQ  |
| Form generator                | Medium   | Leon Polak        |                             |
| Admin panel                   | Medium   | Leon Polak        |                             |
| WEB IDE                       | Medium   | Leon Polak        |                             |
| Frontend framework            | Medium   | Roman Ohiievych   | `swayer`                    |
| Metacom (ws, streams)         | Low      | Roman Ohiievych   |                             |
| Transport (http2, tcp, tls)   | Low      |                   |                             |
| Computation (Spreadsheet)     | Low      | Timur Shemsedinov | js reactive expressions     |
| Metarhia CLI                  | Low      |                   | generate app, api etc.      |
| Orchestration                 | Low      | Timur Shemsedinov | `metacom` between peers     |
| Double-entry accounting       | Low      |                   | reactive js expressions     |
| PG migrations                 | Paused   |                   |                             |
| Application firewall          | Paused   |                   |                             |
| Load balancer                 | Paused   |                   |                             |
| Globalstorage                 | Paused   | Timur Shemsedinov | distributed storage         |

## Timeline

| Critical | High   | Medium  | Low         | Paused |
| -------- | ------ | ------- | ----------- | ------ |
| 14 May   | 21 May | 11 June | End ot 2022 |        |
