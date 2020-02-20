Aviator Consensus Plug-In for Swirlds Hashgraph
===============================================

This repository contains a Swirlds Hashgraph consensus plug-in implementation for Aviator/Aviator Core Framework.  For more information on Aviator Core Framework and consensus plugins, please visit https://github.com/TxMQ/aviator-core

## Swirlds SDK Compatibility
This version of aviator-core-swirlds has been built for the 2018-12-30 version of the Swirlds SDK.  
Please use this version of the SDK when building your applications.

## Usage
The best way to utilize this library in your Aviator application is to include it as a maven dependency using the following repository and coordinates in your Maven POM:
```xml
<repositories>
	<repository>
		<id>aviator-core</id>
		<name>TxMQ Aviator Core Public Repository</name>
		<url>https://nexus.txmq.com:8080/repository/aviator-core/</url>
	</repository>		
  </repositories>

  <dependencyManagement>
  	<dependencies>
		<dependency>
			<groupId>com.txmq.aviator</groupId>
			<artifactId>aviator-core-bom</artifactId>
			<version>1.2.0</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
  	</dependencies>
  </dependencyManagement>
  <dependencies>
	<dependency>
		<groupId>com.txmq.aviator</groupId>
		<artifactId>AviatorCoreSwirlds</artifactId>
	</dependency>
  </dependencies>
