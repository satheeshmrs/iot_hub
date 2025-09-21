## IOT
- Hostnames
- Endpoint --> IOT devices send message
- Eventhub
- Built-in endpoints

## Message Routing:
- Custom endpoints
- Event hubs, Service Bus Queue, Service Bus Topic, Storage

  ## Storage -->
  SA, Storage V2
  West Europe,

  what is encoding, AVRO and JSON

## Routes
--> How to send message to which endpoint.

  And what we are going to do now is to define route so that the IoT Hub will know which messages to route to which end point.
So let's do that. Click add here, so that we add a new route. And let's name it error route. As you can probably guess, this route is going to define how exactly we are going to route messages to the error endpoint. And therefore we are going to pick here

--> Device deletmetry message

--> Routing Query 
    --> Error Message ($body.status='error')

--> is that we can test messages so that we can make sure that our query actually works.

--> Test the message


## Adding Devices:
1. Devices registeration (Manually)
2. API
3. DeviceID
4.  
