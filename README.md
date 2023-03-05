## Cloud-Native-101

**NOTE:**
* View Day-1 in `main` branch.
* View Day-2 in `node-exporter` branch.

* Prometheus official website: https://prometheus.io/
* Prometheus official documentation: https://prometheus.io/docs/introduction/overview/
* CAdvisor, Prometheus, Redis Setup: https://prometheus.io/docs/guides/cadvisor/

NOTE: Use my docker-compose.yml file to setup Prometheus, Grafana and CAdvisor.

* How zerodha uses Prometheus: https://zerodha.tech/blog/infra-monitoring-at-zerodha/
* How Uber using microservices: https://www.uber.com/en-IN/blog/microservice-architecture/
* Sysdig Prometheus: https://sysdig.com/blog/redis-prometheus/
* Thanos: https://thanos.io/
* Grafana: https://grafana.com/

* Grafana Dashboard: https://grafana.com/grafana/dashboards

* Grafana Node Exporter Dashboard: https://grafana.com/grafana/dashboards/1860

* Login to Grafana: http://localhost:3000
* Login to Prometheus: http://localhost:9090/graph
* Login to CAdvisor: http://localhost:8080

* Grafana Credentials: admin/admin

### How to setup?

* Clone the repo: `git clone <repo>`
* Run `docker-compose up` to start the containers.
* Run `docker-compose down` to stop the containers.

* Always see the logs of the containers: `docker-compose logs -f`






