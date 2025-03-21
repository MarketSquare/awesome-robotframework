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
  - [Wrappers](#wrappers)
  
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
  - [AWS](https://pypi.org/project/robotframework-aws/) - Keywords for interacting with AWS services in your test suites.
  - [Jenkins](https://pypi.org/project/robotframework-jenkins/) Jenkins interaction.
  - [Webpack](https://pypi.org/project/robotframework-webpack/) Control Webpack dev servers.
  - [Kubernetes](https://pypi.org/project/robotframework-kubelibrary/) - Keywords for interacting with the [Kubernetes API](https://kubernetes.io/).
  - [Terraform](https://pypi.org/project/robotframework-terraformlibrary/) - Infrastructure as Code via [Terraform](https://www.terraform.io/) and [OpenTofu](https://opentofu.org/).

### Data
  - [Datetime-TZ](https://pypi.org/project/robotframework-datetime-tz/) Date/time with locales and time zones.
  - [Excel Library](https://github.com/NaviNet-OSS/robotframework-excellibrary) Library which provides keywords to allow opening, reading, writing and saving Excel files.
  - [Excel10library](https://pypi.org/project/robotframework-excel10library/) Basic control over Excel10 (xlsx) files.
  - [Excel Lib](https://pypi.org/project/robotframework-excellib/) Work with Excel documents.
  - [JSON Schema Library](https://github.com/jstaffans/robotframework-jsonschemalibrary) JSON Schema validation library for Robot Framework.
  - [JSON Validator](https://pypi.org/project/robotframework-jsonvalidator/) JSON validation based on JSONSchema, JSONPath, JSONSelect.
  - [String Format](https://pypi.org/project/robotframework-stringformat/) String formatting.

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
  - [Construct](https://github.com/MarketSquare/robotframework-construct) Build and parse binary data.

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

### Messaging/Communication
  - [Confluent Kafka Library](https://pypi.org/project/robotframework-confluentkafkalibrary/) Wrapper for the confluent-kafka-python.
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


- Integrations
  - [Renode](https://renode.readthedocs.io/en/latest/introduction/testing.html#) Simulation in the loop testing for complex embedded systems based on Robot Framework.

- Network testing
  - [pyats.robot](https://pypi.org/project/pyats.robot/) - Sub-component of Cisco pyATS library for enabling network testing using RobotFramework.

- Remote Library Examples
  - [robotframework-scala-remote-library](https://github.com/jg8481/robotframework-scala-remote-library) An example of a Remote Server Keywords library implementation in Scala and based on a blog post written by Thomas Jaspers.

## Tools

- Built-in tools
  - [DbBot](https://github.com/MarketSquare/DbBot) DbBot is a tool to serialize Robot Framework test run results into a SQLite database.
  - [Rebot](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#post-processing-outputs) Tool for generating logs and reports based on XML outputs and for combining multiple outputs together.
  - [RoboMachine](https://github.com/mkorpela/RoboMachine) Model-based testing with Robot Framework.
  - [Libdoc](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#libdoc) Tool for generating Keywords for test libraries and resource files.
  - [Pabot](https://github.com/mkorpela/pabot) Parallel executor for Robot Framework test cases.
  - [Testdoc](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#testdoc) Generates high level HTML documentation based on Robot Framework test cases.
  - [Tidy](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#tidy) Tool for cleaning up and changing format of Robot Framework test data files.
  - [Remote Interface](https://github.com/robotframework/RemoteInterface) Introduction to the remote interface with a list of available remote servers.
  - [rfhub2](https://github.com/pbylicki/rfhub2) Tool for collecting, browsing and sharing documentation of existing keywords written in RobotFramework and python.

- Build
  - [Jenkins plugin](https://plugins.jenkins.io/robot/) Plugin to collect and publish Robot Framework test results in Jenkins.
  - [Robotcorder](https://chromewebstore.google.com/detail/robotcorder/ifiilbfgcemdapeibjfohnfpfmfblmpd) Chrome plugin to record session for Robot Framework.  
  - [Maven plugin](https://robotframework.org/MavenPlugin/) Maven plugin for using Robot Framework.
  - [Ant task](https://github.com/lcarbonn/robotframework-ant) Ant task for running Robot Framework tests.

- Cryptocurrency or Blockchain tools
  - [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) Robot Framework tools that integrate with various Web3 blockchain technologies for testing and deploying smart contracts written in Solidity. It also provides an example (using a forked Fantom mainnet) for starting your own blockchain monitoring process.

- Docker
  - [docker-robot-framework](https://github.com/ppodgorsek/docker-robot-framework) Robot Framework (with Firefox and Chrome) in Docker.
  - [robotframework-distbot](https://pypi.org/project/robotframework-distbot/) Distribute tests into multiple machines/docker containers.

- Editors
  - Jupyter
    - [robotkernel](https://github.com/robots-from-jupyter/robotkernel) RobotFramework kernel for Jupyter notebooks.
    - [xeus-robot](https://github.com/jupyter-xeus/xeus-robot) Jupyter kernel for Robot Framework based on the native implementation of the Jupyter protocol xeus.
  - [RobotCode](https://robotcode.io/) RobotCode Is a set of tools and extensions and plugins for working with Robot Framework in different IDEs, editors and on the command line.
    - VSCode Extensions
      - [RobotCode for VSCode](https://marketplace.visualstudio.com/items?itemName=d-biehl.robotcode) 
    - Pycharm/Intellij
      - [Robotcode for Jetbrains](https://plugins.jetbrains.com/plugin/26216-robotcode--robot-framework-support) 
    - 
- IDEs
  - [robotframework-workbench](https://pypi.org/project/robotframework-workbench/) Collection of tools for working with robotframework test suite and resource files.

- Integrations
  - [allure-robotframework](https://pypi.org/project/allure-robotframework/#data) - Robot Framework integration for Allure.
  - [robotframework-rp-tools](https://pypi.org/project/robotframework-rp-tools/) - Listener and visitor modules for integration with ReportPortal.
  - [RobotMK](https://www.robotmk.org) Robot Framework integration for the Open Source monitoring solution [Checkmk](https://checkmk.com).
  - [molecule-robotframework](https://pypi.org/project/molecule-robotframework/) - Ansible Molecule plugin for running molecule tests with Robot Framework.
  - [pytest-robotframework](https://pypi.org/project/pytest_robotframework/) - Pytest plugin that creates robotframework reports for tests written in python and allows you to run robotframework tests with Pytest.

- Verification
  - [Robot Framework Lint](https://github.com/boakley/robotframework-lint) Linter for robot framework plain text files.
  - [Robocop](https://github.com/MarketSquare/robotframework-robocop) Static code analysis tool for Robot Framework with use of latest robot API and many built-in rules that can be easily configured or switched off.

- Dashboard
  - [robotframework-metrics](https://github.com/adiralashiva8/robotframework-metrics) Dashboard view of execution results
  - [robotframework-dashboard](https://github.com/timdegroot1996/robotframework-dashboard) Dashboard view that provides insight of your test results across multiple runs. 
  - 
- Personal Assistants
  - [robotframework-test-assistant](https://github.com/jg8481/leon/tree/develop/packages/robotframework-test-assistant) Use a conversational AI test assistant to control Robot Framework test suites and RPA tasks with your voice or with text commands.

 - Performance
   - [rfswarm](https://github.com/damies13/rfswarm) Performance testing in robotframework

 - Historic
   - [robotframework-historic](https://github.com/adiralashiva8/robotframework-historic) Library to capture and generate historical reports
   
 - Robot Framework Executor
   - [robotframework-executor](https://github.com/MandyYdnam/Robo_App) Gui Application to Run the Robot Framework Test. With features like parellel execution, Batch monitor, Execution Monitor, Historical Stats, Downloads Batch/execution/historical data to csv, Bookmark test cases etc.  

## Resources

- Robocon 2020
  - [Playlist](https://www.youtube.com/playlist?list=PLSK6YK5OGX1AZMAffD8EiTDq0lfzshRNg&cbrd=1&ucbcb=1)

- RoboCon 2019
  - [Welcome back! What's new since RoboCon 2018?](https://www.youtube.com/watch?v=wBhY5Z2RoqQ&index=2&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [The start of the open source RPA movement](https://www.youtube.com/watch?v=uv6dvcoxdvU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=2)
  - [Evolution of Robot Framework user](https://www.youtube.com/watch?v=ynUmfWvZxpw&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=3)
  - [Decade with SeleniumLibrary and browsers' UI automation](https://www.youtube.com/watch?v=HVAnWH8t4rU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=4)
  - [RobotFramework for Embedded Software Testing](https://www.youtube.com/watch?v=0q4-AjqpO9M&index=5&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [RENAT - a network testing plugin based on Robot Framework](https://www.youtube.com/watch?v=FSjmJLq4S4A&index=6&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Robot Framework with Patient Monitors: Test Automation at GE Healthcare Finland](https://www.youtube.com/watch?v=gxbz5QJWdq4&index=7&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Practical Experiences on Evaluating Software Testing Tools](https://www.youtube.com/watch?v=2qKa3GEqcvY&index=8&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Robots from Jupyter The Future of Authoring Tests and Tasks](https://www.youtube.com/watch?v=rbYF_RmiAR8&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=9)
  - [Dynamically scalable test environment on top of Kubernetes](https://www.youtube.com/watch?v=ivLsjU77Q6c&index=10&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Dynamic Generation of Model Based Testcases Using Listener Interface Version 3](https://www.youtube.com/watch?v=qtEYZ5Om1Qk&index=11&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning Talks I - robotframework-whitelibrary](https://www.youtube.com/watch?v=ck_zvTq4zz8&index=12&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning talk II](https://www.youtube.com/watch?v=a-27Ot_suEU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=13)
  - [Lightning talk III - DevSecOps in embedded systems](https://www.youtube.com/watch?v=hA99dYnlb-s&index=14&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning talk IV - Testing Complext Graphical Applications & Games with RobotFramework](https://www.youtube.com/watch?v=g98m3XpE8gw&index=16&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [Lightning talk V - Robot Framework Testing in Cloud](https://www.youtube.com/watch?v=YJ4FTjxVG3o&index=17&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [Lightning talk VI - Robot Framework: More than just automation](https://www.youtube.com/watch?v=9HHgrLb41go&index=17&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Turning Test Results into Big Data](https://www.youtube.com/watch?v=fb42449bdz0&index=18&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)

- RoboCon 2018
  - [How Did We Get Here? Where Do We Go Next?](https://www.youtube.com/watch?v=6Kb1M3NECic&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z)
  - [The Naked Truth About Successful Test Automation Journey](https://www.youtube.com/watch?v=Z-9XIGZBf9U&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=2)
  - [Mega Robot Projects - What To Expect](https://www.youtube.com/watch?v=KsRP9TsZwEQ&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=3)
  - [Robot Framework in Plone CMS Project](https://www.youtube.com/watch?v=iJEWobuwPeI&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=4)
  - [The Importance of Open Source Communities](https://www.youtube.com/watch?v=2GDrtvz_1Ds&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=5)
  - [Towards Contract - Based API Testing with a New Rest Json Test Library](https://www.youtube.com/watch?v=TMU4WCIq3NA&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=6)
  - [Extending SeleniumLibrary 3.0](https://www.youtube.com/watch?v=ZPqQ-RozkYQ&index=7&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z)
  - [Design Patterns for Efficient Multi-Platform](https://www.youtube.com/watch?v=QDaXTkiviT0&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=8)
  - [Parallel test execution with Pabot](https://www.youtube.com/watch?v=i0RV6SJSIn8&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=9)

- Official Docs
  - [Robot Framework Introduction](https://github.com/robotframework/IntroSlides)
  - [Quickstart Guide](https://github.com/robotframework/QuickStartGuide/blob/master/QuickStart.rst)
  - [User Guide](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html)
  - [How To Write Good Test Cases](https://github.com/robotframework/HowToWriteGoodTestCases/blob/master/HowToWriteGoodTestCases.rst)

- Books

- MOOCs

- Theses
  - [Data-Driven and Keyword-Driven Test Automation Frameworks](http://eliga.fi/Thesis-Pekka-Laukkanen.pdf) Master's Thesis, Pekka Laukkanen
  - [Web  Application  Test  Automation  with  Robot Framework](https://www.theseus.fi/bitstream/handle/10024/93164/Thesis_Jani_Luostarinen_v1_0.pdf?sequence=1) Bachelor's Thesis, Jani Luostarinen

- Shared Code Repositories
  - [MarketSquare](https://github.com/MarketSquare) A community run collection of repositories for Robot Framework. Originally featured in a RoboCon 2020 lightning talk presented by Edward Manlove.

- Cookbooks
  - [Robot Framework recipes](https://github.com/adrianyorke/robotframework-cookbook/)

## Trainings
- [RFCP Training Providers](https://cert.robotframework.org/providers) Official page of the RFCP accredited training providers

## Wrappers

- [robotframework-webservice](https://github.com/MarketSquare/robotframework-webservice) Webservice for running Robot Framework test cases.
- [robotframework-aio](https://robotframework-aio.org/) RobotFramework AIO (All In One) installer for both Windows and Linux.
