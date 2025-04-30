# Awesome Robot Framework [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
![Build Status](https://github.com/marketsquare/awesome-robotframework/actions/workflows/ci.yml/badge.svg)

[<img src="https://raw.githubusercontent.com/marketsquare/awesome-robotframework/master/robot_framework_logo_new.png" align="right" width="86">](https://robotframework.org/)

> A curated list of awesome Robot Framework resources and libraries

## Contents

- Awesome Robot Framework
  - [Robot Framework](#robot-framework)
  - [Robot Framework Foundation](#robot-framework-foundation)
  - [Libraries](#libraries)
  - [Tools](#tools)
  - [Resources](#resources)

## Robot Framework

- [Official Website](https://robotframework.org) The official Robot Framework Website
- [Guides](https://docs.robotframework.org/docs) The Robot Framework guides, with examples and explanations on how to use Robot Framework
- [RFCP](https://robotframework.org/robotframework-RFCP-syllabus/) The syllabus for the Robot Framework Certified Professional Exam
- [Robocon](https://robocon.io) The Premier Robot Framework conference, generally held in February
- [Standard Libraries](https://robotframework.org/robotframework/#standard-libraries) The standard set of Robot Framework Libraries, included with Robot Framework. Also known as "Core Libraries"
- [Style Guide](https://docs.robotframework.org/docs/style_guide) A community driven set of sensible rules to write your Robot Framework code.
- [User Guide](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html) Reference manual explaining all Robot Framework features in detail

### Robot Framework Foundation

The Robot Framework Foundation is a non-profit organization that supports the development and maintenance of the Robot Framework, an open-source automation tool used for acceptance testing and robotic process automation. The foundation sponsors bug fixes, ecosystem projects, reviews community contributions, and manages the framework's infrastructure, encouraging users to contribute to its ongoing development.

- [Robot Framework Foundation](https://robotframework.org/foundation) Join the Robot Framework Foundation

## Community

- [MarketSquare](https://marketsquare.github.io/) A community run collection of repositories for Robot Framework.
- [Slack](https://slack.robotframework.org/) Official Robot Framework Slack Channel.
- [Forum](https://forum.robotframework.org/) Official Robot Framework forum.
- [LinkedIn](https://www.linkedin.com/groups/3710899/) The Robot Framework Linkedin Group

## Libraries

### Core

- [BuiltIn](https://robotframework.org/robotframework/latest/libraries/BuiltIn.html) Contains generic often needed keywords. Imported automatically and thus always available.
- [Collections](https://robotframework.org/robotframework/latest/libraries/Collections.html) Contains keywords for handling lists and dictionaries.
- [DateTime](https://robotframework.org/robotframework/latest/libraries/DateTime.html) Supports creating and verifying date and time values as well as calculations between them.
- [Dialogs](https://robotframework.org/robotframework/latest/libraries/Dialogs.html) Supports pausing the test execution and getting input from users.
- [OperatingSystem](https://robotframework.org/robotframework/latest/libraries/OperatingSystem.html) Enables performing various operating system related tasks.
- [Process](https://robotframework.org/robotframework/latest/libraries/Process.html) Supports executing processes in the system.
- [Screenshot](https://robotframework.org/robotframework/latest/libraries/Screenshot.html) Provides keywords to capture and store screenshots of the desktop.
- [String](https://robotframework.org/robotframework/latest/libraries/String.html) Library for manipulating strings and verifying their contents.
- [Telnet](https://robotframework.org/robotframework/latest/libraries/Telnet.html) Supports connecting to Telnet servers and executing commands on the opened connections.
- [XML](https://robotframework.org/robotframework/latest/libraries/XML.html) Library for verifying and modifying XML documents.

### App/Mobile

- [Android Library](https://github.com/lovelysystems/robotframework-androidlibrary) ([Keywords](http://www.lovelysystems.com/robotframework-androidlibrary/AndroidLibrary.html)) Library for all your Android automation needs. It uses Calabash Android internally.
- [Appium Library](https://github.com/serhatbolsu/robotframework-appiumlibrary) Library for Android- and iOS-testing. It uses Appium internally.
- [iOS Library](https://github.com/lovelysystems/robotframework-ioslibrary) Library for all your iOS automation needs. It uses Calabash iOS Server internally.

### Cloud and Devops

- AWS
  - [AWS](https://pypi.org/project/robotframework-aws/) - Keywords for interacting with AWS services in your test suites.
  - [DynamoDBSQL Library](https://github.com/rickypc/robotframework-dynamodbsqllibrary) - An Amazon AWS DynamoDB big data testing library for Robot Framework with SQL-like DSL.
- [Jenkins](https://pypi.org/project/robotframework-jenkins/) Jenkins interaction.
- [Webpack](https://pypi.org/project/robotframework-webpack/) Control Webpack dev servers.
- [Kubernetes](https://pypi.org/project/robotframework-kubelibrary/) - Keywords for interacting with the [Kubernetes API](https://kubernetes.io/).
- [Terraform](https://pypi.org/project/robotframework-terraformlibrary/) - Infrastructure as Code via [Terraform](https://developer.hashicorp.com/terraform) and [OpenTofu](https://opentofu.org/).

### Data

- [Datetime-TZ](https://pypi.org/project/robotframework-datetime-tz/) Date/time with locales and time zones.
- [Excel Library](https://github.com/NaviNet-OSS/robotframework-excellibrary) Library which provides keywords to allow opening, reading, writing and saving Excel files.
- [Excel10library](https://pypi.org/project/robotframework-excel10library/) Basic control over Excel10 (xlsx) files.
- [Excel Lib](https://pypi.org/project/robotframework-excellib/) Work with Excel documents.
- [JSON Schema Library](https://github.com/jstaffans/robotframework-jsonschemalibrary) JSON Schema validation library for Robot Framework.
- [JSON Validator](https://pypi.org/project/robotframework-jsonvalidator/) JSON validation based on JSONSchema, JSONPath, JSONSelect.
- [String Format](https://pypi.org/project/robotframework-stringformat/) String formatting.
- [XML Validator](https://pypi.org/project/robotframework-xmlvalidator/) A Robot Framework library for validating XML files against XSD schemas.

### Database

- [Cassandracql Library](https://pypi.org/project/robotframework-cassandracqllibrary/) Execute CQL statements in Cassandra Database.
- [Couchbase Library](https://pypi.org/project/robotframework-couchbaselibrary/) Work with Couchbase.
- [Couchbase Manager](https://pypi.org/project/robotframework-couchbasemanager/) Manage Couchbase server.
- [Database Library](https://github.com/MarketSquare/Robotframework-Database-Library) Python based library for database testing. Works with any Python interpreter, including Jython.
- [Database Library (SQLAlchemy)](https://pypi.org/project/robotframework-databaselib/) Database lib based on SQLAlchemy.
- [Keepass Library](https://pypi.org/project/robotframework-keepasslibrary/) Work with KeePass databases.
- [MongoDB Library](https://github.com/iPlantCollaborativeOpenSource/Robotframework-MongoDB-Library#readme) Library for interacting with MongoDB using pymongo.
- [Oracledb Library](https://pypi.org/project/robotframework-oracledb/) Work with Oracle Databases.
- [Postgresqldb Library](https://pypi.org/project/robotframework-postgresqldb/) Work with PostgresSQL databases.
- [Tarantool Library](https://pypi.org/project/robotframework-tarantoollibrary/) Work with Tarantool DB.

### Embedded

- [CncLibrary](https://github.com/Eficode/robotframework-cnclibrary) Control a ShapeOko 2 CNC-milling machine (controlled by Arduino based grbl motion controller connected to Raspberry Pi 2 with camera module).
- [Construct](https://github.com/MarketSquare/robotframework-construct) Build and parse binary data.
- [HPI Library](https://github.com/kontron/robotframework-hpilibrary) Interface processors using the Hardware Platform Interface (HPI) specification.
- [IPMI Library](https://github.com/kontron/robotframework-ipmilibrary) Interface hardware using the Intelligent Platform Management Interface (IPMI) specification.

### Fieldbus

- [ModbusLibrary](https://github.com/Legrandgroup/robotframework-modbuslibrary) Modbus library.

### File Handling

- [Archive Library](https://github.com/MarketSquare/robotframework-archivelibrary) Library for handling zip- and tar-archives.
- [OpenAFS Library](https://pypi.org/project/robotframework-openafslibrary/) Test library for the OpenAFS distributed filesystem.
- [UNIX Filesystem Library](https://github.com/ChrisHirsch/robotframework-unixfilesystem) Unix filesystem testing for Robot Framework.

### Frameworks

- [AngularJS Library](https://github.com/MarketSquare/robotframework-angularjs) An AngularJS extention library to Robotframework's Selenium2Library.
- [DjangoLibrary](https://kitconcept.github.io/robotframework-djangolibrary/DjangoLibraryDocs.html) Library for Django, a Python web framework.
- [Drupal Library](https://github.com/alterway/robotframework-drupallibrary) Library targeting Drupal sites, built on top of Selenium2Library.
- [React Library](https://pypi.org/project/robotframework-react/) Work with React.js based web applications.

### GUI And Applications

- [AutoIt Library](https://code.google.com/archive/p/robotframework-autoitlibrary/) Windows GUI testing library that uses AutoIt freeware tool as a driver.
- [Eclipse Library](https://github.com/lcarbonn/robotframework-eclipselibrary) Library for testing Eclipse RCP applications using SWT widgets.
- [Remote Swing Library](https://github.com/MarketSquare/remoteswinglibrary) Robot Framework library for testing and connecting to a java process and using SwingLibrary.
- [RoboSAPiens](https://github.com/imbus/robotframework-robosapiens) SAP GUI Automation for Humans
- [SapGui Library](https://github.com/frankvanderkuur/robotframework-sapguilibrary) Automate the SAP GUI Desktop client
- [Swing Library](https://github.com/MarketSquare/SwingLibrary) ([Keywords](https://marketsquare.github.io/SwingLibrary/SwingLibrary-2.3.0.html)) Library for testing Java applications with Swing GUI.
- [Zoomba](https://pypi.org/project/robotframework-zoomba/) Collection of testing libraries spanning GUI, REST/SOAP API, and Windows Desktop automation.

### Identity Management

- [OimClient Library](robotframework-oimclientlibrary) Oracle Identity Manager testing.

### Messaging/Communication

- [BonjourLibrary](https://github.com/Legrandgroup/robotframework-bonjourlibrary) Testing devices announcing services using the Bonjour/mDNS protocol.
- [Confluent Kafka Library](https://pypi.org/project/robotframework-confluentkafkalibrary/) Wrapper for the confluent-kafka-python.
- [DHCP Client Library](https://github.com/Legrandgroup/robotframework-dhcpclientlibrary) Library for testing DHCP servers.
- [DHCP Server Library](https://github.com/Legrandgroup/robotframework-dhcpserverlibrary) Library for testing DHCP clients.
- [FTP Library](https://github.com/kowalpy/Robot-Framework-FTP-Library) Library which makes it possible to test or use FTP server using Robot Framework keywords.
- [HTTP Ctrl](https://pypi.org/project/robotframework-httpctrl/) HTTP/HTTPS client and HTTP server services to make REST API testing easy.
- [HTTP Request (Java)](https://github.com/MarketSquare/robotframework-httprequestlibrary) Library for HTTP level testing using Apache HTTP client.
- [HTTP Request (livetest)](https://github.com/peritus/robotframework-httplibrary) Library for HTTP level testing using livetest tool internally.
- [HTTP Request (Requests)](https://github.com/MarketSquare/robotframework-requests) Library for HTTP level testing using Request internally.
- [IMAP Library](https://github.com/rickypc/robotframework-imaplibrary) Library to test IMAP email validation tasks.
- [MQTT Library](https://github.com/randomsync/robotframework-mqttlibrary) Library that provides keywords for testing on MQTT brokers.
- [RabbitMQ](https://pypi.org/project/robotframework-rabbitmq/) Work with RabbitMQ.
- [Requests Checker](https://pypi.org/project/robotframework-requestschecker/) Check HTTP Response Status Codes.
- [Requests Logging](https://pypi.org/project/robotframework-requestslogger/) Log HTTP requests and responses.
- [RESTinstance Library](https://pypi.org/project/RESTinstance/) Robot Framework test library for (RESTful) JSON APIs.
- [SSH Library](https://pypi.org/project/robotframework-sshlibrary/) Test library for SSH and SFTP.
- [SNMP Library](https://pypi.org/project/robotframework-snmplibrary/) Work with SNMP.
- [SSHTunnel Library](https://pypi.org/project/robotframework-sshtunnellibrary/) Connect to remote host using SSH Local Forwarding.
- [Stub Library](https://pypi.org/project/robotframework-stublibrary/) For all your HTTP needs.
- [Suds Library](https://github.com/ombre42/robotframework-sudslibrary) ([Keywords](http://ombre42.github.io/robotframework-sudslibrary/doc/SudsLibrary.html)) Library for functional testing of SOAP-based web services with Suds, a dynamic SOAP 1.1 client.
- [UA RF TESTER](https://github.com/mikakaraila/UA-RF-TESTER) OPC UA library for functional and security testing.
- [UPnP/SSDP Library](https://github.com/Legrandgroup/robotframework-upnplibrary) Testing devices announcing services using the UPnP/SSDP protocol.
- [Websocket Client](https://pypi.org/project/robotframework-websocketclient/) Wrapper for the websocket-client module.

### Screenshots

- [Remotetransfer](https://pypi.org/project/robotframework-remotetransfer/) Transfer screenshots from remoteserver to local machine.
- [Screencap Library](https://pypi.org/project/robotframework-screencaplibrary/) Take screenshots and videos.

### System and Network Management

- [Docker](https://pypi.org/project/robotframework-docker/) Work with Docker and Docker Compose.
- [IPMI](https://pypi.org/project/robotframework-ipmilibrary/) Test IPMI devices.
- [Ncclient](https://github.com/vkosuri/robotframework-ncclient) ([Keywords](https://vkosuri.github.io/robotframework-ncclient/)) Robotframework NETCONF wrapper library of ncclient.
- [Apache Tomcat](https://pypi.org/project/robotframework-apachetomcat/) - Manage Apache Tomcat server.
- [Zookeeper Manager](https://pypi.org/project/robotframework-zookeepermanager/) Manage Apache Zookeeper.
- [Xvfb](https://pypi.org/project/robotframework-xvfb/) Interact with Xvfb.
- [WinRegistry](https://pypi.org/project/winregistry/) Work with Windows Registry.
- [PerfmonLibrary](https://github.com/damies13/robotframework-perfmon) Read Windows Performance Monitor Counters.

### Testing And Debugging

- [Advanced Logging](https://pypi.org/project/robotframework-advancedlogging/) Create additional logs.
- [Debug Library](https://github.com/xyb/robotframework-debuglibrary) Debug Library for Robot Framework
- [Dependency Library](https://pypi.org/project/robotframework-dependencylibrary/) Declare dependencies between Robot Framework tests.
- [Dependency Solver](https://pypi.org/project/robotframework-dependencysolver/) A Robot Framework prerunmodifier for interdependent test cases execution.
- [Testrail](https://pypi.org/project/robotframework-testrail/) Listener and pre-run modifier for working with TestRail.

### Visual Testing

- [Applitools Robot Framework](https://github.com/applitools/eyes.sdk.python/tree/develop/eyes_robotframework) Visual Verification Test Library using Applitools Eyes (Utilizes AppiumLibrary or\and SeleniumLibrary).
- [DocTestLibrary](https://github.com/manykarim/robotframework-doctestlibrary) Simple Automated Visual Document Testing.
- [Eyes](https://pypi.org/project/robotframework-eyeslibrary/) To automate visual software testing.
- [ImageHorizonLibrary](https://github.com/Eficode/robotframework-imagehorizonlibrary) ([Keywords](https://eficode.github.io/robotframework-imagehorizonlibrary/doc/ImageHorizonLibrary.html)) Cross-platform, pure Python library for GUI automation based on image recognition.
- [WatchUI](https://github.com/Tesena-smart-testing/WatchUI) Custom library for works with image, pdf and tesseract with RF.

### Web Testing

- [AnywhereLibrary](https://github.com/luisxiaomai/robotframework-anywherelibrary) Library for testing Single-Page Apps (SPA). Uses Selenium Webdriver and Appium internally.
- [Browser](https://pypi.org/project/robotframework-browser/) - Automate the browser using Playwright.
- [Page Object Library](https://github.com/boakley/robotframework-pageobjectlibrary) Library that makes it possible to use the page object pattern when testing web pages.
- [QWeb](https://github.com/qentinelqi/qweb) - Keyword based test automation for the web. ([Keywords](https://qentinelqi.github.io/qweb/QWeb.html))
- [Selenium Library](robotframework-seleniumlibrary) Web testing based on Selenium.
- [Selenium Screenshots](https://pypi.org/project/robotframework-seleniumscreenshots/) Capture annotated screenshots with SeleniumLibrary.
- [Selenium Testability](https://pypi.org/project/robotframework-seleniumtestability/) Provides either manual or automatic waiting asyncronous events within SUT.

## Integrations and Examples

### Integrations

- [allure-robotframework](https://pypi.org/project/allure-robotframework/#data) - Robot Framework integration for Allure.
- [Renode](https://renode.readthedocs.io/en/latest/introduction/testing.html#) - Simulation in the loop testing for complex embedded systems based on Robot Framework.
- [robotframework-oxygen](https://github.com/eficode/robotframework-oxygen) - Convert the results of any testing tool or framework to RobotFramework's reporting.
- [robotframework-rp-tools](https://pypi.org/project/robotframework-rp-tools/) - Listener and visitor modules for integration with ReportPortal.
- [RobotMK](https://www.robotmk.org) - Integration for the Open Source monitoring solution [Checkmk](https://checkmk.com).
- [molecule-robotframework](https://pypi.org/project/molecule-robotframework/) - Ansible Molecule plugin for running molecule tests with Robot Framework.
- [pytest-robotframework](https://pypi.org/project/pytest_robotframework/) - Pytest plugin for creating Robot Framework reports and running tests.

### Network Testing

- [pyats.robot](https://pypi.org/project/pyats.robot/) - Sub-component of Cisco pyATS library for enabling network testing using Robot Framework.

### Remote Library Examples

- [robotframework-scala-remote-library](https://github.com/jg8481/robotframework-scala-remote-library) - Example of a Remote Server Keywords library implementation in Scala, based on a blog post by Thomas Jaspers.

## Tools

### Built-in Tools

- [Rebot](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#post-processing-outputs) - Generate logs and reports based on XML outputs and combine multiple outputs.
- [Libdoc](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#libdoc) - Generate keywords for test libraries and resource files.
- [Testdoc](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#testdoc) - Generate high-level HTML documentation from test cases.
- [Remote Interface](https://github.com/robotframework/RemoteInterface) - Introduction to the remote interface with a list of available remote servers.
- [Maven plugin](https://robotframework.org/MavenPlugin/) - Maven plugin for using Robot Framework.

### Advanced Testing Tools

- [Robot Framework Swarm](https://github.com/damies13/rfswarm) - Performance testing in Robot Framework.
- [Pabot](https://github.com/mkorpela/pabot) - Parallel executor for Robot Framework test cases.
- [RoboMachine](https://github.com/mkorpela/RoboMachine) - Model-based testing with Robot Framework.

### Build Tools

- [Jenkins plugin](https://plugins.jenkins.io/robot/) - Collect and publish Robot Framework test results in Jenkins.
- [Ant task](https://github.com/lcarbonn/robotframework-ant) - Ant task for running Robot Framework tests.

### Toolkits

- [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) - A toolkit for testing, deploying, and monitoring Solidity smart contracts on EVM-compatible blockchains using Robot Framework, with support for local clean-room environments and multichain setups.

### Containerization

- [BrowserLibraryDocker](https://hub.docker.com/r/marketsquare/robotframework-browser/tags?page=1&ordering=last_updated) - Docker image for Robot Framework with BrowserLibrary.
- [docker-robot-framework](https://github.com/ppodgorsek/docker-robot-framework) - Robot Framework (with Firefox and Chrome) in Docker.
- [robotframework-distbot](https://github.com/rajeevnaikte/distbot) - Distribute tests across multiple machines or Docker containers.

### Development and Editing Tools

- [RIDE - Robot Framework IDE](https://github.com/robotframework/RIDE/) - Lightweight and intuitive editor for Robot Framework test data.
- [RobotCode](https://robotcode.io/) - Tools, extensions, and plugins for working with Robot Framework.
- [RobotCode for VSCode](https://marketplace.visualstudio.com/items?itemName=d-biehl.robotcode) - VSCode extension.
- [RobotCode for Jetbrains](https://plugins.jetbrains.com/plugin/26216-robotcode--robot-framework-support) - Plugin for PyCharm/IntelliJ.
- [Robocop](https://robocop.readthedocs.io/en/stable/) - Static code analysis tool and formatting with configurable rules.

### Reporting Tools

- [robotframework-metrics](https://github.com/adiralashiva8/robotframework-metrics) - Dashboard view of execution results of a single run.
- [robotframework-dashboard](https://github.com/timdegroot1996/robotframework-dashboard) - Dashboard for insights into test results across multiple runs.
- [DbBot](https://github.com/MarketSquare/DbBot) - Serialize Robot Framework test run results into a SQLite database.
- [robotframework-historic](https://github.com/adiralashiva8/robotframework-historic) - Generate historical reports from test results.

### AI Tools

- [RobotFramework-AI](https://github.com/imbus/robotframework-ai) Adds AI functionality (generates test data, replies to messages).
- [robotframework-test-assistant](https://github.com/jg8481/leon/tree/develop/packages/robotframework-test-assistant) - Conversational AI assistant for controlling Robot Framework test suites and RPA tasks.

### Execution Tools

- [robotframework-executor](https://github.com/MandyYdnam/Robo_App) - GUI application for running Robot Framework tests with features like parallel execution, batch monitoring, and historical stats.
- [robotframework-webservice](https://github.com/MarketSquare/robotframework-webservice) Webservice for running Robot Framework test cases.
- [robotframework-aio](https://robotframework-aio.org/) RobotFramework AIO (All In One) installer for both Windows and Linux.

### (Interactive) Learning Tools

- [Robot Framework Online Playground](https://robotframework.org/code/) - Try tutorial examples in the browser or share code on forums or Slack.
- [Code Examples](https://github.com/Snooz82/robotframework-code-examples) - Various file configurations for Robot Framework.
- [Robot Framework Cookbook](https://github.com/adrianyorke/robotframework-cookbook/)
- [robotkernel](https://github.com/robots-from-jupyter/robotkernel) - Robot Framework kernel for Jupyter notebooks.
- [xeus-robot](https://github.com/jupyter-xeus/xeus-robot) - Jupyter kernel for Robot Framework based on the xeus protocol.

## Resources

- [robotframework-cookbook](https://github.com/adrianyorke/robotframework-cookbook) - A curated list of delicious Robot Framework recipes that will help accelerate the development of test automation scripts, especially for beginner or intermediate level engineers.
- [RobotFramework Youtube Channel](https://www.youtube.com/c/RobotFrameworkChannel) with speaches from previous Robocon and [tutorials in the live section](https://www.youtube.com/@RobotFrameworkChannel/streams).

### Robocon

- [Playlist 2024](https://www.youtube.com/playlist?list=PLSK6YK5OGX1CECNLS7E9H2iTsWPMZrHmA)
- [Playlist 2023](https://www.youtube.com/playlist?list=PLSK6YK5OGX1DYqe35OX0_CqE1DEP7dI9I)
- [Playlist 2022](https://www.youtube.com/playlist?list=PLSK6YK5OGX1AN9PSVHz1vsoSqbz3tFS_C)
- [Playlist 2021](https://www.youtube.com/playlist?list=PLSK6YK5OGX1ALlSRlwr9dWJu3mFHMlVq8)
- [Playlist 2020](https://www.youtube.com/playlist?list=PLSK6YK5OGX1AZMAffD8EiTDq0lfzshRNg)
- [Playlist 2019](https://www.youtube.com/playlist?list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
- [Playlist 2018](https://www.youtube.com/playlist?list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z)

### Theses

- [Data-Driven and Keyword-Driven Test Automation Frameworks](http://eliga.fi/Thesis-Pekka-Laukkanen.pdf) Master's Thesis, Pekka Laukkanen (2006)
- [Web Application Test Automation with Robot Framework](https://www.theseus.fi/bitstream/handle/10024/93164/Thesis_Jani_Luostarinen_v1_0.pdf?sequence=1) Bachelor's Thesis, Jani Luostarinen (2015)
- [Enabling Self-healing Locators for Robot Framework with Large Language Models](https://helda.helsinki.fi/server/api/core/bitstreams/631b961a-8642-42ed-9826-3e196eac9cf7/content) Master’s thesis, Paavo Rohamo (2024)

## Trainings

- [RFCP Training Providers](https://cert.robotframework.org/providers) Official page of the RFCP accredited training providers
