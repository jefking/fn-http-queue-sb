# Azure Function: HTTP (API) -> Azure Service Bus Queue

Sets up an HTTP POST API; the message body will then be added to an Azure Service Bus Queue for downstream processing.

## Quick Deploy to Azure

[![Deploy to Azure](http://azuredeploy.net/deploybutton.svg)](https://azuredeploy.net/)

## Application settings

- **ServiceBus** - Azure Service Bus Connection String for the Queue.