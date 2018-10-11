# DrivingLessonSystem

A system to handle driving lessons, payment and authorization, utilizing Java Web Application and Tomcat.

# Installation

## Windows

1. Download [JDK 11](https://download.java.net/java/ga/jdk11/openjdk-11_windows-x64_bin.zip) and set it up in IntelliJ IDEA.

2. Clone the repository to a folder.

3. Import the repository in IntelliJ IDEA as a Maven project, the project should now be setup.

4. Install [Tomcat 8.5.34](http://dk.mirrors.quenda.co/apache/tomcat/tomcat-8/v8.5.34/bin/apache-tomcat-8.5.34.exe). At the end of the install, do NOT start the service. If you have accidentally started it, just stop it.

5. In IntelliJ IDEA, in the upper right corner choose: "Add configuration" or "Edit configuration"

6. Expand the "Defaults" arrow to get the list of applications, choose: Tomcat Server -> Local

7. In "Application Server", set it to the directory of your Tomcat Server.

8. Fix the artifact deployment by pressing on the "Fix" button that is marked with a red circle and an exclamation mark. If this is not done, no web application will be deployed to Tomcat upon build and test.

9. The project is now setup.

## Linux

## macOS
