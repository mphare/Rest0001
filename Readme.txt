Convert Celsius to Fahrenheit

Where the tutorial is
---------------------
Crunchify REST Example
http://crunchify.com/how-to-build-restful-service-with-java-using-jax-rs-and-jersey/

Run it
------
  Use this URL to test:
    http://localhost:8080/crunchify/ctofservice
    http://localhost:8080/crunchify/ctofservice/<celsius>
    http://localhost:8080/crunchify/ctofservice/celsius?c=<celsius>

What it is
----------
Creates a few RESTful endpoints of various types
	1. url, fixed: Uses a constant independent value and returns the same dependent value every time
	2. url, variable: adds a variable for the independent value to the url, dependent value is based on the independent value
	3. url with parameter: uses a parameter for the independent value, dependent value is based on the independent value

ctofservice returns xml
ftocservice returns json

Also, this is a port from Eclipse to IntelliJ using the same Maven libraries the Eclipse project used


Concepts
--------
Rest and Maven with IntelliJ
different type of REST endpoints (url and parameterized)
different return types (xml and json)