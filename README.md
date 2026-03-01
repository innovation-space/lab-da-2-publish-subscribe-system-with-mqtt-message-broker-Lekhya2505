# Smart Campus Monitoring using MQTT and Node-RED

## Objective
To design and implement a publish–subscribe system using MQTT protocol and Node-RED.

## MQTT Broker
broker.hivemq.com (Port 1883)

## Publishers
1. campus/blockA/temperature (QoS 1)
2. campus/blockB/airquality (QoS 2)

## Wildcard Subscriber
Subscribed using:
campus/+/+

## Status Topic
campus/status  
Retained message enabled to store latest system state.

## QoS Demonstration
- QoS 1 → At least once delivery
- QoS 2 → Exactly once delivery

## Dashboard
- Temperature Gauge
- Air Quality Line Chart
- System Status Display

## Conclusion
This project demonstrates MQTT publish–subscribe architecture with QoS levels, wildcard subscriptions, retained messages, and live dashboard visualization.
