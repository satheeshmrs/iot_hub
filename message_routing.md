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

