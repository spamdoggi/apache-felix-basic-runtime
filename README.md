apache-felix-basic-runtime
==========================

A Maven driven pre-configured Apache Felix Runtime for ready-to-use


This repository provides a basic pom.xml which is useful as a quick-start for OSGi development.
All Maven Artifacts should be available from mvnrepository.com. This Projects consists of following Components:

- Apache Felix Runtime
- Apache Felix GoGo Shell
- Apache Felix Webconsole
- Pax Web (Jetty) as HTTP Service Implementation (for Felix Webconsole)
- Pax Logging (with a basic ready to use configuration in configurations/services/org.ops4j.pax.logging.properties)
- Pax URL for easy loading OSGi Projects from your IDE

This Content based on this Guide:

http://maksim.sorokin.dk/it/2011/07/19/maven-apache-felix-easy-development-and-debugging-with-eclipse

I suggest you to read this Guide, to configure your Eclipse IDE for starting Felix straight out your IDE.
