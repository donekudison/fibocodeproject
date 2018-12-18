# fibocodeproject
`Instruction required to complete A RESTful web service project`

1. The project should provide a RESTful web service.
  a. The web service accepts a number, n, as input and returns the first n Fibonacci numbers, starting from 0. I.e. given n = 5, appropriate output would represent the sequence [0, 1, 1, 2, 3].
  b. Given a negative number, it will respond with an appropriate error.
2. Include whatever instructions are necessary to build and deploy/run the project, where "deploy/run" means the web service is accepting requests and responding to them as appropriate.
3. Include some unit and/or functional tests
4. Use any language that you know well

While this project is admittedly trivial, approach it as representing a more complex problem that you'll have to put into production and maintain for 5 years.
Providing a link to a GitHub/Bit bucket repo with the project would probably be the easiest way to submit.


## Build/Deployment Instructions

This section includes the instructions necessary to build and have the web service accepting requests and responding to them.

 - Clone this [git repository]
 - Execute the following:
    - `https://https://github.com/donekudison/fibocodeproject.github.io`
 - Access the endpoint(s) with a web browser or CLI tool like `curl`:
    - `curl -iv http://localhost:8080/fibocodeproject`
    - `curl -iv http://localhost:8080/fibocodeproject/0`
    - `curl -iv http://localhost:8080/fibocodeproject/50`
    - `curl -iv http://localhost:8080/fibocodeproject/100`


## JS CODE : 
run the js code like  http://localhost:8080/fibocodeproject/js/index.html?n=5
