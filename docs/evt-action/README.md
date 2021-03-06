# Taking An Action with Cloud Functions

IBM Cloud Functions is a "Serverless" compute offering. While one of the appeals of serverless computing is the provision of cost-effective compute time, it also provides a simplified *event-driven programming model* which is very valuable for event-driven solutions.

valuable for event-driven solutions.
With Cloud Functions, the process is as follows:


* Developers write functional logic called *actions*.
* *Actions* can be written in many supported languages including Java, Python, Node, Swift, Go, or other languages.
* *Actions* are triggered from events being published to Kafka topics (the event backbone).
* Cloud Functions brings up the required compute to run the action.
* Cloud Functions shuts down the server when the action is complete.
* Cloud Functions automatically scales for event volume and velocity.

For event-driven systems, this simple event driven programming model is powerful.  It abstracts the complications of event handling and load balancing to ensure that you have enough subscribing consumers ready to handle the velocity of events published through the system.

Developers write the code which executes the required business logic.

## Supporting products

[IBM Cloud Functions](https://console.bluemix.net/openwhisk) is a commercial service offering version of the [Apache Openwhisk project](https://openwhisk.apache.org)

IBM Cloud Functions product offering https://www.ibm.com/cloud/functions

## Suggested reading

Getting Started with Cloud Functions https://console.bluemix.net/openwhisk/

Using Cloud functions with event trigger in Kafka  https://github.com/IBM/ibm-cloud-functions-message-hub-trigger
