# ADS-over-MQTT route configuration files
This folder contains different route configuration files for ADS-over-MQTT. Their main purpose is to demonstrate how to configure ADS-over-MQTT for certain use cases. To activate and use a particular configuration file, please copy the file to the TwinCAT sub directory \3.1\Target\Routes and restart TwinCAT. Please make sure to modify the configuration file to your needs and system environment. 

The following configuration files can be found in this folder:

| Config file | Description |
| ----------- | ----------- |
| [AdsOverMqtt_insecure.xml](AdsOverMqtt_insecure.xml) | Demonstrates how to set up ADS-over-MQTT without any security requirements |
| [AdsOverMqtt_noRetain.xml](AdsOverMqtt_noRetain.xml) | Demonstrates how to use the NoRetain attribute |
| [AdsOverMqtt_secureTlsCa.xml](AdsOverMqtt_secureTlsCa.xml) | Demonstrates how to set up ADS-over-MQTT with TLS and server certificate validation (but no client certificate) |
| [AdsOverMqtt_secureTlsCert.xml](AdsOverMqtt_secureTlsCert.xml) | Demonstrates how to set up ADS-over-MQTT with TLS and client certificate |
| [AdsOverMqtt_secureTlsPsk.xml](AdsOverMqtt_secureTlsPsk.xml) | Demonstrates how to set up ADS-over-MQTT with TLS-PSK and hex key |
| [AdsOverMqtt_secureTlsPsk2.xml](AdsOverMqtt_secureTlsPsk2.xml) | Demonstrates how to set up ADS-over-MQTT with TLS-PSK and password |
| [AdsOverMqtt_tcMqttPluginACL.xml](AdsOverMqtt_tcMqttPluginACL.xml) | Configuration example for TcMqttPlugin Access Control List file |
| [AdsOverMqtt_unidirectional.xml](AdsOverMqtt_unidirectional.xml) | Demonstrates how to use the Unidirectional attribute |
| [AdsOverMqtt_username.xml](AdsOverMqtt_username.xml) | Demonstrates how to set up ADS-over-MQTT with username and password |
