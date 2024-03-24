Run the index.html file on a phone with chrome browser

Following are included in the html file and the app.

User should be able to insert the MQTT message broker host and port number.
Both Start and End button is added for connecting or disconnecting the connection with the MQTT message broker. 
When user clicks the start button, host and port input fields are disabled untill End button is clicked.
Users will receive a message when disconnected. 
Application will automatically re-establish the connection.
Users can publish any messages on any topic with the user input.
When “Share My Status” button is clicked , it sends the current location and a random value for the temperature as an MQTT message. 
User can also send GeoJson data from MQTTX which can be received on the web app on the phone.
All the messages are visible on MQTTX.