# To build:
mvn clean install


# To run: 
Run config in IntelliJ pointing to RsocketShellClientApplication
Or: mvn clean package spring-boot:run -DskipTests=true


# To test:
Once the app has started, you will get a shell:> prompt. Type: 
    - request-response to test in mode request-response, ie standard HTTP model.
    - fire-and-forget to test by sending a request but not waiting for a response.
    - stream to stream data using the conventional ‘client-requests-a-server-stream’ approach. Note that it is also possible to implement the less common ‘server-requests-a-client-stream’ model.
    - channel to request a channel from the server.
To finish off your testing when using stream/channel, type 's' + enter.

To exit the app, type 'exit' + enter.
