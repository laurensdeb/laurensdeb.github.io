---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BSc. Computer Science, Ghent University, 2017-2020
* MSc. Computer Science, 2020-2022 (expected)

Work experience
======

## Summer 2020: Software Engineer (Internship)
**Informatie Vlaanderen** (Flemish Government)

During this summer internship I worked as a developer on the modernisation team for Informatie Vlaanderen’s MAGDA platform, a few of the cases I worked on:

* Modernisation and re-writing of common libraries using the Spring Boot framework.
* Automation of status page updates for the MAGDA platform using Spring Cloud Kubernetes and the StatusPage.io API.
* Improving high-level documentation on the modernisation efforts of MAGDA
* Implementation of an OAuth API client for our integration testing project.
* Development of a proof-of-concept service for connecting MAGDA to Solid data pods.

## Summer 2019: Software Engineer (Internship)
**Informatie Vlaanderen** (Flemish Government)

Over the course of the summer I worked on the modernisation effort of Informatie Vlaanderen’s MAGDA platform. On the project I was responsible for porting a number of existing libraries to JDK 11 and Spring Boot and aiding development of a new Business Service for the platform. Alongside a team of experienced architects and developers, I also reworked our Audit Logging technology stack using RabbitMQ and Spring’s AMQP integration to provide optimised asynchronous logging for our new business services with use of Spring Boot starters to facilitate future integration in new projects. I also helped deliver an automated post-deployment integration testing suite with Slack and JFrog Artifactory integration to automatically publish integration test reports for new builds.

Technologies used:
* JDK 11
* Spring & Spring Boot
* RabbitMQ
* Kubernetes
* Docker
* Maven
* Cucumber BDD-testing
* BitBucket Pipelines

## Summer 2018: Information Management (Internship)
**Informatie Vlaanderen** (Flemish Government)

Over the course of the summer I participated in redesigning and rewriting the technical documentation of the MAGDA platform. I also developed internal tooling and templating to facilitate the documentation process and developed a new application for managing metadata on the API services of Informatie Vlaanderen.
  
Skills
======
* Git
* JavaScript
  - Node.JS
  - React
  - TypeScript
  - Express.JS
* Java
  - JavaFx
  - Spring (Boot)
  - Maven
  - Cucumber BDD testing
* Docker
* Kubernetes
* Python (Numpy, Pandas, TensorFlow, Keras, PyTorch)
* CI/CD
  - Jenkins
  - Bitbucket Pipelines
  - SonarQube
* Rust
* HTML
* CSS


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
