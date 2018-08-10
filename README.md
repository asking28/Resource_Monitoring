# Resource_monitoring
Resource monitoring with Prometheus, Alertmanager, Grafana, node_exporter, tomcat_exporter and mongodb_exporter.
# Prometheus
Prometheus is a powerful, open-source monitoring system that collects metrics from your services and stores them in a time-series database. It offers a multi-dimensional data model, a flexible query language, and diverse visualization possibilities through tools like Grafana.
By default, Prometheus only exports metrics about itself (e.g. the number of requests it's received, its memory consumption, etc.). But, you can greatly expand Prometheus by installing exporters, optional programs that generate additional metrics.
Exporters — both the official ones that the Prometheus team maintains as well as the community-contributed ones — provide information about everything from infrastructure, databases, and web servers to messaging systems, APIs, and more.

## Components
- node_exporter - This produces metrics about infrastructure, including the current CPU, memory and disk usage, as well as I/O and network statistics, such as the number of bytes read from a disk or a server's average load.
- blackbox_exporter - This generates metrics derived from probing protocols like HTTP and HTTPS to determine endpoint availability, response time, and more.
- mysqld_exporter - This gathers metrics related to a MySQL server, such as the number of executed queries, average query response time, and cluster replication status.
- rabbitmq_exporter - This outputs metrics about the RabbitMQ messaging system, including the number of messages published, the number of messages ready to be delivered, and the size of all the messages in the queue.<br/>
- nginx-vts-exporter - This provides metrics about an Nginx web server using the Nginx VTS module, including the number of open connections, the number of sent responses (grouped by response codes), and the total size of sent or received requests in bytes.<br/>
Source- https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-on-ubuntu-16-04 
Recommended- We can add new user and add ownership of Prometheus to it (For security Purposes).

## Check out Wiki Page
