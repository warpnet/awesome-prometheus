# Awesome Prometheus  [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Prometheus resources, projects and tools.

<!--lint ignore double-link-->
[![Prometheus](media/prometheus.png)](https://prometheus.io/)

Prometheus is an open-source systems monitoring and alerting toolkit.

## Contents
- [Official resources](#official-resources)
- [Tutorials](#tutorials)
- [Books](#books)
- [Videos](#videos)
- [Podcasts and interviews](#podcasts-and-interviews)
- [Presentations](#presentations)
- [Blog posts and opinions](#blog-posts-and-opinions)
- [Deployment tools](#deployment-tools)
- [Dashboards](#dashboards)
- [Exporters](#exporters)
    - [Databases](#databases)
    - [Hardware related](#hardware-related)
    - [HTTP](#http)
    - [Other monitoring systems](#other-monitoring-systems)
    - [Miscellaneous](#miscellaneous)
- [Alertmanager](#alertmanager)
- [Proxies](#proxies)
- [High Availability](#high-availability)
- [Uncategorized](#uncategorized)

## Official resources
<!--lint ignore double-link-->
- [Website](https://prometheus.io/) - Official Prometheus project website.
- [GitHub repository](https://github.com/prometheus/prometheus) - Prometheus' source code, issues discussion and collaboration.
- [Documentation](https://prometheus.io/docs/introduction/overview/) - Official Prometheus documentation.
- [Blog](https://prometheus.io/blog/) - Official Prometheus blog.
- [Official Prometheus demo](https://demo.do.prometheus.io) - Official Prometheus demo site managed by Cloud Alchemy Ansible roles updating daily using configuration from [Prometheus repository](https://github.com/prometheus/demo-site).

## Tutorials
- [Kubernetes monitoring with Prometheus, the ultimate guide](https://sysdig.com/blog/kubernetes-monitoring-prometheus/) - Kubernetes monitoring with Prometheus, the ultimate guide by Mateo Burillo.
- [How To Install Prometheus using Docker on CentOS 7](https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-using-docker-on-centos-7) - Walkthrough on how to install Prometheus on CentOS 7.
- [How to Use Prometheus to Monitor Your CentOS 7 Server](https://www.digitalocean.com/community/tutorials/how-to-use-prometheus-to-monitor-your-centos-7-server) - Walkthrough on how to monitor a CentOS 7 server using Prometheus.
- [How To Add a Prometheus Dashboard to Grafana](https://www.digitalocean.com/community/tutorials/how-to-add-a-prometheus-dashboard-to-grafana) - Walkthrough on how to add a Prometheus dashboard to Grafana.
- [Instructions and example code for a Prometheus workshop](https://github.com/juliusv/prometheus_workshop) - Instructions and example code for a Prometheus workshop by Julius Volz.
- [Checking if SSH is responding with Prometheus](https://www.robustperception.io/checking-if-ssh-is-responding-with-prometheus/) - Walkthrough on how to use the Blackbox Exporter to check if SSH is responding by Brian Brazil.
- [Monitor your GitHub Repos with Docker and Prometheus](https://www.brianchristner.io/monitor-your-github-repos-with-docker/) - Monitor your GitHub Repos with Docker and Prometheus.
- [Docker daemon metrics in Prometheus](https://medium.com/lucjuggery/docker-daemon-metrics-in-prometheus-7c359c7ff550) - Docker daemon metrics in Prometheus by Luc Juggery.
- [Prometheus Monitoring Tutorial (10 minutes)](https://pagertree.com/blog/prometheus-monitoring-tutorial) - Simple tutorial to create a Prometheus monitoring stack with Grafana, AlertManager, and PagerTree by Austin Miller.
- [Prometheus-Basics](https://github.com/yolossn/Prometheus-Basics) - Beginner friendly introduction to Prometheus by [yolossn](https://github.com/yolossn).
- [Setting up Prometheus Monitoring On a Kubernetes Cluster](https://spacelift.io/blog/prometheus-kubernetes) - Setting up Prometheus Monitoring On a Kubernetes Cluster by James Walker.

## Books
- [Monitoring with Prometheus](https://www.prometheusbook.com/) - Monitoring with Prometheus by James Turnbull.
- [Prometheus: Up & Running](http://shop.oreilly.com/product/0636920147343.do) - Prometheus: Up & Running by Brian Brazil.
- [Hands-On Infrastructure Monitoring with Prometheus](https://www.prombook.info/) - Hands-On Infrastructure Monitoring with Prometheus by Joel Bastos & Pedro Araújo, reviewed by Brian Brazil.

## Videos
- [PromCon Online 2020](https://www.youtube.com/playlist?list=PLoz-W_CUquUm0r6nxziK9B9LnmNntzctE) - PromCon Online - July 14-16, 2020.
- [PromCon 2019](https://www.youtube.com/playlist?list=PLoz-W_CUquUmIYKS97RBghcWumZIX2kvv) - PromCon Munich - November 7-8, 2019, PromCon EU 2019.
- [An Introduction to Systems & Service Monitoring with Prometheus](https://www.youtube.com/watch?v=5O1djJ13gRU) - GOTO 2019: An Introduction to Systems & Service Monitoring with Prometheus - Julius Volz.
- [Explain it Like I'm Five - What I Learned Teaching Observability to My Kids](https://vimeo.com/341142428) - Monitorama PDX, 2019 - Dave Cadwallader.
- [Prometheus Deep Dive](https://www.youtube.com/watch?v=Me-kZi4xkEs) - KubeCon - 2017 - GitLab: Prometheus Deep Dive - Ben Kochie.
- [PromCon 2018](https://www.youtube.com/playlist?list=PLoz-W_CUquUlml1wBtQVBKErwoszt5B0h) - PromCon Munich - August 9-10, 2018 - talk recordings from PromCon 2018 in Munich.
- [Prometheus Monitoring for Java Web Applications w o Modifying Source Code](https://www.youtube.com/watch?v=BjyI93c8ltA) - Devoxx Belgium - November 7, 2017 - Fabian Stäber.
- [PromCon 2017](https://www.youtube.com/playlist\?list\=PLoz-W_CUquUlnvoEBbqChb7A0ZEZsWSXt) - PromCon Munich - August 17-18, 2017 - talk recordings from PromCon 2017 in Berlin.
- [Best Practices and Beastly Pitfalls](https://www.youtube.com/watch?v=_MNYuTNfTb4) - PromCon 2017: Best Practices and Beastly Pitfalls - Julius Volz.
- [Counting with Prometheus](https://www.youtube.com/watch?v=67Ulrq6DxwA) - Cloud Native Con - 2017 - Counting with Prometheus - Brian Brazil, Robust Perception.
- [Understanding and Extending Prometheus AlertManager](https://www.youtube.com/watch?v=jpb6fLQOgn4) - Cloud Native Con - 2017 - Understanding and Extending Prometheus AlertManager - Lee Calcote, SolarWinds.
- [Infrastructure and application monitoring using Prometheus](https://www.youtube.com/watch?v=5GYe_-qqP30) - Devoxx - May 17, 2017 at Devoxx UK - Marco Pas.
- [Prometheus Monitoring for Java Developers](https://www.youtube.com/watch?v=jb9j_IYv4cU) - Devoxx Belgium - November 8, 2016 - Fabian Stäber.
- [Prometheus: Design and Philosophy - why it is the way it is](https://www.youtube.com/watch?v=QgJbxCWRZ1s) - Docker - October 14, 2016 - Julius Volz.
- [PromCon 2016](https://www.youtube.com/playlist?list=PLoz-W_CUquUlCq-Q0hy53TolAhaED9vmU) - PromCon Berlin - August 25-26, 2016 - talk recordings from PromCon 2016 in Berlin.
- [Prometheus: A Next Generation Monitoring System](https://www.youtube.com/watch?v=cwRmXqXKGtk) - FOSDEM 2016 - January 31, 2016 - Brian Brazil.
- [The Prometheus Time Series Database](https://www.youtube.com/watch?v=HbnGSNEjhUc) - PromCon 2016: The Prometheus Time Series Database - Björn Rabenstein.
- [PromCon 2016: So You Want to Write an Exporter](https://www.youtube.com/watch?v=KXq5ibSj2qA) - PromCon 2016 - So You Want to Write an Exporter - Brian Brazil.

## Podcasts and interviews
- [Prometheus on FLOSS Weekly 357](https://twit.tv/shows/floss-weekly/episodes/357) -  Julius Volz on the FLOSS Weekly TWiT.tv show.
- [Prometheus and Service Monitoring](https://changelog.com/podcast/168) - Julius Volz on the Changelog podcast.
- [Prometheus Monitoring with Brian Brazil](https://softwareengineeringdaily.com/2016/08/10/prometheus-monitoring-with-brian-brazil/) - Brian Brazil on the Software Engineering Daily podcast.

## Presentations
- [Prometheus Overview](http://www.slideshare.net/brianbrazil/prometheus-overview) - The Promethean ideal of monitoring by Brian Brazil.
- [System Monitoring with Prometheus](http://www.slideshare.net/brianbrazil/devops-ireland-systems-monitoring-with-prometheus) - Brian Brazil at Devops Ireland Meetup, Dublin.
- [OMG! Prometheus](https://www.dropbox.com/s/0l7kxhjqjbabtb0/prometheus%20site-ops%20preso.pdf?dl=0) - Benjamin Staffin, Fitbit Site Operations, explains the case for Prometheus to his team.
- [Deploying Prometheus](https://fosdem.org/2017/schedule/event/deploying_prometheus_at_wikimedia_foundation/attachments/slides/1773/export/events/attachments/deploying_prometheus_at_wikimedia_foundation/slides/1773/Prometheus_at_WMF_Fosdem_2017.pdf) - Filippo Giunchedi, WikiMedia Foundation at FOSDEM 2017.

## Blog posts and opinions
- [Prometheus: Monitoring at SoundCloud](https://developers.soundcloud.com/blog/prometheus-monitoring-at-soundcloud) - Overview of Prometheus and first hand experience from Soundcloud.
- [Monitor Docker Containers with Prometheus](http://5pi.de/2015/01/26/monitor-docker-containers-with-prometheus/) - Using Prometheus to monitor Docker containers.
- [Prometheus and Kubernetes: A Perfect Match](https://www.weave.works/prometheus-kubernetes-perfect-match/) - Part 1 of 3 in the series _Prometheus and Kubernetes_.
- [Prometheus and Kubernetes: Deploying](https://www.weave.works/prometheus-kubernetes-deploying/) - Part 2 of 3 in the series _Prometheus and Kubernetes_.
- [Prometheus and Kubernetes: Monitoring Your Applications](https://www.weave.works/prometheus-and-kubernetes-monitoring-your-applications/) - Part 3 in the series _Prometheus and Kubernetes_.
- [Robust Perception](https://www.robustperception.io/tag/prometheus/) - Multiple blog posts about Prometheus by Brian Bazil.
- [Initial experiences with the Prometheus monitoring system](https://medium.com/@griggheo/initial-experiences-with-the-prometheus-monitoring-system-167054ac439c#.q565suk4h) - Initial experiences with the Prometheus by Grig Gheorghiu.
- [Monitor your applications with Prometheus](http://blog.alexellis.io/prometheus-monitoring/) - Monitor your applications with Prometheus by Alex Ellis.
- [Practical Services Monitoring with Prometheus and Docker](https://web.archive.org/web/20221206045124/https://airtame.engineering/practical-services-monitoring-with-prometheus-and-docker-30abd3cf9603?gi=b81b1156b4d9) - Practical services monitoring with Prometheus and Docker by Simon KP.
- [Prometheus Blog Series (Part 1): Metrics and Labels](https://pierrevincent.github.io/2017/12/prometheus-blog-series-part-1-metrics-and-labels/) - Part 1 in the series _Prometheus Blog Series_ by Pierre Vincent.
- [Prometheus Blog Series (Part 2): Metric types](https://pierrevincent.github.io/2017/12/prometheus-blog-series-part-2-metric-types/) - Part 2 in the series _Prometheus Blog Series_ by Pierre Vincent.
- [Prometheus Blog Series (Part 3): Exposing and collecting metrics](https://pierrevincent.github.io/2017/12/prometheus-blog-series-part-3-exposing-and-collecting-metrics/) - Part 3 in the series _Prometheus Blog Series_ by Pierre Vincent.
- [Prometheus Blog Series (Part 4): Instrumenting code in Go and Java](https://pierrevincent.github.io/2017/12/prometheus-blog-series-part-4-instrumenting-code-in-go-and-java/) - Part 4 in the series _Prometheus Blog Series_ by Pierre Vincent.
- [Horizontal Pod Autoscaling in Kubernetes with Prometheus](https://livewyer.io/blog/2019/05/28/horizontal-pod-autoscaling/) - Horizontal Pod Autoscaling in Kubernetes with Prometheus by Louise.
- [PromQL tutorial for beginners](https://medium.com/@valyala/promql-tutorial-for-beginners-9ab455142085) - PromQL tutorial for beginners by Aliaksandr Valialkin.
- [Prometheus storage: technical terms explained](https://medium.com/@valyala/prometheus-storage-technical-terms-for-humans-4ab4de6c3d48) - Prometheus storage: technical terms for humans by Aliaksandr Valialkin.
- [Alerting issues with Alertmanager](https://ali.sattari.me/posts/2020/alerting-issues-with-alertmanager/) - Addressing alert flapping and duplicates in Alertmanager by [Ali Sattari](https://github.com/ali-sattari).
- [Contributing to Prometheus](https://atibhiagrawal.medium.com/contributing-to-prometheus-2bf35bd28256) - Contributing to Prometheus by Atibhi Agrawal.
- [Simple Prometheus queries for metrics inspection](https://mkaz.me/blog/2023/simple-prometheus-queries-for-metrics-inspection/) - Overview of PromQL queries that help to identify high cardinality metrics by Michal Kazmierczak.
- [Learn Prometheus](https://pagertree.com/learn/prometheus) - A crash course of Prometheus by PagerTree LLC.

## Deployment tools
- [Ansitheus](https://github.com/ntk148v/ansitheus) - Ansible playbook to containerize, configure and deploy Prometheus ecosystem _by ntk148v_.
- [Cloud Alchemy Ansible roles](https://github.com/cloudalchemy) - Ansible roles to manage Prometheus, Alertmanager, Grafana, and common Prometheus exporters.
- [Ansible-prometheus](https://github.com/ernestas-poskus/ansible-prometheus) - Ansible playbook for installing Prometheus monitoring system, exporters such as: node, snmp, blackbox, thus alert manager and push gateway _by Ernestas Poskus_.
- [Click-to-deploy Prometheus](https://github.com/GoogleCloudPlatform/click-to-deploy/tree/master/k8s/prometheus) - Source for Google Click to Deploy Prometheus solutions listed on Google Cloud Marketplace _by GoogleCloudPlatform_.
- [Prometheus Operator](https://github.com/coreos/prometheus-operator) - Prometheus Operator creates/configures/manages Prometheus clusters atop Kubernetes _by CoreOS_.

## Dashboards
- [Grafana](https://prometheus.io/docs/visualization/grafana/) - Grafana is an open-source metric analytics & visualization suite _tutorial by Prometheus_.
- [Prometheus Monitoring with Grafana](http://logz.io/blog/prometheus-monitoring/) - Prometheus Monitoring with Grafana _tutorial by logz.io_.

## Exporters
The lists below contain all the official Prometheus exporters that are maintained by the [Prometheus GitHub organization](https://github.com/prometheus). For a complete list of exporters including any non-official exporters see [prometheus.io](https://prometheus.io/docs/instrumenting/exporters/) or [exporterhub.io](https://exporterhub.io) for a curated list of Prometheus exporters.

### Databases
- [Consul exporter](https://github.com/prometheus/consul_exporter) - The exporter for Consul metrics.
- [Memcached exporter](https://github.com/prometheus/memcached_exporter) - The Memcached exporter periodically scrapes Memcached stats.
- [MySQL server exporter](https://github.com/prometheus/mysqld_exporter) - The MySQL server exporter periodically scrapes MySQL stats.

### Hardware related
- [Node/system metrics exporter](https://github.com/prometheus/node_exporter) - The Node exporter periodically scrapes system stats.

### HTTP
- [HAProxy exporter](https://github.com/prometheus/haproxy_exporter) - The HAProxy exporter periodically scrapes HAProxy stats.

### Other monitoring systems
- [AWS CloudWatch exporter](https://github.com/prometheus/cloudwatch_exporter) - The exporter for Amazon AWS CloudWatch metrics.
- [Collectd exporter](https://github.com/prometheus/collectd_exporter) - The exporter for Collectd metrics.
- [Graphite exporter](https://github.com/prometheus/graphite_exporter) - The exporter for Graphite metrics.
- [InfluxDB](https://github.com/prometheus/influxdb_exporter) - The exporter for InfluxDB metrics.
- [JMX exporter](https://github.com/prometheus/jmx_exporter) - The exporter for JMX metrics.
- [SNMP exporter](https://github.com/prometheus/snmp_exporter) - The exporter for SNMP metrics.
- [StatsD exporter](https://github.com/prometheus/statsd_exporter) - The exporter for StatsD metrics.

### Miscellaneous
- [Blackbox](https://github.com/prometheus/blackbox_exporter) - The Blackbox exporter allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP and ICMP.

## Alertmanager
- [Monitoring mixins](https://monitoring.mixins.dev) - Community managed bundles of alerts, recording rules, and Grafana dashboards.
- [Awesome Prometheus Alerting Rules](https://github.com/samber/awesome-prometheus-alerts) - Awesome List of Prometheus alerting rules.
- [Karma](https://github.com/prymitive/karma) - Alert dashboard for Prometheus Alertmanager.

## Proxies
- [Multi-prometheus proxy](https://github.com/matt-deboer/mpp) - Forwards incoming requests to one of a set of multiple Prometheus instances deployed as HA duplicates of each other using a selector strategy.
- [Promxy](https://github.com/jacksontj/promxy) - Deduplicates data from Prometheus HA pairs.
- [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy/cache for HTTP applications and a dashboard query accelerator for time series databases.
- [exporter_proxy](https://github.com/mrichar1/exporter_proxy) - A tiny, simple pure-python reverse-proxy for Prometheus exporters, with TLS support.
- [PromQL Guard](https://github.com/kfdm/promql-guard) - Provides a thin proxy on top of Prometheus, that allows PromQL queries to be inspected and re-written, so that a tenant can only see allowed data, even when using a shared Prometheus server.
- [Pushgateway Exporter](https://github.com/oboroworks/pushgateway-exporter) - Make *pushgateway* services notifications available for probing as in Blackbox Exporter.

## High Availability
- [Cortex](https://github.com/cortexproject/cortex) - Horizontally scalable, highly available, multi-tenant, long-term Prometheus.
- [Thanos](https://github.com/thanos-io/thanos) - Highly available Prometheus setup with long term storage capabilities.
- [M3DB](https://github.com/m3db/m3) - Scalable long-term remote storage for Prometheus.
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - Cost-effective easy to operate remote storage for Prometheus.

## Uncategorized
- [Prometheus Monitoring subreddit](https://www.reddit.com/r/PrometheusMonitoring/) - Subreddit collecting all Prometheus-related resources on the internet.
- [PromCon](https://promcon.io/) - The Prometheus conference.
