# Apache Tomcat (apache-tomcat)
Apache Tomcat is an open-source implementation of the Java Servlet, JavaServer Pages (JSP), Java Expression Language, and Java WebSocket technologies. It is one of the most widely deployed Java application servers, hosting Java web applications and REST API backends.

**URL:** [https://tomcat.apache.org/](https://tomcat.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Application Server, Java, JSP, Open Source, Servlet, Web Server

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Apache Tomcat Manager API
HTTP text protocol API for deploying, undeploying, starting, stopping, and reloading web applications remotely via the Tomcat Manager application.

**Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)

#### Tags:

 - Administration, Deployment, Management, REST

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)

### Apache Tomcat JMX API
JMX management and monitoring beans for Connectors, Engines, Hosts, Contexts, Sessions, DataSources, and thread pools.

**Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html](https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html)

#### Tags:

 - JMX, Monitoring, Management, Java

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/tomcat)
- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/)
- [Portal](https://tomcat.apache.org/)
- [GettingStarted](https://tomcat.apache.org/tomcat-10.1-doc/setup.html)
- [ReleaseNotes](https://tomcat.apache.org/tomcat-10.1-doc/changelog.html)
- [Support](https://tomcat.apache.org/lists.html)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Servlet Container | Jakarta Servlet 6.0 compliant servlet container. |
| JSP Engine | JavaServer Pages compiler and runtime engine. |
| WebSocket Support | Jakarta WebSocket 2.1 for full-duplex browser-server communication. |
| HTTP/2 Support | HTTP/2 multiplexing and server push via APR/Native connector. |
| SSL/TLS Termination | Built-in SSL/TLS support via JSSE or APR/OpenSSL connectors. |
| Connection Pooling | DBCP2-based database connection pool management via JNDI DataSource. |
| Clustering | Session replication across Tomcat cluster nodes. |

## Use Cases

| Name | Description |
|------|-------------|
| Java Web Application Hosting | Deploy and host Java Servlet/JSP web applications. |
| API Gateway Backend | Host REST API backends built with Spring MVC or JAX-RS. |
| Microservices Container | Embedded Tomcat in Spring Boot for microservices deployment. |
| Legacy Application Migration | Host Java EE applications during cloud migration. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Boot | Embedded Tomcat as the default servlet container in Spring Boot. |
| Apache HTTP Server | mod_jk and mod_proxy_ajp for load balancing between Apache httpd and Tomcat. |
| Nginx | Nginx reverse proxy for Tomcat with SSL termination and load balancing. |
| Prometheus | JMX Exporter for exposing Tomcat metrics in Prometheus format. |
| Docker | Official Docker image for containerized Tomcat deployment. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
