Awesome Robot Framework [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

> A curated list of awesome Robot Framework resources and libraries

Resources
---------

Libraries
---------

- Standard Libraries
  - [BuiltIn](http://robotframework.org/robotframework/latest/libraries/BuiltIn.html) Contains generic often needed keywords. Imported automatically and thus always available.
  - [Collections](http://robotframework.org/robotframework/latest/libraries/Collections.html) Contains keywords for handling lists and dictionaries.
  - [DateTime](http://robotframework.org/robotframework/latest/libraries/DateTime.html) Supports creating and verifying date and time values as well as calculations between them.
  - [Dialogs](http://robotframework.org/robotframework/latest/libraries/Dialogs.html) Supports pausing the test execution and getting input from users.
  - [OperatingSystem](http://robotframework.org/robotframework/latest/libraries/OperatingSystem.html) Enables performing various operating system related tasks.
  - [Process](http://robotframework.org/robotframework/latest/libraries/Process.html) Supports executing processes in the system.
  - [Screenshot](http://robotframework.org/robotframework/latest/libraries/Screenshot.html) Provides keywords to capture and store screenshots of the desktop.
  - [String](http://robotframework.org/robotframework/latest/libraries/String.html) Library for manipulating strings and verifying their contents.
  - [Telnet](http://robotframework.org/robotframework/latest/libraries/Telnet.html) Supports connecting to Telnet servers and executing commands on the opened connections.
  - [XML](http://robotframework.org/robotframework/latest/libraries/XML.html) Library for verifying and modifying XML documents.

Tools
-----

- Built-in tools
  - [Rebot](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#post-processing-outputs) Tool for generating logs and reports based on XML outputs and for combining multiple outputs together.
  - [Libdoc](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#libdoc) Tool for generating keyword documentation for test libraries and resource files.
  - [Testdoc](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#testdoc) Generates high level HTML documentation based on Robot Framework test cases.
  - [Tidy](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#tidy) Tool for cleaning up and changing format of Robot Framework test data files.

- Build
  - [Jenkins plugin](https://wiki.jenkins-ci.org/display/JENKINS/Robot+Framework+Plugin) Plugin to collect and publish Robot Framework test results in Jenkins.
  - [Maven plugin](http://robotframework.org/MavenPlugin/) Maven plugin for using Robot Framework.
  - [Ant task](https://github.com/lcarbonn/robotframework-ant) Ant task for running Robot Framework tests.

- Mid level (framework) Libraries
  - [Android Library](https://github.com/lovelysystems/robotframework-androidlibrary) Library for all your Android automation needs. It uses Calabash Android internally.
  - [AnywhereLibrary](https://github.com/luisxiaomai/robotframework-anywherelibrary) Library for testing Single-Page Apps (SPA). Uses Selenium Webdriver and Appium internally.
  - [Appium Library](https://github.com/serhatbolsu/robotframework-appiumlibrary) Library for Android- and iOS-testing. It uses Appium internally.

- Low level (driver) Librabries
  - [Archive Library](https://github.com/bulkan/robotframework-archivelibrary) Library for handling zip- and tar-archives.
  - [AutoIt Library](https://code.google.com/archive/p/robotframework-autoitlibrary/) Windows GUI testing library that uses AutoIt freeware tool as a driver.
  - [Database Library (Java)](https://github.com/ThomasJaspers/robotframework-dblibrary) Java-based library for database testing. Usable with Jython.
  - [Database Library (Python)](https://github.com/franz-see/Robotframework-Database-Library) Python based library for database testing. Works with any Python interpreter, including Jython.

- Editors
  - [Atom Language Robot Framework](https://atom.io/packages/language-robot-framework) Robot Framework syntax highlighting for Atom
  - [Autocomplete Robot Framework](https://atom.io/packages/autocomplete-robot-framework) Robot Framework autocomplete for Atom
  - [Hyperclick Robot Framework](https://atom.io/packages/hyperclick-robot-framework) Robot Framework hyperclick provider for Atom

- Verification
  - [Robot Framework Lint](https://github.com/boakley/robotframework-lint) Linter for robot framework plain text files.
