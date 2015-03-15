# SonarQube notes and configuration

SonarQube is a static code analysis tool that provides a lot of information concerning the code in your projects.  It runs rules over all of your source code and provides a report with issues that should be addressed.

The main SonarQube page is at http://www.sonarqube.org/.  The documentation pages are at http://docs.sonarqube.org/.

## SonarQube Architecture
The architecture of SonarQube is very simple, and is depicted in the following diagram.  There is a central database that stores the SonarQube configuration and the results of the Analyzers.  The Web Server displays information from the central database and allows configuration of SonarQube. 

![Image of SonarQube Architecture](https://github.com/mcacciapouti/utd-sonarqube/blob/master/sonarqube-architecture.jpg)
