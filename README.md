# config-server
Configuration server

Eeach microservice can download its configuration data using configuration server.
This dramatically simplifies the management of many microservices by centralizing their 
configuration in one location and provides the ability to “live” refresh a microservice’s 
configuration without redeploying the service. As a bonus, Spring Cloud Config provides 
out-of-the-box support for storing/reading configuration from Git repositories, 
giving you a full audit history of changes in one location.
