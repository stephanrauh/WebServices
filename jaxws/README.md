# Subset of Java EE tutorial examples (only webservices)

This repository is a subset of the tutorials at
[Java EE Tutorial](https://javaee.github.io/tutorial).

It has been tested on Wildfly 10.1.0.CR1.


This software is provided to you under the terms described in
this [License](LICENSE.txt). By using this software, you agree to accept
the terms, as described by this license.

## Build this example

Run "mvn install" on the pom.xml of the root folder.

## Deploying
Using Eclipse, simply drag'n'drop the two projects hello-webclient and helloservice-war
to the Wildfly 10 server in the server tab.

## Testing
After starting Wildfly, navigate to these URLs:

http://localhost:8080/helloservice-war/Hello?wsdl
http://localhost:8080/hello-webclient/HelloServlet 

## Managment console of Wildfly
Find out about the URL of the WSDL file:
http://127.0.0.1:9990/console/App.html#standalone-deployments;backButton=/deployments-details

## Further documentation on WebServices:
https://docs.oracle.com/javaee/7/tutorial/jaxws001.htm#BNAYN
