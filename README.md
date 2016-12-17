# Aspera sample plug-in

*This sample plug-in has a dependency on a new IBM Aspera Faspex client SDK release. Once this new release is available the sample plug-in will be available from this location.*

Aspera Faspex provides an efficient way to send files from anywhere in the world.
This sample plug-in demonstrates the use of Aspera Faspex from within IBM Content Navigator.

![aspera dialog](https://cloud.githubusercontent.com/assets/22042538/21284644/f7a22f40-c3ef-11e6-86fb-d78d9d638d49.png)

## Getting started

Use these instructions to help you get the plug-in up and running in IBM Content Navigator.

## Prerequisites

* IBM Content Navigator 3.0 or later
* FileNet Content Engine Java API
* Aspera Redistributable Package
* Servlet API
* [Apache Commons Configuration](https://commons.apache.org/proper/commons-configuration/)
* [Apache Ant](http://ant.apache.org/)
* JUnit
* Mockito
* Dojo Toolkit source

### Installing the plug-in

1. Clone or download the plug-in from [GitHub](https://github.com/ibm-ecm/ibm-navigator-aspera-sample).
2. Create a **lib** directory under the plug-in's root directory and copy prerequisite libraries except for the Dojo Toolkit source to the **lib** directory.
3. Copy the Dojo Toolkit source archive file to the **build** directory.
4. Build the plug-in JAR file by running Apache Ant.
5. [Register and configure the plug-in in IBM Content Navigator.](http://www.ibm.com/support/knowledgecenter/SSEUEX_3.0.0/com.ibm.installingeuc.doc/eucco012.htm)
6. Add the **Send to IBM Aspera** menu action to the document context menu.

## Additional references

* [Developing applications with IBM Content Navigator](https://www.ibm.com/support/knowledgecenter/SSEUEX_3.0.0/com.ibm.developingeuc.doc/eucdi000.html)
* [dW Answers forum](https://developer.ibm.com/answers/topics/icn/)
