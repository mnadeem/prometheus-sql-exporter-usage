# Prometheus SQL Exporter

![](docs/img/sql-exporter-design.png)

### Deployment Strategy

![](docs/img/sql-exporter.png)

Execute `docker-compose up`

````bash
E:\githubRepos\prometheus-sql-exporter-usage>docker-compose up
Starting prometheus-sql-exporter-usage_postgres_1        ... done
Starting prometheus-sql-exporter-usage_mssql_1           ... done
Starting prometheus-sql-exporter-usage_mysql_1           ... done
Starting prometheus-sql-exporter-usage_prometheus_1      ... done
Starting prometheus-sql-exporter-usage_volume_exporter_1 ... done
Starting prometheus-sql-exporter-usage_sql_exporter_1    ... done
Starting prometheus-sql-exporter-usage_grafana_1         ... done
````

### Metrics endpoint

![](docs/img/metrics.png)

### Prometheus

![](docs/img/metrics_prom.png)

### Grafana

![](docs/img/metrics_grafana.png)


# Connecting To DBs

All Connections

![](docs/img/all-connections.png)

## MSSQL

![](docs/img/mssql.png)

## Postgresql

![](docs/img/postgres.png)

## MySQL

![](docs/img/mysql1.png)

![](docs/img/mysql2.png)