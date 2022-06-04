# Metarhia subsystems

## Done issues

| Subsystem / Task                         | Priority  | Maintainer                        | Comments                                           |
| ---------------------------------------- | --------- | --------------------------------- | -------------------------------------------------- |
| Application server ([impress][impress])  | Done      | [Timur Shemsedinov][tshemsedinov] | worker restart & stability                         |
| Scheduling refactor                      | Done      | [Timur Shemsedinov][tshemsedinov] | run task planner in thread 0                       |
| Schemas ([metaschema][metaschema])       | Done      | [Georg Oldenburger][georgolden]   | custom types, refactoring                          |
| Enterprise bus ([openapi][openapi])      | Done      | [Timur Shemsedinov][tshemsedinov] | declarative service integration                    |
| Application multitenancy                 | Done      | [Timur Shemsedinov][tshemsedinov] | on the top of multithreading                       |
| Metacom: run server in random thread     | Done      | [Timur Shemsedinov][tshemsedinov] | https://github.com/metarhia/metacom/issues/302     |
| Metacom: run in any thread               | Done      | [Timur Shemsedinov][tshemsedinov] | https://github.com/metarhia/metacom/pull/233       |
| Computation (Spreadsheet)                | Done      | [Timur Shemsedinov][tshemsedinov] | [metacalc][metacalc] js reactive expressions       |

## Next month plan

| Subsystem / Task                         | Priority  | Maintainer                        | Comments                                           |
| ---------------------------------------- | --------- | --------------------------------- | -------------------------------------------------- |
| Core modules                             | Permanent | [Timur Shemsedinov][tshemsedinov] | support                                            |
| Ultra-thin isolation ([metavm][metavm])  | High      | [Timur Shemsedinov][tshemsedinov] | dependencies access control                        |
| Lowcode runtime ([lowscript][lowscript]) | High      | [Timur Shemsedinov][tshemsedinov] | [md][md], [petri][petri]                           |
| Scheduling improve                       | Medium    | [Timur Shemsedinov][tshemsedinov] | [cron][cron]: `0 5 * ? * * *`                      |
| [OAuth 2.0][oauth2] client               | Critical  | [Timur Shemsedinov][tshemsedinov] | prerequisite for ESB                               |
| [OAuth 2.0][oauth2] server               | Low       |                                   | provide auth service for 3rd party app             |
| Storage multitenancy                     | Critical  | [Georg Oldenburger][georgolden]   | sharding key, tenant id                            |
| User custom code multitenancy            | Critical  | [Timur Shemsedinov][tshemsedinov] | on the top of multitreading multitenancy           |
| Deploy docker setup                      | Medium    |                                   |                                                    |
| Deploy automation                        | Medium    |                                   | `git pull` and restart                             |
| Health monitoring                        | Medium    |                                   | Logs, profiling, metrics                           |
| Payment integration                      | Medium    | [Leon Polak][leonpolak]           | [Paypal][paypal], [Stripe][stripe]                 |
| Green threads                            | Medium    | [Timur Shemsedinov][tshemsedinov] | [noroutine][noroutine]                             |
| File storage                             | Medium    |                                   | [S3][s3], [MinIO][minio]                           |
| Mail subsystem                           | Medium    |                                   | [metamail][metamail]                               |
| Report generator                         | Medium    |                                   | [LaTeX][latex], [pdfmake][pdfmake]                 |
| Message queue                            | Medium    | [Timur Shemsedinov][tshemsedinov] | [Redis BULL][bull], [metacom][metacom]             |
| Form generator                           | Medium    | [Leon Polak][leonpolak]           |                                                    |
| Admin panel                              | Medium    | [Leon Polak][leonpolak]           |                                                    |
| WEB IDE                                  | Medium    | [Leon Polak][leonpolak]           |                                                    |
| Frontend framework                       | Medium    | [Roman Ohiievych][rohiievych]     | [swayer][swayer]                                   |
| Metacom: send events to server           | Medium    | [Timur Shemsedinov][tshemsedinov] | https://github.com/metarhia/metacom/issues/304     |
| Metacom: streams                         | Medium    | [Roman Ohiievych][rohiievych]     | https://github.com/metarhia/metacom/pull/233       |
| Metacom transport: ws                    | Low       |                                   | https://github.com/metarhia/metacom/issues/192     |
| Metacom transport: tcp, tls              | Low       |                                   | https://github.com/metarhia/metacom/issues/305     |
| Metacom transport: http2, http3          | Low       |                                   | https://github.com/metarhia/metacom/issues/306     |
| Metarhia CLI                             | Low       |                                   | generate app, api etc.                             |
| Orchestration                            | Medium    | [Timur Shemsedinov][tshemsedinov] | [metacom][metacom] between peers                   |
| Double-entry accounting                  | Low       |                                   | reactive js expressions                            |
| PG migrations                            | Paused    |                                   | [metasql][metasql]                                 |
| Application firewall                     | Paused    |                                   | https://github.com/metarhia/impress/issues/928     |
| Load balancer                            | Paused    |                                   |                                                    |
| Globalstorage                            | Paused    | [Timur Shemsedinov][tshemsedinov] | [globalstorage][globalstorage] distributed storage |

## Timeline

| Critical | High    | Medium  | Low         | Paused |
| -------- | ------- | ------- | ----------- | ------ |
| 11 June  | 18 June | 02 July | End of 2022 |        |

[impress]: https://github.com/metarhia/impress
[metavm]: https://github.com/metarhia/metavm
[lowscript]: https://github.com/metarhia/lowscript
[metaschema]: https://github.com/metarhia/metaschema
[noroutine]: https://github.com/metarhia/noroutine
[metamail]: https://github.com/metarhia/metamail
[swayer]: https://github.com/metarhia/swayer
[metacom]: https://github.com/metarhia/metacom
[metacalc]: https://github.com/metarhia/metacalc
[metasql]: https://github.com/metarhia/metasql
[globalstorage]: https://github.com/metarhia/globalstorage
[oauth2]: https://oauth.net/2/
[tshemsedinov]: https://github.com/tshemsedinov
[leonpolak]: https://github.com/leonpolak
[georgolden]: https://github.com/georgolden
[rohiievych]: https://github.com/rohiievych
[md]: https://daringfireball.net/projects/markdown/
[petri]: https://en.wikipedia.org/wiki/Petri_net
[cron]: https://en.wikipedia.org/wiki/Cron
[openapi]: https://github.com/metarhia/impress/issues/1733
[s3]: https://aws.amazon.com/s3/
[minio]: https://min.io/
[latex]: https://www.latex-project.org/
[pdfmake]: https://www.npmjs.com/package/pdfmake
[bull]: https://github.com/OptimalBits/bull
[paypal]: https://www.paypal.com/
[stripe]: https://stripe.com/
