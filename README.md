----
# Welcome to GALA! #

----
## What is GALA? ##
GALA is a cryptocurrency to make the world a better place.

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8 
    - *Windows* - https://www.java.com/
    - [![Why is Java 8 recommended](https://www.teststrana.com/images/java.jpg)](https://www.java.com/en/download/why-java-8-recommended.html)
    - *Ubuntu* - https://tecadmin.net/install-java-ubuntu-20-04/
    - *Debian* - https://docs.datastax.com/en/jdk-install/doc/jdk-install/installOpenJdkDeb.html
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##
    download and unzip file
  - click on the GALA icon, or start from the command line:
  - Unix: `./run.sh`
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:7003/ in a browser

----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Troubleshooting the NRS (GALA Reference Software) ##

  - How to Stop the NRS Server?
    - click on GALA Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on BitBucket

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder

----

## License
* This program is distributed under the terms of the Jelurida Public License version 1.1 for the Ardor Public Blockchain Platform.
