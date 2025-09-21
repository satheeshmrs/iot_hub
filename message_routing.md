# Message Routing
--> Connecting IOT hub is not only enough
--> Messages from IOT device should be routed somewhere
--> EventHub and Custom Hub
--> EventHub /Service bus

## Typical Architecture

Device --> IOT Hub --> EventHub --> Function (Validate) --> Event Grid --> Function --> COsmos --> Web

## Communication
1. Device to cloud Communication
2. Cloud to Device Communication

## Device to CLoud Communication:
Three Modes
1. Telemetry and Data (The most COmmon)
2. Files Upload
3. Device Twin

## Cloud to Device Communication
The Other way around
1. Send COmmand to the device
2. Software updates

   Use Direct call to Device


    Installation of the Extension: The session begins with installing the Azure IoT Tools extension in VS Code, which facilitates better interaction with the IoT Hub.

    Sending Messages: After setting up a connection string, the lecture demonstrates how to send a Device-to-Cloud (D-to-C) message from a device called 'IoT Dev 1' using a JSON formatted message indicating an error status.

    Message Confirmation: The lecturer checks the Azure portal to ensure that the message was received and routed properly.

    Message Routing: There's a discussion about the significance of message routing in the IoT Hub, specifically regarding the fallback route for messages that do not match any predefined routes.

    Routing Issues: Metrics are used to confirm that the message went to the fallback route, highlighting issues in reaching the intended storage account container.

    Message Properties: For proper message routing, certain properties must be defined that cannot be set using the simulator in VS Code. Coding is suggested to fully utilize the message routing capabilities.

