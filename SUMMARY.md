# Summary

* [Introduction](README.adoc)
* [License](license.adoc)
* Getting Started
   * [Introducing WildFly Swarm](getting-started/basics.adoc)
       * [Concepts and Terminology](getting-started/concepts.adoc)
   * [System Requirements](getting-started/system_requirements.adoc)
   * [Developing your first application](first-steps/index.adoc)
       * [Maven pom.xml](first-steps/maven_pom.adoc)
       * [Adding application code](first-steps/writing_code.adoc)
       * [Running the application](first-steps/running_the_app.adoc)
* Using WildFly Swarm
   * [Build System](getting-started/_build_system.adoc)
       * [Maven](getting-started/tooling/maven-plugin.adoc)
           * [Advanced](getting-started/tooling/plugin_advanced.adoc)
       * [Gradle](getting-started/tooling/gradle-plugin.adoc)
       * Application Bootstrap
           * [Container](getting-started/container.adoc)
           * [Deployments using ShrinkWrap](getting-started/shrinkwrap.adoc)
           * Packaging Types
               * [WAR](getting-started/war-applications.adoc)
               * [JAR](getting-started/jar-applications.adoc)
       * [Configuration](configuration/index.adoc)
           * [System Properties](configuration_properties.adoc)
           * [Command line arguments](configuration/command_line.adoc)
           * [Using the Java API](configuration/java_api.adoc)
           * [Project Stages](configuration/project_stages.adoc)
           * [Using XML](configuration/using_xml.adoc)
       * Testing your application
           * [Using Arquillian](testing/arquillian.adoc)
* Features (Fractions)
   * Logging
       * [Logging](common/logging.adoc)
       * [Logstash](advanced/logstash.adoc)
       * [FluentD](advanced/fluentd.adoc)
   * Data Access
       * [JPA](common/jpa.adoc)
       * [Datasources](common/datasources.adoc)
       * [Flyway](advanced/flyway.adoc)
       * [NoSQL](common/nosql.adoc)
   * REST/HTTP
       * [JAX-RS](common/jax-rs.adoc)
       * [Swagger](advanced/swagger.adoc)
   * [Dependency Injection](common/weld_cdi.adoc)
   * [Messaging](common/messaging.adoc)
   * Web
       * [JSF](common/jsf.adoc)
   * Security
       * [Security Realms](security/realms.adoc)
       * [Single Sign On](security/keycloak.adoc)
       * [Keycloak Server](security/keycloak_server.adoc)
   * Stability Patterns
       * [Circuit Breaker](common/netflixoss.adoc)
   * Reactive
       * [Integration with Vert.x](reactive/vertx.adoc)
   * [Service Discovery](advanced/topology.adoc)
       * [Multicast discovery](topology/jgroups.adoc)
       * [Integration with Consul](topology/consul.adoc)
       * [Javascript API](topology/topology_webapp.adoc)
   * Transactions
       * [JTA/JTS](common/transactions.adoc)
       * [STM](advanced/stm.adoc)
   * [Spring](common/spring.adoc)
   * Management
       * [Remote Access](advanced/management.adoc)
       * [Jolokia](advanced/jolokia.adoc)
   * Monitoring
       * [Health Checks](advanced/monitoring.adoc)
       * [Distributed Tracing](advanced/tracing-zipkin.adoc)
   * Clustering
       * [JGroups](advanced/jgroups.adoc)
       * [Infinispan](advanced/infinispan.adoc)
* Tools
   * [Forge Add-on](getting-started/tooling/forge-addon.adoc)
   * [SwarmTool](getting-started/tooling/swarmtool.adoc)
* [Pre-built Servers](servers.adoc)
   * [MicroProfile](server/microprofile.adoc)
   * [Keycloak Server](server/keycloak.adoc)
   * [Swagger UI](server/swagger_ui.adoc)
   * [Management Console](server/management-console.adoc)
* [Additional Reading](reading.adoc)
* Getting Involved
   * [Contributing to WildFly Swarm](getting_involved.adoc)
   * [Implementation Details](implementation_details.adoc)
   * [Fraction Authoring](fraction_authoring.adoc)
