---
title: "Installing Drill on Linux and Mac OS X"
parent: "Installing Drill in Embedded Mode"
---
First, check that you [meet the prerequisites]({{site.baseurl}}/docs/embedded-mode-prerequisites), and then install Apache Drill on Linux or Mac OS X:

Complete the following steps to install Drill:  

1. In a terminal windows, change to the directory where you want to install Drill.

2. To download the latest version of Apache Drill, download Drill from the [Drill web site](http://getdrill.org/drill/download/apache-drill-1.0.0.tar.gz) or run one of the following commands, depending on which you have installed on your system:  
   * `wget http://getdrill.org/drill/download/apache-drill-1.0.0.tar.gz`  
   *  `curl -o apache-drill-1.0.0.tar.gz http://getdrill.org/drill/download/apache-drill-1.0.0.tar.gz`  

3. Copy the downloaded file to the directory where you want to install Drill. 

4. Extract the contents of the Drill tar.gz file. Use sudo only if necessary:  

        tar -xvzf apache-drill-1.0.0.tar.gz  

The extraction process creates the installation directory named apache-drill-1.0.0 containing the Drill software.

At this point, you can [start Drill]({{site.baseurl}}/docs/starting-drill-on-linux-and-mac-os-x).