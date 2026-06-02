# holbertonschool-system_engineering-devops

System engineering and DevOps projects from Holberton School.

## Projects

### [web_infrastructure_design](./web_infrastructure_design)

Whiteboard design exercises building up a web infrastructure for
`www.foobar.com`, from a single server to a scaled, secured, and monitored
multi-tier architecture.

| Task | File | Description |
|------|------|-------------|
| 0 | [0-simple_web_stack](./web_infrastructure_design/0-simple_web_stack) | One-server LAMP-style stack (Nginx, application server, code base, MySQL) reachable via a domain name. |
| 1 | [1-distributed_web_infrastructure](./web_infrastructure_design/1-distributed_web_infrastructure) | Three-server setup: HAProxy load balancer in front of two app servers with a MySQL Primary-Replica cluster. |
| 2 | [2-secured_and_monitored_web_infrastructure](./web_infrastructure_design/2-secured_and_monitored_web_infrastructure) | Adds firewalls, HTTPS via an SSL certificate, and monitoring clients. |
| 3 | [3-scale_up](./web_infrastructure_design/3-scale_up) | Splits web, application, and database onto dedicated servers and clusters the load balancers. |

Each file contains an ASCII diagram of the architecture and written
explanations of the design choices, the role of every component, and the
issues with the infrastructure.

## Author

Yasi Philippe
