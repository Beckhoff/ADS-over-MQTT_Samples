# Mosquitto configuration files
This folder contains configuration examples for the Mosquitto Message Broker. The following configuration files can be found in this folder:

| Config file | Description |
| ----------- | ----------- |
| [mosquitto.acl](mosquitto.acl) | Access Control List (ACL) that shows how to set permissions for ADS devices |
| [mosquitto_insecure.conf](mosquitto_insecure.conf) | Configuration file without any security requirements |
| [mosquitto_insecureWithUserAuth.conf](mosquitto_insecureWithUserAuth.conf) | Configuration file with user authentication |
| [mosquitto_insecureWithUserAuthAcl.conf](mosquitto_insecureWithUserAuthAcl.conf) | Configuration file with user authentication and ACL |
| [mosquitto_secureTlsCert.conf](mosquitto_secureTlsCert.conf) | Configuration file for TLS setup and the requirement of client certificates |
| [mosquitto_secureTlsCertTcMqttPlugin.conf](mosquitto_secureTlsCertTcMqttPlugin.conf) | Configuration file for TLS setup, the requirement of client certificates and import of TcMqttPlugin |
| [mosquitto_secureTlsCertUserAuth.conf](mosquitto_secureTlsCertUserAuth.conf) | Configuration file for TLS setup and user authentication |
| [mosquitto_secureTlsCertUserAuthAcl.conf](mosquitto_secureTlsCertUserAuthAcl.conf) | Configuration file for TLS setup, user authentication and ACL |
| [mosquitto_secureTlsPsk.conf](mosquitto_secureTlsPsk.conf) | Configuration file for TLS setup with a PreSharedKey (PSK) |
| [myKeys.psk](myKeys.psk) | PreSharedKey (PSK) file, required for configurations with TLS-PSK |
| [users.pwd](users.pwd) | User password file, required for configurations with user authentication |

All configuration files are provided as-is and have been added to this repository to help users get started with ADS-over-MQTT. For further information about the Mosquitto message broker and official documentation please visit the [Mosquitto website](https://www.mosquitto.org).
