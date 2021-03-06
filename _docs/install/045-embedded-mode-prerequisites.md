---
title: "Distributed Mode Prerequisites"
parent: "Installing Drill in Distributed Mode"
---
You can install Apache Drill in distributed mode on one or multiple nodes to
run it in a clustered environment.

To install Apache Drill in distributed mode, complete the following steps:

  1. Install Drill on each designated node in the cluster.
  2. Configure a cluster ID and add Zookeeper information.
  3. Connect Drill to your data sources. 


**Prerequisites**

Before you install Apache Drill on nodes in your cluster, install and configure the
following software and services:

  * [Oracle JDK version 7](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html) (Required)
  * Configured and running a ZooKeeper quorum (Required)
  * Configured and running a Hadoop cluster (Recommended)
  * DNS (Recommended)
