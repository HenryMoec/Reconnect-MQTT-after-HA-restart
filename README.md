Setup for automatically MQTT reconnection after Home Assistant restart

1. Add Code from configuration.yaml in your configuration.yaml. Make sure that you insert the following informations:
   - IP: IP of your Zendure device
   - SN: serial number of your Zendure device
   - IP MQTT BROKER: IP number of your MQTT broker
   - MQTTUSERNAME: your MQTT broker username
   - MQTTPASSWORT: your MQTT broker passwort

2. Create a new automation in HA and add Code from cautomation.yaml in your automation

Now after restart of Home Assistant your device will automatically reconnected to MQTT Broker.
