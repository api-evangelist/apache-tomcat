# Apache Tomcat (apache-tomcat)

Apache Tomcat is an open-source implementation of the Java Servlet, JavaServer Pages (JSP), Java Expression Language, and Java WebSocket technologies. It provides a pure Java HTTP web server and servlet container for hosting Java web applications. Tomcat exposes management APIs via the Manager application (HTTP text protocol), JMX for monitoring, and a Virtual Host Manager for configuration management. It is maintained by the Apache Software Foundation and is one of the most widely deployed Java application servers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-tomcat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-tomcat/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Server
- Java
- JSP
- Open Source
- Servlet
- Web Server

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Apache Tomcat Manager API

The Tomcat Manager application provides an HTTP text protocol API for deploying, undeploying, starting, stopping, and reloading web applications remotely. Key endpoints include: /manager/text/list (list deployed apps), /manager/text/deploy (deploy a WAR file), /manager/text/undeploy, /manager/text/start, /manager/text/stop, /manager/text/reload, /manager/text/sessions (session statistics), and /manager/text/serverinfo. Requires manager-script role authentication.

- **Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)

#### Tags

- Administration
- Deployment
- Management
- REST

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html)
- [Postman Collection](collections/apache-tomcat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-tomcat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Tomcat JMX API

The Tomcat JMX API exposes management and monitoring beans for Connectors, Engines, Hosts, Contexts, Sessions, DataSources, thread pools, and memory via Java Management Extensions. JMX can be accessed via JConsole, Java VisualVM, or remote JMX clients. Prometheus JMX Exporter can expose Tomcat metrics in Prometheus format via HTTP endpoint.

- **Human URL:** [https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html](https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html)

#### Tags

- JMX
- Monitoring
- Management
- Java

#### Properties

- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html)
- [Postman Collection](collections/apache-tomcat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-tomcat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/tomcat)
- [Documentation](https://tomcat.apache.org/tomcat-10.1-doc/)
- [Portal](https://tomcat.apache.org/)
- [Getting Started](https://tomcat.apache.org/tomcat-10.1-doc/setup.html)
- [Release Notes](https://tomcat.apache.org/tomcat-10.1-doc/changelog.html)
- [Support](https://tomcat.apache.org/lists.html)
- [Terms of Service](https://www.apache.org/licenses/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
