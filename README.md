# To build:
mvn clean install


# To run: 
Run config in IntelliJ pointing to RsocketShellClientApplication
Or: mvn clean package spring-boot:run -DskipTests=true


# To test:
Once the app has started, you will get a shell:> prompt. Type: 
    - request-response to test in mode request-response, ie standard HTTP model.
    - fire-and-forget to test by sending a request but not waiting for a response.
To finish off your testing, type: exit
