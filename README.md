Ansible-Prometheus
=========

Installs the Prometheus monitoring server, the node_exporter binary and the PromDash dashboard. Runs them as Upstart services.

Role Variables
--------------

```yml
prometheus_version: v2.0.0-rc.2
prometheus_link: 2.0.0-rc.2
node_exporter_version: v0.15.0
node_exporter_link: 0.15.0
prometheus_root_dir: /opt/prometheus
prometheus_config_dir: /etc/prometheus
prometheus_server_dir: "{{ prometheus_root_dir }}/prometheus-server"
prometheus_bin_dir: "{{ prometheus_root_dir }}/bin"
prometheus_dist_dir: "{{ prometheus_root_dir }}/dist"
prometheus_db_dir: "{{ prometheus_root_dir }}/databases" 
prometheus_host_domain_name: prometheus.branchmessenger.com
inventory_hostname: prometheus.branchmessenger.com
```
