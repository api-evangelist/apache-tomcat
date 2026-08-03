# Apache Tomcat (apache-tomcat)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
