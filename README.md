maven
=====

This repository is including maven components and workouts. Especially pom.xml and dependencies.

Contents
========


Converting wsdl2java
--------------------

- You can find this example as wsdl2java-pom.xml

- With this pom you can generate java client service code from WSDL.

- "wsdlPath" is the property of WSDL location which can be online or local source.

- For execute this you can add to your project's pom.xml build and properties. After that at console(terminal or command promt) you can run this maven project with this example.
  
```

   $ mvn clean install -DwsdlPath=http://wsf.cdyne.com/WeatherWS/Weather.asmx?WSDL
 
```
- Apache CFX used for this operation. If you need more options as changing service name, generate server side of it or more.. You can visit apache cfx wsdl2java docs -> https://cxf.apache.org/docs/wsdl-to-java.html
