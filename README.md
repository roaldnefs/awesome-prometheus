# Awesome Prometheus  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Prometheus resources, projects and tools.

Prometheus is an open-source systems monitoring and alerting toolkit.

## Contents

- [Official resources](#official-resources)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Podcasts and interviews](#podcasts-and-interviews)
- [Presentations](#presentations)
- [Blogposts and opinions](#blogposts-and-opinions)
- [Dashboards](#dashboards)
- [Exporters](#exporters)
- [Uncategorized](#uncategorized)

## Official resources

* [Prometheus](https://prometheus.io/) - Official Prometheus project website.
* [GitHub repo](https://github.com/prometheus/prometheus) - Prometheus' source code, issues discussion and collaboration.
* [Prometheus Documentation](https://prometheus.io/docs/introduction/overview/) - Official Prometheus documentation.
* [Prometheus Blog](https://prometheus.io/blog/) - Official Prometheus blog.

## Tutorials

* [How To Install Prometheus using Docker on CentOS 7 ](https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-using-docker-on-centos-7) - Walkthough on how to install Prometheus on CentOS 7.
* [How to Use Prometheus to Monitor Your CentOS 7 Server ](https://www.digitalocean.com/community/tutorials/how-to-use-prometheus-to-monitor-your-centos-7-server) - Walkthough on how to monitor a CentOS 7 server using Prometheus.
* [How To Install Prometheus using Docker on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-using-docker-on-ubuntu-14-04) - Walkthough on how to install Prometheus on Ubuntu 14.04.
* [How To Use Prometheus to Monitor Your Ubuntu 14.04 Server](https://www.digitalocean.com/community/tutorials/how-to-use-prometheus-to-monitor-your-ubuntu-14-04-server) - Walkthough on how to monitor a Ubuntu 14.04 server using Prometheus.
* [How To Query Prometheus on Ubuntu 14.04 Part 1](https://www.digitalocean.com/community/tutorials/how-to-query-prometheus-on-ubuntu-14-04-part-1) - Part 1 of 2 in the series _How To Query Prometheus on Ubuntu 14.04_.
* [How To Query Prometheus on Ubuntu 14.04 Part 2](https://www.digitalocean.com/community/tutorials/how-to-query-prometheus-on-ubuntu-14-04-part-2) - Part 2 in the series _How To Query Prometheus on Ubuntu 14.04_.
* [How To Add a Prometheus Dashboard to Grafana ](https://www.digitalocean.com/community/tutorials/how-to-add-a-prometheus-dashboard-to-grafana) - Walkthrough on how to add a Prometheus dashboard to Grafana.
* [Instructions and example code for a Prometheus workshop](https://github.com/juliusv/prometheus_workshop) - Instructions and example code for a Prometheus workshop by Julius Volz.
* [Checking if SSH is responding with Prometheus](https://www.robustperception.io/checking-if-ssh-is-responding-with-prometheus/) - Walkthrough on how to use the Blackbox Exporter to check if SSH is responding by Brian Brazil.

## Videos

* [PromCon 2016](https://www.youtube.com/playlist?list=PLoz-W_CUquUlCq-Q0hy53TolAhaED9vmU) - PromCon Berlin - August 25-26, 2016 - talk recordings from PromCon 2016 in Berlin.
* [Prometheus Monitoring for Java Developers](https://www.youtube.com/watch?v=jb9j_IYv4cU) - Devoxx Belgium - November 8, 2016 - Fabian Stäber.
* [Prometheus: A Next Generation Monitoring System](https://www.youtube.com/watch?v=cwRmXqXKGtk) - FOSDEM 2016 - January 31, 2016 - Brian Brazil.

## Podcasts and interviews

* [Prometheus on FLOSS Weekly 357](https://twit.tv/shows/floss-weekly/episodes/357) -  Julius Volz on the FLOSS Weekly TWiT.tv show.
* [Prometheus and Service Monitoring ](https://changelog.com/podcast/168) - Julius Volz on the Changelog podcast.

## Presentations

* [Prometheus Overview](http://www.slideshare.net/brianbrazil/prometheus-overview) - The Promethean ideal of monitoring by Brian Brazil.
* [System Monitoring with Prometheus](http://www.slideshare.net/brianbrazil/devops-ireland-systems-monitoring-with-prometheus) - Brian Brazil at Devops Ireland Meetup, Dublin.
* [OMG! Prometheus](https://www.dropbox.com/s/0l7kxhjqjbabtb0/prometheus%20site-ops%20preso.pdf?dl=0) - Benjamin Staffin, Fitbit Site Operations, explains the case for Prometheus to his team.

## Blogposts and opinions

* [Prometheus: Monitoring at SoundCloud ](https://developers.soundcloud.com/blog/prometheus-monitoring-at-soundcloud) - Overview of Prometheus and first hand experience from Soundcloud.
* [Prometheus: A Next-Generation Monitoring System](http://www.boxever.com/prometheus-a-next-generation-monitoring-system/) - First hand experiences using Prometheus from Boxever Tech.
* [Monitor Docker Containers with Prometheus](http://5pi.de/2015/01/26/monitor-docker-containers-with-prometheus/) - Using Prometheus to monitor Docker containers.
* [Prometheus and Kubernetes: A Perfect Match](https://www.weave.works/prometheus-kubernetes-perfect-match/) - Part 1 of 3 in the series _Prometheus and Kubernetes_.
* [Prometheus and Kubernetes: Deploying](https://www.weave.works/prometheus-kubernetes-deploying/) - Part 2 of 3 in the series _Prometheus and Kubernetes_.
* [Prometheus and Kubernetes: Monitoring Your Applications](https://www.weave.works/prometheus-and-kubernetes-monitoring-your-applications/) - Part 3 in the series _Prometheus and Kubernetes_.
* [Robust Perception](https://www.robustperception.io/tag/prometheus/) - Multiple blogposts about Prometheus by Brian Bazil.

## Dashboards

* [Grafana](https://prometheus.io/docs/visualization/grafana/) - Grafana is an open source metric analytics & visualization suite _tutorial by Prometheus_.
* [Grafana](http://docs.grafana.org/datasources/prometheus/) - Grafana is an open source metric analytics & visualization suite _tutorial by Grafana_.
* [PromDash](https://prometheus.io/docs/visualization/promdash/) - Browser-based dashboard builder for Prometheus _tutorial by Prometheus_.

## Exporters
* [Blackbox exporter](https://github.com/prometheus/blackbox_exporter) - The Blackbox exporter allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP and ICMP **(official exporter)**.
* [HAProxy exporter](https://github.com/prometheus/haproxy_exporter) - The HAProxy exporter periodically scrapes HAProxy stats **(official exporter)**.
* [Memcached exporter](https://github.com/prometheus/memcached_exporter) - The Memcached exporter periodically scrapes Memcached stats **(official exporter)**.
* [MySQL Server exporter](https://github.com/prometheus/mysqld_exporter) - The MySQL server exporter periodically scrapes MySQL stats **(official exporter)**.
* [Node exporter](https://github.com/prometheus/node_exporter) - The Node exporter periodically scrapes system stats **(official exporter)**.

## Uncategorized

* [Prometheus Monitoring subreddit](https://www.reddit.com/r/PrometheusMonitoring/) - Subreddit collecting all Prometheus-related resources on the internet.
* [PromCon](https://promcon.io/) - The Prometheus conference.

## License

[![CC0](https://camo.githubusercontent.com/60561947585c982aee67ed3e3b25388184cc0aa3/687474703a2f2f6d6972726f72732e6372656174697665636f6d6d6f6e732e6f72672f70726573736b69742f627574746f6e732f38387833312f7376672f63632d7a65726f2e737667)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Roald](https://github.com/roaldnefs/) has waived all copyright and related or neighboring rights to this work.
