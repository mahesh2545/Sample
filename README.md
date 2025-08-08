# MQDemoApp - Sample ACE Application

This is a simple App Connect Enterprise (ACE) application that reads a message from an MQ queue and writes it to another MQ queue using a basic MQInput → Compute → MQOutput flow.

## Build Instructions

You can use `ibmint package` to build a BAR file:

```bash
source /opt/ibm/ace-12/server/bin/mqsiprofile
ibmint package --input-path . --output-bar-file MQDemoApp.bar
