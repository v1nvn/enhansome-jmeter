# Awesome JMeter [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<!--lint ignore double-link-->

A curated collection of resources covering [Apache JMeter](https://jmeter.apache.org/) and related stuff and shiny things: plugins, integrations, testing techniques, DevOps practices, etc.

<!--lint ignore double-link match-punctuation -->

[<img src="assets/images/jmeter-logo.svg" align="right" width="260" alt="Apache JMeter">](https://jmeter.apache.org/)

<!--lint ignore double-link-->

> [Apache JMeter](https://jmeter.apache.org/) is open source, pure Java application designed to load test functional behavior and measure performance.

<!--lint ignore double-link-->

This list grew up from [an occasional answer](https://sqa.stackexchange.com/a/2552/1842) on Stack Exchange and personal JMeter-related links collection, got further inspiration from [awesome](https://github.com/sindresorhus/awesome) ⭐ 436,589 | 🐛 68 | 📅 2026-01-28 project and improved by these [amazing contributors](origin/CONTRIBUTORS.md).

## Contents

<!--lint ignore double-link-->

* [Official Resources](#official-resources)
* [Distributions](#distributions)
* [Getting Started](#getting-started)
* [Tutorials](#tutorials)
* [Best Practices](#best-practices)
* [Scripting](#scripting)
* [Automation](#automation)
  * [DSL](#dsl)
  * [Packages](#packages)
  * [Frameworks](#frameworks)
  * [Conversion](#conversion)
* [CI](#ci)
  * [Tools & Plugins](#tools--plugins)
  * [Tutorials & Demo](#tutorials--demo)
* [Distributed Testing](#distributed-testing)
* [Cloud Services / SaaS](#cloud-services--saas)
* [Results Processing](#results-processing)
  * [Results Analysis](#results-analysis)
  * [Reporting & Visualization](#reporting--visualization)
* [Performance Testing](#performance-testing)
  * [Streaming Protocols](#streaming-protocols)
  * [Mobile Apps](#mobile-apps)
  * [Mainframe Environments](#mainframe-environments)
  * [RPC Frameworks](#rpc-frameworks)
  * [RESTful API](#restful-api)
* [Tools](#tools)
  * [Plugins](#plugins)
  * [Correlation](#correlation)
  * [Extending JMeter](#extending-jmeter)
  * [IDE Integration](#ide-integration)
  * [Editors](#editors)
  * [Utilities](#utilities)
* [APM Integration](#apm-integration)
* [JMeter Performance](#jmeter-performance)
* [Tips & Tricks](#tips--tricks)
* [Books](#books)
* [Trainings & Courses](#trainings--courses)
* [Videos](#videos)
* [Community](#community)
  * [Blogs](#blogs)
  * [Forums](#forums)
  * [Twitter](#twitter)
  * [Q\&A](#qa)
* [Related](#related)
  * [Awesome Lists](#awesome-lists)
  * [Other](#other)

## Official Resources

<!--lint ignore double-link-->

* [Apache JMeter Project](https://jmeter.apache.org/) - Apache JMeter official website.
* [GitHub Repository](https://github.com/apache/jmeter) ⭐ 9,222 | 🐛 940 | 🌐 Java | 📅 2026-01-12 - Apache JMeter source code repository.
* [JMeter Wiki](https://cwiki.apache.org/confluence/display/jmeter) - Apache JMeter official documentation.
* [Issue Tracking](https://jmeter.apache.org/issues.html) - Apache JMeter issue tracking system.
* [Mailing Lists](https://jmeter.apache.org/mail2.html) - Apache JMeter mailing lists.

## Distributions

* [Download Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) - Apache JMeter: Official downloads.
* [JMeter for Windows](https://sourceforge.net/projects/jmeterforwindows/) - Package for installation JMeter with plugins.
* [JMeter Bootstrap](https://github.com/cfpb/jmeter-bootstrap) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2019-04-22 - Solution to setup JMeter and JMeter plugins, suitable to be used as a submodule.

## Getting Started

* [Getting Started with Apache JMeter](https://dzone.com/refcardz/getting-started-with-apache-jmeter)
* [The Beginner's Guide to Performance Testing with Apache JMeter](https://medium.com/better-programming/the-beginners-guide-to-performance-testing-with-apache-jmeter-5cc52c327ff6)
* JMeter — Performance and Load Testing: Beginner's Guide: [part 1](https://ekremkurt1907.medium.com/jmeter-performance-and-load-testing-beginners-guide-part-i-5121604bf97a), [part 2](https://ekremkurt1907.medium.com/jmeter-performance-and-load-testing-beginners-guide-part-ii-7edb98b0d2c3)

## Tutorials

* [JMeter Tutorial](https://artoftesting.com/jmeter-tutorial) - By ArtOfTesting.
* Load Testing with JMeter: [part 1](https://lincolnloop.com/blog/load-testing-jmeter-part-1-getting-started/), [part 2](https://lincolnloop.com/blog/load-testing-jmeter-part-2-headless-testing-and-je/), [part 3](https://lincolnloop.com/blog/load-testing-jmeter-part-3-replaying-apache-logs/) - By Brandon Konkle.
* [JMeter Tutorial](https://www.tutorialspoint.com/jmeter/) - By Tutorials Point.
* [JMeter Tutorial for Load Testing: The Ultimate Guide](https://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html) - By Daniel Gutierrez Diez.
* [JMeter: Load Development Lifecycle](https://datacadamia.com/jmeter/lifecycle) - By DataCadamia.
* [Load Testing with Apache JMeter](https://www.digitalocean.com/community/tutorial-series/load-testing-with-apache-jmeter) - By Mitchell Anicas @ DigitalOcean.
* [JMeter Tutorial for Beginners](https://www.guru99.com/jmeter-tutorials.html) - By Guru99.
* [JMeter Tutorials](https://qaautomation.expert/2023/12/07/jmeter-tutorials/) - By QA Automation Expert.
* [Web App Load Testing Using Maven Plugins for Apache JMeter, and Analyzing the Results](https://dzone.com/articles/running-load-test-web-app-using-maven-plugins) - By Vincent DABURON.

## Best Practices

* [JMeter Official Best Practices](https://jmeter.apache.org/usermanual/best-practices.html)
* [Optimize JMeter for Large Scale Tests](https://blog.octoperf.com/optimize-jmeter-for-large-scale-tests/)
* [Concurrent, High Throughput Performance Testing with JMeter](https://howtojboss.wordpress.com/2012/07/31/concurrent-high-throughput-performance-testing-with-jmeter/)

## Scripting

* [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-jmeter) - Most popular scripting mechanisms performance comparison.
* [Testing with Groovy](https://static.packt-cdn.com/downloads/Testingwithgroovy.pdf) - Using JMeter and Groovy for load testing.

## Automation

### DSL

* [pymeter](https://github.com/eldaduzman/pymeter) ⭐ 143 | 🐛 6 | 🌐 Python | 📅 2023-12-05 - Simple JMeter performance tests API for Python.
* [jmeter-as-code](https://github.com/anasoid/jmeter-as-code) ⭐ 39 | 🐛 17 | 🌐 Java | 📅 2026-02-01 - Simple wrapper for JMeter to write and execute JMeter tests with Java.
* [jmeter-groovy-dsl](https://github.com/smicyk/groovy-jmeter) ⭐ 14 | 🐛 2 | 🌐 Groovy | 📅 2024-05-30 - The Groovy-JMeter project is simple DSL to write JMeter test plans.
* [jmeter-java-dsl](https://abstracta.github.io/jmeter-java-dsl/) - Simple Java API to run JMeter performance tests in an VCS and programmers friendly way.
* [jmeter-dotnet-dsl](https://abstracta.github.io/jmeter-dotnet-dsl/) - Simple .Net API to run JMeter performance tests in an VCS and programmers friendly way.

### Packages

* [loadtest](https://github.com/tmobile/loadtest) ⭐ 91 | 🐛 10 | 🌐 R | 📅 2020-05-06 - An R package for load testing using JMeter.

### Frameworks

* [MeterSphere](https://github.com/metersphere/metersphere) ⭐ 12,937 | 🐛 44 | 🌐 Java | 📅 2026-02-11 - One-stop open-source enterprise-class continuous testing platform, compatible with open-source standards such as JMeter :cn:.
* [Performance testing framework](https://github.com/serputko/performance-testing-framework) ⭐ 414 | 🐛 15 | 🌐 JavaScript | 📅 2023-12-19 - Framework both for backend load testing with Apache JMeter and frontend load testing with sitespeed.io + webpagetest private instance.
* [JMeter Load Testing Center](https://github.com/innogames/ltc) ⭐ 204 | 🐛 14 | 🌐 Python | 📅 2025-02-12 - Online web-application/dashboard to run, monitor and analyze results of load tests using JMeter.
* [Taurus](https://gettaurus.org/) - Automation-friendly framework for Continuous Testing.
* [Carrier](https://github.com/carrier-io) - Continuous test execution platform with ability to perform load testing using customized JMeter and Gatling containers.

### Conversion

* [postman2jmx](https://github.com/Loadium/postman2jmx) ⭐ 190 | 🐛 15 | 🌐 Java | 📅 2023-10-15 - Postman collection to JMeter jmx file converter.
* [swaggerjmx](https://github.com/Pactortester/swaggerjmx) ⭐ 115 | 🐛 1 | 🌐 Python | 📅 2023-05-15 - Tool to convert Swagger UI specification into JMeter test plans.
* [fiddler2jmeter](https://github.com/dperfly/fiddler2jmeter) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2025-07-15 - Fiddler or Charles to JMeter script convertor.
* [har-convertor-jmeter-tool](https://github.com/vdaburon/har-convertor-jmeter-plugin) ⭐ 23 | 🐛 2 | 🌐 Java | 📅 2026-02-04 - Apache JMeter Plugin to convert a HAR file to a JMeter script and Record XML file.
* [JMeter HAR Importer Plugin](https://github.com/Qytera-Gmbh/JMeterHARImporterPlugin) ⭐ 19 | 🐛 0 | 🌐 Java | 📅 2026-02-02 - JMeter plugin to import HTTP Archive (HAR) files into Apache JMeter.
* [convert-postman-jmeter](https://github.com/sercheo87/convert-postman-jmeter) ⭐ 11 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-29 - Convert Postman projects to JMeter.

## CI

### Tools & Plugins

* [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin) ⭐ 437 | 🐛 20 | 🌐 Java | 📅 2025-01-03 - Maven plugin that provides the ability to run JMeter tests as part of the build.
* [JMeter Gradle Plugin](https://github.com/jmeter-gradle-plugin/jmeter-gradle-plugin) ⭐ 51 | 🐛 43 | 🌐 Groovy | 📅 2020-11-25 - Gradle plugin to execute JMeter tests.
* [JMeter Ant Task](https://github.com/jfifield/ant-jmeter) ⭐ 27 | 🐛 1 | 🌐 XSLT | 📅 2017-07-01 - Ant task to automate running JMeter test plans.
* [TeamCity Performance Tests Analysis Plugin](https://github.com/jtorgan/jmeter_plugin) ⭐ 21 | 🐛 25 | 🌐 JavaScript | 📅 2017-07-25 - TeamCity plugin to organize simplest performance testing in CI 💀.
* [Sonar JMeter Plugin](https://github.com/SonarQubeCommunity/sonar-jmeter) ⭐ 10 | 🐛 7 | 🌐 Java | 📅 2021-01-15 - Plugin to collect JMeter performance tests results and display in Sonar dashboard 💀.
* [Jenkins Performance Plugin](https://plugins.jenkins.io/performance/) - Jenkins plugin to capture reports from JMeter and generate graphic charts with the trend report of performance and robustness.
* [Bamboo JMeter Aggregator Plugin](https://marketplace.atlassian.com/apps/5902/jmeter-aggregator-for-bamboo) - Bamboo plugin to collect, assert and graph JMeter test results.
* [Lightning](https://deliverymind.github.io/lightning/) - Framework to integrate JMeter non-functional tests with CI/CD server.
* [Taurus JMeter Executor](https://gettaurus.org/docs/JMeter/) - JMeter Executor in Taurus automation framework.
* [PerfAction for JMeter](https://github.com/marketplace/actions/perfaction-for-jmeter) - GitHub Action to run performance tests using Apache JMeter and its plugins.
* [Apache JMeter GitHub Action](https://github.com/marketplace/actions/apache-jmeter) - A GitHub Action for carrying out Apache JMeter performance tests.

### Tutorials & Demo

* Jenkins
  * [Performance Tests with JMeter, Maven and Hudson](https://medium.com/the-server-labs/performance-tests-with-jmeter-maven-and-hudson-d1cbdb3ffad8)
  * [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter) ⭐ 21 | 🐛 0 | 🌐 HTML | 📅 2015-04-08
  * [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
  * [Automating JMeter tests with Maven and Jenkins](https://www.codecentric.de/en/knowledge-hub/blog/automating-jmeter-tests-maven-jenkins)
  * How to automate JMeter tests with Maven and Jenkins: [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/), [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
  * JMeter Continuous Performance Testing (JMeter + Ant + Jenkins): [part 1](https://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/), [part 2](https://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)
  * [Continuous Integration 101: How to Run JMeter with Jenkins](https://dzone.com/articles/continuous-integration-101-how-to-run-jmeter-with)
* Bamboo
  * [How to Run JMeter in a Continuous Integration Environment with Bamboo](https://dzone.com/articles/how-to-run-jmeter-in-a-continuous-integration-envi)
* TeamCity
  * [How to Run JMeter Tests with TeamCity for Continuous Integration](https://web.archive.org/web/20211204112944/https://www.blazemeter.com/blog/how-run-jmeter-tests-teamcity-continuous-integration/)
* CircleCI
  * [How to integrate JMeter into CircleCI](https://www.blazemeter.com/blog/circleci-jmeter)
* SonarQube
  * [JMeter with Sonar](https://testersinaction.blogspot.com/2013/05/v-behaviorurldefaultvmlo_24.html)

## Distributed Testing

* Testing in Cloud
  * Amazon Web Services
    * [jmeter-ec2](https://github.com/oliverlloyd/jmeter-ec2/) ⭐ 461 | 🐛 18 | 🌐 Shell | 📅 2019-06-24 - Automates running Apache JMeter on Amazon EC2.
    * [jmeter-ecs](https://github.com/smithmicro/jmeter-ecs) ⭐ 44 | 🐛 16 | 🌐 Shell | 📅 2022-11-22 - JMeter Docker image for distributed testing on EC2 Container Service (ECS).
    * [gee](https://github.com/kowalcj0/gee) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2014-01-02 - A modified version of JMeter-EC2 project.
    * [os-jmeter-aws](https://github.com/Aptimyze/os-jmeter-aws) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-09-18 - Run JMeter on multiple Amazon EC2 instances, view results in ELK.
    * [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
    * [Performance Testing in the Cloud with JMeter & AWS](https://web.archive.org/web/20190526033436/http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
    * [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/17/jmeter-distributed-testing-with-amazon-ec2/)
  * Kubernetes
    * [jmeter-kubernetes](https://github.com/kubernauts/jmeter-kubernetes) ⭐ 366 | 🐛 22 | 🌐 Shell | 📅 2024-04-30 - JMeter cluster support for Kubernetes and OpenShift.
    * [kangal](https://github.com/hellofresh/kangal) ⭐ 172 | 🐛 21 | 🌐 Go | 📅 2026-01-29 - Kubernetes and Go Automatic Loader solution to run performance tests in Kubernetes cluster using multiple load generators.
    * [jmeter-k8s-starterkit](https://github.com/Rbillon59/jmeter-k8s-starterkit) ⭐ 91 | 🐛 0 | 🌐 Shell | 📅 2025-04-24 - JMeter Kubernetes starter kit, with live test reporting, JMeter monitoring, Kubernetes monitoring and mock as a service.
    * [aks\_testing\_fwk](https://github.com/petegrimsdale/aks_testing_fwk) ⭐ 37 | 🐛 1 | 🌐 Shell | 📅 2020-08-24 - AKS-based scalable JMeter test framework with Grafana reporting.
  * Microsoft Azure
    * [Load Testing Pipeline with JMeter, ACI and Terraform](https://github.com/Azure-Samples/jmeter-aci-terraform) ⚠️ Archived - Scalable cloud load/stress testing pipeline solution with Apache JMeter and Terraform to dynamically provision and destroy the required infrastructure on Azure.
  * DigitalOcean
    * [Lightweight JMeter Cloud](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/) - Building your own JMeter Cloud using DigitalOcean, JMeter and Docker.
* Dockerized
  * [AutoMeter](https://github.com/intuit/autometer) ⭐ 60 | 🐛 0 | 🌐 Shell | 📅 2019-07-08 - An automation tool for scaling load tests using distributed slaves, based on JMeter master-slave architecture.
  * [Dockerized JMeter](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b) - Distributed load testing workflow with Docker and JMeter.
  * [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0\&isOfficial=0\&page=1\&pullCount=0\&q=jmeter\&starCount=0)
  * [Distributed JMeter testing using Docker](https://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
  * [A Docker solution to JMeter + InfluxDB + Grafana performance testing](https://medium.com/@ellenhuang523/a-docker-solution-to-jmeter-influxdb-grafana-performance-testing-568848de7a0f)
  * [JMeter Docker Extension](https://hub.docker.com/extensions/qainsights/jmeter-docker-extension) - Docker extension to run JMeter tests from Docker Desktop.
* [JMeter Distributed Testing Step-by-step](https://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
* [JMeter Remote Testing](https://jmeter.apache.org/usermanual/remote-test.html)
* [Setting up a JMeter Cluster for web server load testing](https://www.howtoforge.com/setting-up-jmeter-cluster-for-load-testing/)

## Cloud Services / SaaS

*List of cloud-based load testing services with support of JMeter test plans execution.*

* [Perforce BlazeMeter](https://www.blazemeter.com/) - Performance engineering platform with JMeter and Selenium support.
* [OctoPerf](https://octoperf.com/) - SaaS and On-Premise Load Testing Tool with JMeter and Selenium support.
* [RedLine13](https://redline13.com/) - AWS-based load testing service with JMeter, Gatling and Selenium scenarios support.
* [OpenText Core Performance Engineering](https://www.opentext.com/products/saas/core-performance-engineering) - OpenText cloud-based solution for web and mobile performance testing with JMeter and Gatling support (formerly Micro Focus LoadRunner Cloud, formerly HP StormRunner Load).
* [Loadium](https://loadium.com/) - AWS-based load testing service with JMeter and Selenium support.
* [Azure Microsoft](https://azure.microsoft.com/en-us/products/load-testing/) - Azure Load Testing Service use Apache JMeter.

## Results Processing

* [JMeter Report Dashboard](https://jmeter.apache.org/usermanual/generating-dashboard.html) - JMeter supports dashboard report generation to get graphs and statistics from a test plan.
* [Latency Lingo](https://latencylingo.com) - Publish test results to generate hosted, interactive dashboards containing insights.

### Results Analysis

<!--lint ignore double-link-->

* [JtlReporter](https://github.com/ludeknovy/jtl-reporter) ⭐ 151 | 🐛 1 | 🌐 Python | 📅 2025-07-16 - Online reporting application to generate reports by uploading JTL file.
* [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin) ⚠️ Archived - Maven plugin that parses JMeter test results and generates detailed reports with charts.
* SLA and KPIs
  * [JMeter SLA Report](https://github.com/sgoeschl/jmeter-sla-report) ⭐ 39 | 🐛 1 | 🌐 HTML | 📅 2021-04-23 - JMeter HTML report generator based on JAMon.
  * [JMeter JUnit Reporter](https://github.com/tilln/jmeter-junit-reporter) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2025-10-03 - Apache JMeter plugin for generating JUnit Reports in XML format, based on custom KPIs (Key Performance Indicators).
  * Tools to validate results from KPIs:
    * [JUnit KPI Reporter from JMeter Dashboard Statistics JSON File](https://github.com/vdaburon/JUnitReportKpiJMeterDashboardStats) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2025-04-25 - Tool to generate JUnit Report based on custom KPIs applied to the JMeter Dashboard Statistics JSON file.
    * [JUnit Report Compare 2 JMeter Report CSV Files](https://github.com/vdaburon/JUnitReportKpiCompareJMeterReportCsv) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2025-04-25 - Tool to compare 2 load tests using JMeter Report CSV files and create a JUnit Report based on custom KPIs.
    * [JUnit KPI Reporter from JMeter CSV Report](https://github.com/vdaburon/JUnitReportKpiJMeterReportCsv) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2025-04-25 - Tool to generate JUnit Report based on custom KPIs applied to the JMeter Report CSV file.
* [JMeter Graph Tool Maven Plugin](https://github.com/vdaburon/jmeter-graph-tool-maven-plugin) ⭐ 11 | 🐛 0 | 🌐 Java | 📅 2024-06-07 - Maven plugin to create graphs and filter results using CMDRunner and Filter Results Tools from [JMeter Plugins](#plugins); usually used along with the [JMeter Maven Plugin](#tools--plugins) and  set of [companion plugins](https://github.com/vdaburon/jmeter-graph-tool-maven-plugin#compagnion-tools) ⭐ 11 | 🐛 0 | 🌐 Java | 📅 2024-06-07.
* [JMeter Log Analysis](https://cwiki.apache.org/confluence/display/jmeter/LogAnalysis) - Suggestions and recipes for JMeter log analysis.
* [Analyzing JMeter Results](https://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results)
* [JMeter Result Analysis: The Ultimate Guide](https://blog.octoperf.com/jmeter-result-analysis-the-ultimate-guide/)
* [JMeter Results Analyser](https://sourceforge.net/projects/jmstats/) - Web-based application for collating, analysing and reporting JMeter test results.
* DB Results Collectors
  * [JMeter DBCollector Plugin](https://sourceforge.net/projects/jmeterdbcollect/) - Plugin to enable results logging into a database for more effective reporting.
  * [JMeter MySQLCollector Plugin](https://cwiki.apache.org/confluence/display/jmeter/MysqlCollectorPlugin) - Patch to configure listener to log into MySQL database.

### Reporting & Visualization

<!--lint ignore double-link-->

* InfluxDB & Grafana
  * [InfluxDB Community Template for JMeter](https://github.com/influxdata/community-templates/tree/master/apache_jmeter) ⭐ 370 | 🐛 76 | 🌐 Python | 📅 2023-06-15 - Prepackaged InfluxDB configurations that contain everything from dashboards and Telegraf configurations to notifications and alerts in a single manifest file.
  * [JMeter-InfluxBD-Writer Plugin](https://github.com/NovatecConsulting/JMeter-InfluxDB-Writer) ⚠️ Archived - JMeter plugin to write load test data on-the-fly into InfluxDB.
  * [jmeterReports](https://github.com/kirillyu/jmeterReports) ⭐ 27 | 🐛 2 | 📅 2021-12-13 - Autogenerated JMeter test-run results reported into Confluence, using Grafana custom dashboards :ru:.
  * [JMeter Results to InfluxDB](https://github.com/soprasteria/jmeter2influxdb) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2025-04-09 - Read JMeter results from csv file and put into InfluxDB database.
  * [Using JMeter with InfluxDB & Grafana](https://blog.vinsguru.com/category/influxdb/) - Collection of guides to collect and visualize real-time test results and server monitoring stats using InfluxDB & Grafana.
  * [How to Use Grafana to Monitor JMeter Non-GUI Results](https://dzone.com/articles/how-to-use-grafana-to-monitor-jmeter-non-gui-resul)
  * Grafana Dashboards
    * [JMeter Load Test Dashboard](https://grafana.com/grafana/dashboards/1152-jmeter-load-test/) - Grafana dashboard shows live load test metrics provided by JMeter (by NovaTec-APM).
    * [JMeter Dashboard using Core InfluxdbBackendListenerClient](https://grafana.com/grafana/dashboards/5496-apache-jmeter-dashboard-by-ubikloadpack/) - Monitor your Apache JMeter load test in real time with InfluxDB and Grafana (by Philippe M).
    * [JMeter Dashboard (3.2 and up)](https://grafana.com/grafana/dashboards/3351-jmeter-3-3/) - Monitor JMeter load test in real time with InfluxDB and Grafana (by adrianbanu).
    * [JMeter (via prometheus exporter)](https://grafana.com/grafana/dashboards/2492-jmeter/) - A Grafana dashboard to inspect JMeter metrics via Prometheus exporter (by chiabre).
* Prometheus
  * [jmeter-prometheus-plugin](https://github.com/johrstrom/jmeter-prometheus-plugin) ⭐ 185 | 🐛 36 | 🌐 Java | 📅 2023-08-03 - A Prometheus Listener for Apache JMeter that exposes results in HTTP API.
  * [jmeter-prometheus-listener](https://github.com/kolesnikovm/jmeter-prometheus-listener) ⭐ 20 | 🐛 0 | 🌐 Java | 📅 2023-03-01 - Apache JMeter Backend Listener implementation for Prometheus metrics exporting.
  * [ulp-observability-plugin](https://github.com/ubikingenierie/ulp-observability-plugin) ⭐ 6 | 🐛 4 | 🌐 HTML | 📅 2023-10-13 - Allows you to monitor your JMeter CLI performance test from your favorite browser without having to start JMeter in GUI mode.
* Backend Listener Implementations
  * [jmeter-influxdb2-listener-plugin](https://github.com/mderevyankoaqa/jmeter-influxdb2-listener-plugin) ⭐ 133 | 🐛 51 | 🌐 Java | 📅 2024-08-09 - InfluxDB v2.0 listener plugin for Apache JMeter.
  * [jmeter-elasticsearch-backend-listener](https://github.com/anthonygauthier/jmeter-elasticsearch-backend-listener) ⭐ 100 | 🐛 20 | 🌐 Java | 📅 2024-03-11 - JMeter plugin to send test results to an Elasticsearch engine.
  * [jmeter-backend-azure](https://github.com/adrianmo/jmeter-backend-azure) ⭐ 32 | 🐛 7 | 🌐 Java | 📅 2023-04-21 - JMeter plugin to send test results to Azure Application Insights.
  * [jmeter-backend-listener-kafka](https://github.com/veeranalyticsltd/jmeter-backend-listener-kafka) ⭐ 32 | 🐛 6 | 🌐 Java | 📅 2022-05-20 - JMeter plugin to send test results to a Kafka server.
  * [jmeter-dynatrace-plugin](https://github.com/dynatrace-oss/jmeter-dynatrace-plugin) ⚠️ Archived - A JMeter Backend listener implementation to send the recorded load test metrics via the Dynatrace MINT metric ingest to the configured Dynatrace monitoring environment.
  * [jmeter-datadog-backend-listener](https://github.com/DataDog/jmeter-datadog-backend-listener) ⭐ 13 | 🐛 10 | 🌐 Java | 📅 2026-02-10 - Send JMeter test results to Datadog.
  * [jmeter-backend-newrelic](https://github.com/darrensmithwtc/jmeter-backend-newrelic) ⭐ 9 | 🐛 8 | 🌐 Java | 📅 2024-04-29 - A JMeter plugin to send test results to New Relic Metrics API.
  * [jmeter-listener](https://gitlab.com/testload/jmeter-listener) - JMeter plugin to write load test data on-the-fly to ClickHouse, InfluxDB, Elasticsearch.
* AWS CloudWatch
  * [jmeter-cw-logs](https://github.com/concurrencylabs/jmeter-cw-logs) ⭐ 10 | 🐛 1 | 📅 2016-10-20 - CloudFormation template for publishing JMeter test results to AWS CloudWatch Logs.
* ELK Stack
  * [jmeter-logstash](https://github.com/anasoid/jmeter-logstash) ⭐ 8 | 🐛 3 | 🌐 Shell | 📅 2026-02-03 - Parse JTL result with Docker and Logstash in real time or after test end, and send data to Elasticsearch or InfluxDB, to have a nice dashboard and compare different tests.
  * [Using ELK](https://ecmarchitect.com/archives/2014/09/09/3932) - Using Elasticsearch, Logstash, and Kibana to visualize JMeter test results.
  * [JMeter + Elasticsearch Live Monitoring](https://medium.com/@anthony.gauthier325/jmeter-elasticsearch-live-monitoring-c895c843c51e) - Using the Elasticsearch Backend listener and Grafana/Kibana to monitor results in real time.
* Custom & Deprecated
  * JMeter Dashboard: [howto](https://seangkuan.blogspot.com/2015/06/jmeter-dashboard-realtime-monitoring-of.html), [sources](https://github.com/vincentskooi/JMeterDashboard) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2015-06-05 - Real-time monitoring of JMeter load test.
  * [JChav](https://github.com/d6y/jchav) ⭐ 3 | 🐛 5 | 🌐 Java | 📅 2015-04-14 - JMeter Chart History and Visualization library.
  * [Using Matplotlib & Python](https://www.metaltoad.com/blog/plotting-your-load-test-jmeter) - Plotting JMeter load test results with Matplotlib plotting tool and Python.
  * [Statistical Aggregate Report](https://rubenlaguna.com/post/2007-01-02-better-jmeter-graphs/) - Custom Statistical Aggregate Report listener for enhanced results visualization.
  * [Using CMDRunner & Powershell](https://performancewebautoamtionother.blogspot.com/2015/12/jmeter-create-graphs-with-cmdrunner.html) - Create JMeter graphs with CMDRunner with powershell parallel execution.
* ClickHouse
  * [JMeter Results from ClickHouse](https://grafana.com/grafana/dashboards/9561-jmeter-results-from-clickhouse-eng/) - Using the [JMeter Listener pack](https://gitlab.com/testload/jmeter-listener/-/wikis/3.3-ClickHouse-usage), ClickHouse and Grafana to collect and monitor test results.
  * [jmeter-clickhouse-listener](https://gitlab.com/testload-group/jmeter-clickhouse-listener) - JMeter plugin allows to write load test data on-the-fly to ClickHouse.

## Performance Testing

### Streaming Protocols

* [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](https://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
* [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](https://web.archive.org/web/20210918113142/https://www.realeyes.com/blog/wowza-streaming/)
* [How to Test Video Streaming with JMeter](https://www.blazemeter.com/blog/video-streaming-testing)
* [HLS JMeter Plugin](https://github.com/Blazemeter/HLSPlugin) ⭐ 49 | 🐛 15 | 🌐 Java | 📅 2026-01-26

### Mobile Apps

* [Record iOS application HTTP requests](https://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
* [Load Testing Mobile Apps Made Easy](https://www.blazemeter.com/blog/mobile-app-load-testing)

### Mainframe Environments

* [JMeter RTE Plugin](https://github.com/Blazemeter/RTEPlugin) ⭐ 20 | 🐛 25 | 🌐 Java | 📅 2025-07-23 - JMeter RTE (Remote Terminal Emulator protocol) plugin for testing Mainframe applications.

### RPC Frameworks

* [JMeter Dubbo Plugin](https://github.com/thubbo/jmeter-plugins-for-apache-dubbo) ⭐ 570 | 🐛 20 | 🌐 Java | 📅 2023-09-21 - JMeter plugin for Apache Dubbo.
* [JMeter gRPC Request](https://github.com/zalopay-oss/jmeter-grpc-request) ⚠️ Archived - JMeter sampler to send an gRPC request to a server.
* [JMeter gRPC Plugin](https://github.com/zalopay-oss/jmeter-grpc-plugin) ⭐ 45 | 🐛 12 | 🌐 Java | 📅 2023-06-14 - JMeter plugin supports load test gRPC.

### RESTful API

* [REST API Testing with JMeter. Step by Step Guide](https://blog.octoperf.com/rest-api-testing-with-jmeter-step-by-step-guide/)

## Tools

### Plugins

* [JMeter Plugins](https://jmeter-plugins.org/) - Independent set of plugins for Apache JMeter, with plugin manager references many plugins and simplifies installation.
* [Ubik Load Pack](https://ubikloadpack.com/) - Productivity extensions for Apache JMeter.
* GitHub Topics: [jmeter-plugin](https://github.com/topics/jmeter-plugin), [jmeter-plugins](https://github.com/topics/jmeter-plugins) - Explore JMeter plugins tagged with the `jmeter-plugin` or `jmeter-plugins` labels.

### Correlation

<!--lint ignore double-link-->

* [Correlation Recorder Plugin](https://github.com/Blazemeter/CorrelationRecorder) ⭐ 28 | 🐛 21 | 🌐 Java | 📅 2025-04-17 - JMeter plugin that simplifies the process of recording for applications with Dynamic Variables by providing automatic correlations of variables at recording time.
* [Siebel CRM Plugin](https://github.com/Blazemeter/SiebelPlugin) ⭐ 11 | 🐛 2 | 🌐 Java | 📅 2026-01-26 - JMeter plugin to simplify the scripting of Siebel CRM applications by providing automatic correlations of variables at recording time ❄️.
* [ULP Auto-correlator Plugin](https://www.ubik-ingenierie.com/blog/ubikloadpack-autocorrelator-plugin-help/) - Commercial plugin for Oracle and Vaadin-based applications from [Ubik Load Pack](#plugins).

### Extending JMeter

* [JMeter Developer Manual](https://cwiki.apache.org/confluence/display/jmeter/DeveloperManual)
* [How to write a plugin for JMeter](https://jmeter.apache.org/usermanual/jmeter_tutorial.html)
* [How to build a JMeter plugin utilizing Groovy](https://web.archive.org/web/20180225144718/http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
* [How to create a plugin in JMeter](https://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
* [Custom JMeter Samplers and Config Elements](https://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)
* [Implement Custom JMeter Samplers](https://dzone.com/articles/implement-custom-jmeter-samplers)
* [Hello JMeter plugin](https://github.com/Bugazelle/hello-jmeter-plugin) ⭐ 21 | 🐛 1 | 🌐 Java | 📅 2024-04-08 - A brief, clear & fast guide to create your first JMeter plugin.

### IDE Integration

* [IntelliJ IDEA IDE Plugin](https://plugins.jetbrains.com/plugin/7013-jmeter-plugin) - Create run configurations and run JMeter tests from IntelliJ IDEA.
* [JMeter Viewer](https://github.com/anboralabs/intellij-jmeter) ⭐ 5 | 🐛 5 | 🌐 Java | 📅 2026-01-28 - Open JMeter test plans inside IntelliJ IDE.
* [JMeter + Eclipse HOWTO](https://cwiki.apache.org/confluence/display/jmeter/JMeterAndEclipseHowTo) - Develop the JMeter project with Eclipse IDE.
* [Using a Load Generator in NetBeans IDE](https://netbeans.apache.org/tutorial/main/kb/docs/java/profile-loadgenerator/)

### Editors

*Alternative editors for JMX files, in addition to standard JMeter GUI and XML editors.*

<!--lint ignore double-link-->

* [BlocklyJMX Editor](https://jmeter-plugins.org/editor/) - A web-based viewer and editor for JMeter test plan files (part of [JMeter Plugins](#plugins) project).
* [JEval](https://github.com/QAInsights/JEval) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2020-10-21 - A Python-based utility which evaluates JMeter test plan and provides recommendations and best practices by analyzing each element.
* [JMX Enhancer](https://www.jmxenhancer.com/) - A solution to expedite preparation of JMeter test plans.
* [jmx.js](https://www.vinodkd.org/jmx.js/) - Web-based editor for JMeter JMX files 💀.

### Utilities

* [Hamster](https://github.com/QAInsights/hamster) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-02-15 - Swiftly launch your JMeter test plans from Mac menubar.

## APM Integration

*Integration with Application Performance Monitoring (APM) tools to analyze the performance of application servers, database servers, and web services.*

<!--lint ignore double-link-->

* [Servers Performance Monitoring Plugin](https://jmeter-plugins.org/wiki/PerfMon/) - Server monitoring plugin from [JMeter Plugins](#plugins) project.
* [DX App Synthetic Monitor](https://techdocs.broadcom.com/us/en/ca-enterprise-software/it-operations-management/app-synthetic-monitor/SaaS/using/use-jmeter-scripts-to-test-web-servers.html) - Transaction monitoring & testing solution with JMeter support.
* Performance Remediation using New Relic and JMeter: [part 1](https://web.archive.org/web/20250811141928/https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-1-3/), [part 2](https://web.archive.org/web/20250809025316/https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-2-3/), [part 3](https://web.archive.org/web/20250719013947/https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-3-of-3/)
* [Elastic APM integration](https://github.com/vdaburon/jmeter-elastic-apm) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2025-01-14 - Manages the integration of Elastic Application Performance Monitoring API in Apache JMeter script.

## JMeter Performance

* [JMeter Performance](https://cwiki.apache.org/confluence/display/jmeter/JMeterPerformance) - Evolution of JMeter performance across versions.
* [JMeter Performance and Tuning Tips](https://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/) - By Ubik Ingenierie.
* How to speed up JMeter: [part 1](https://pflb.us/blog/how-to-speed-up-jmeter-part-1/), [part 2](https://pflb.us/blog/how-to-speed-up-jmeter-part-2/)

## Tips & Tricks

* [JMeter tips](https://web.archive.org/web/20221126233834/https://www.webwob.com/html/jmeter_tips.html) - Scratchpad for JMeter tips and tricks.

## Books

<!--lint ignore double-link-->

* [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](https://books.google.com/books?id=nX8oKIEvUcYC) - By Emily H. Halili (Packt Publishing).
* [Performance Testing with JMeter 2.9](https://books.google.com/books?id=fpWmv3wPT64C) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-29/9781782165842)); guide to test web applications using Apache JMeter with practical, hands-on examples.
* [Performance Testing with JMeter, 2nd Edition](https://books.google.com/books?id=6ditCAAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter/9781784394813)).
* [Performance Testing with JMeter 3, 3rd Edition](https://books.google.com/books?id=BedDDwAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-3-third-edition/9781787285774)).
* [JMeter Cookbook](https://books.google.com/books?id=gJUeBQAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/jmeter-cookbook/9781783988280)); 70 insightful and practical recipes to help successfully use Apache JMeter.
* [JMeter by Example](https://books.google.com/books?id=iWeJDAEACAAJ) - By Sai Matam and Jagdeep Jain ([Leanpub](https://leanpub.com/jmeterbyexample)); a simple, practical, step-by-step tutorial to measure the performance of websites.
* [Pro Apache JMeter: Web Application Performance Testing](https://books.google.com/books?id=YJ4xDwAAQBAJ) - By Sai Matam and Jagdeep Jain ([Apress](https://link.springer.com/book/10.1007/978-1-4842-2961-3)).
* [Master Apache JMeter: From load testing to DevOps](https://books.google.com/books?id=D_amDwAAQBAJ) - By Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/master-jmeter-from-load-test-to-devops), [Packt Publishing](https://www.packtpub.com/product/master-apache-jmeter-from-load-testing-to-devops/9781839217647)).
* [Advanced JMeter Testing](https://leanpub.com/advanced_jmeter_testing) - By Penny Curich ([Leanpub](https://leanpub.com/advanced_jmeter_testing)), guide to write custom components for Apache JMeter 5.0.

## Trainings & Courses

* [JMeter: Performance and Load Testing (Feb 2019)](https://www.linkedin.com/learning/jmeter-performance-and-load-testing) - By LinkedIn Learning.
* [Advanced JMeter (Jul 2020)](https://www.linkedin.com/learning/advanced-jmeter) - By LinkedIn Learning.
* [JMeter Training Courses](https://www.nobleprog.co.uk/cc/apachejmetertesting) - By NobleProg.
* [BlazeMeter University](https://www.blazemeter.com/university) - By BlazeMeter.
* [JMeter Courses collection](https://www.udemy.com/topic/jmeter/) - By Udemy.
* [Web Applications (and Mobile Apps) Performance Testing with JMeter](http://pragmatictestlabs.com/web-applications-mobile-apps-performance-testing-jmeter/) - By Pragmatic Test Labs.
* [Training courses on Load Testing with Apache JMeter](https://www.ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) - By Ubik Ingenierie.
* [Apache JMeter Training](https://qainsights.com/apache-jmeter-training/) - By QAInsights.
* [JMeter Getting Started Course (Apr 2019)](https://www.pluralsight.com/courses/jmeter-getting-started) - By Pluralsight.

## Videos

* [JMeter Tutorials](https://www.youtube.com/c/AutomationStepByStep/search?query=jmeter) - By Automation Step by Step.
* [Learn Apache JMeter Series](https://www.youtube.com/playlist?list=PLJ9A48W0kpRIjLkZ32Do9yDZXnnm7_uj_) - By QAInsights.
* [JMeter / Devops/ CI-CD / Cloud](https://www.youtube.com/c/xavki-linux/search?query=jmeter) - By xavki :fr:.

## Community

### Blogs

* [BlazeMeter Blog](https://www.blazemeter.com/blog) - BlazeMeter's blog about JMeter and performance testing.
* [Ubik Load Pack Blog](https://www.ubik-ingenierie.com/blog/category/jmeter/) - Ubik Ingenierie blog.
* [TestAutomationGuru Blog](https://www.testautomationguru.com/category/jmeter/) - Technical blog on test automation.
* [RedLine13 Blog](https://www.redline13.com/blog/tag/jmeter/) - JMeter articles in RedLine13 blog.
* [JMeter Blog](https://shantonusarker.blogspot.com/p/jmeter.html) - Another blog for performance & automation testing using JMeter.
* [OctoPerf Blog](https://blog.octoperf.com/categories/jmeter/) - OctoPerf's blog about JMeter and load testing.
* [Abstracta JMeter Archives](https://abstracta.us/blog/tag/jmeter/) - Abstracta blog about JMeter.
* [JMeter Basics](https://thatsabug.com/tags/#jmeter-series) - By João Farias.

### Forums

<!--lint ignore double-link-->

* [JMeterPlugins Google Group](https://groups.google.com/g/jmeter-plugins)

### Twitter

<!--lint ignore double-link-->

* [@ApacheJMeter](https://x.com/apachejmeter) - Official Twitter account of the Apache JMeter load testing tool.
* [@jmeter\_plugins](https://x.com/jmeter_plugins) - Twitter account of custom plugins project for JMeter load testing tool.
* [@BlazeMeter](https://x.com/BlazeMeter) - Official Twitter account of Blazemeter, performance engineering platform for DevOps, based on JMeter.
* [@masterjmeter](https://x.com/masterjmeter) - Official account of the [Master Apache JMeter from Load Testing to DevOps](#books) book.
* [@ubikloadpack](https://x.com/ubikloadpack) - Twitter account of [Ubik Load Pack](#plugins), custom JMeter plugins for Video Streaming & complex protocols load testing.

### Q\&A

* [`jmeter` on Stack Overflow](https://stackoverflow.com/questions/tagged/jmeter)
* [`jmeter` on Gitter](https://app.gitter.im/#/room/#aliesbelik_jmeter-chat:gitter.im)
* [`#jmeter` on Slack](https://jmeterusers.slack.com/)
* [`r/jmeter` on Reddit](https://www.reddit.com/r/jmeter/)

## Related

### Awesome Lists

* [Awesome Software Quality](https://github.com/ligurio/sqa-wiki) ⭐ 2,309 | 🐛 0 | 📅 2023-02-01 - A list of free software testing and verification resources.
* [Awesome Testing](https://github.com/TheJambo/awesome-testing) ⭐ 2,202 | 🐛 4 | 📅 2026-01-21 - A curated list of testing resources.
* [Awesome k6](https://github.com/grafana/awesome-k6) ⭐ 742 | 🐛 4 | 📅 2026-01-18 - Open-source, developer-centric performance monitoring and load testing solution.
* [Awesome Locust](https://github.com/aliesbelik/awesome-locust) ⭐ 110 | 🐛 0 | 📅 2026-01-05 - Open-source scalable load testing framework written in Python.
* [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) ⭐ 77 | 🐛 0 | 📅 2026-01-16 - Open-source load and performance testing framework based on Scala, Akka and Netty.
* [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) ⭐ 23 | 🐛 0 | 📅 2026-01-03 - Open-source multi-protocol distributed load testing tool, developed in Erlang.

### Other

* [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) ⭐ 231 | 🐛 0 | 📅 2025-12-01 - Collection of open-source tools for debugging, benchmarking, load and stress testing your code or services.
* [How They Load Test](https://github.com/aliesbelik/how-they-load) ⭐ 149 | 🐛 0 | 📅 2025-12-01 - A curated collection of publicly available resources on how companies around the world perform load testing.

## Contributing

Please take a look at the [CONTRIBUTING](origin/CONTRIBUTING.md) guidelines first.
