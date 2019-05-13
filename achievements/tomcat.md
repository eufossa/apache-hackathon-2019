# Apache Tomcat

Prior to the Hackathon the Tomcat commiters created a [wiki page](https://cwiki.apache.org/confluence/display/TOMCAT/EU+FOSSA+May+2019) with topics to work on and discuss.

Most of the people at the Tomcat table got interested in getting Tomcat to run on GraalVM. 
Because we already knew that Tomcat would not run with the latest published version of GraalVM, we started with compiling the master branch of GraalVM from Github. There is a commit in master just done a few days before the event that should fix some issues that appeared before.

Compiling GraalVM from source turned out to be a little bit tricky, because it did not compile with a regular version of the Java VM but required a special JVM.

Progress was made on Tomcat support for Graal (documentation, process, use of native-image and utilities, compatibility issues in Tomcat), with a lot more work ahead. The Tomcat container ready packaging is not too far from running in a basic configuration.

## Tasks

* Add feature for directory listing sorting
* Work on testing and voting for new Tomcat releases (9.0.20 and 8.5.41)
* Work on testsuite issues:
  * HTTP/2 input data corruption issue with asynchronous IO
  * incorrect HTTP/2 timeout problem following CVE fix
  * i18n missing causing failures

## More information

* [https://github.com/ventura-eesc/GraalVM-Tomcat](https://github.com/ventura-eesc/GraalVM-Tomcat)
* [https://github.com/ventura-eesc/tomcat-contributions](https://github.com/ventura-eesc/tomcat-contributions)
* [https://github.com/ventura-eesc/gpg-signature-guide](https://github.com/ventura-eesc/gpg-signature-guide)