FROM grafana/grafana

COPY datasources.yml /etc/grafana/provisioning/datasources/
COPY dashboards.yml /etc/grafana/provisioning/dashboards/
COPY dashboards/. /var/lib/grafana/dashboards/
