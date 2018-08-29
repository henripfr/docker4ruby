# Docker-based Ruby stack

[![Build Status](https://travis-ci.com/wodby/docker4ruby.svg?branch=master)](https://travis-ci.com/wodby/docker4ruby)

## Introduction

Docker4Ruby is a set of docker images optimized for Ruby applications. Use `docker-compose.yml` file from the [latest stable release](https://github.com/wodby/docker4ruby/releases) to spin up local environment on Linux, Mac OS X and Windows. 

* Read the docs on [**how to use**](https://docs.wodby.com/stacks/ruby/local#usage)
* Follow [@wodbycloud](https://twitter.com/wodbycloud) for updates announcements
* Join [community slack](https://slack.wodby.com) to ask questions

## Stack

The Ruby stack consist of the following containers:

| Container     | Versions           | Service name    | Image                              | Default |
| ------------- | ------------------ | --------------- | ---------------------------------- | ------- |
| [Nginx]       | 1.15, 1.14         | `nginx`         | [wodby/nginx]                      | ✓       |
| [Ruby]        | 2.5, 2.4, 2.3      | `ruby`          | [wodby/ruby]                       |         |
| [PostgreSQL]  | 10, 9.x            | `postgres`      | [wodby/postgres]                   |         |
| [MariaDB]     | 10.3, 10.2, 10.1   | `mariadb`       | [wodby/mariadb]                    | ✓       |
| [Redis]       | 4.0, 3.2           | `redis`         | [wodby/redis]                      |         |
| [Node.js]     | 9.11, 8.11, 6.14   | `node`          | [wodby/node]                       |         |
| [Varnish]     | 4.1                | `varnish`       | [wodby/varnish]                    |         |
| [Solr]        | 7.x, 6.6, 5.5      | `solr`          | [wodby/solr]                       |         |
| Elasticsearch | 6.x, 5.6, 5.5, 5.4 | `elasticsearch` | [wodby/elasticsearch]              |         |
| Kibana        | 6.x, 5.6, 5.5, 5.4 | `kibana`        | [wodby/kibana]                     |         |
| [Memcached]   | 1.5                | `memcached`     | [wodby/memcached]                  |         |
| [Rsyslog]     | latest             | `rsyslog`       | [wodby/rsyslog]                    |         |
| [AthenaPDF]   | 2.10.0             | `athenapdf`     | [arachnysdocker/athenapdf-service] |         |
| [Mailhog]     | latest             | `mailhog`       | [mailhog/mailhog]                  | ✓       |
| [OpenSMTPD]   | 6.0                | `opensmtpd`     | [wodby/opensmtpd]                  |         |
| Adminer       | 4.6                | `adminer`       | [wodby/adminer]                    |         |
| Portainer     | latest             | `portainer`     | [portainer/portainer]              | ✓       |
| Traefik       | latest             | `traefik`       | [_/traefik]                        | ✓       |

## Documentation

Full documentation is available at https://docs.wodby.com/stacks/ruby/local

## Maintenance

We regularly update images used in this stack and release them together, see [releases page](https://github.com/wodby/docker4ruby/releases) for full changelog and update instructions.

## License

This project is licensed under the MIT open source license.

[Apache]: https://wodby.com/stacks/ruby/docs/containers/apache
[AthenaPDF]: https://wodby.com/stacks/ruby/docs/containers/athenapdf/
[Blackfire]: https://wodby.com/stacks/ruby/docs/containers/blackfire/
[Mailhog]: https://wodby.com/stacks/ruby/docs/containers/mailhog/
[MariaDB]: https://wodby.com/stacks/ruby/docs/containers/mariadb
[Memcached]: https://wodby.com/stacks/ruby/docs/containers/memcached/
[Nginx]: https://wodby.com/stacks/ruby/docs/containers/nginx
[Node.js]: https://wodby.com/stacks/ruby/docs/containers/node
[OpenSMTPD]: https://wodby.com/stacks/ruby/docs/containers/opensmtpd/
[PostgreSQL]: https://wodby.com/stacks/ruby/docs/containers/postgres
[Redis]: https://wodby.com/stacks/ruby/docs/containers/redis
[Rsyslog]: https://wodby.com/stacks/ruby/docs/containers/rsyslog/
[Ruby]: https://wodby.com/stacks/ruby/docs/containers/ruby/
[Solr]: https://wodby.com/stacks/ruby/docs/containers/solr/
[Varnish]: https://wodby.com/stacks/ruby/docs/containers/varnish

[_/traefik]: https://hub.docker.com/_/traefik
[arachnysdocker/athenapdf-service]: https://hub.docker.com/r/arachnysdocker/athenapdf-service
[blackfire/blackfire]: https://hub.docker.com/r/blackfire/blackfire
[mailhog/mailhog]: https://hub.docker.com/r/mailhog/mailhog
[portainer/portainer]: https://hub.docker.com/portainer/portainer
[wodby/adminer]: https://hub.docker.com/r/wodby/adminer
[wodby/elasticsearch]: https://github.com/wodby/elasticsearch
[wodby/kibana]: https://github.com/wodby/kibana
[wodby/mariadb]: https://github.com/wodby/mariadb
[wodby/memcached]: https://github.com/wodby/memcached
[wodby/node]: https://github.com/wodby/node
[wodby/opensmtpd]: https://github.com/wodby/opensmtpd
[wodby/nginx]: https://github.com/wodby/nginx
[wodby/ruby]: https://github.com/wodby/ruby
[wodby/postgres]: https://github.com/wodby/postgres
[wodby/redis]: https://github.com/wodby/redis
[wodby/rsyslog]: https://hub.docker.com/r/wodby/rsyslog
[wodby/solr]: https://github.com/wodby/solr
[wodby/varnish]: https://github.com/wodby/varnish
