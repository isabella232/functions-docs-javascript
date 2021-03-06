# Azure Functions binding examples in JavaScript

The following samples are used as a basis for [Azure Functions 2.x+ binding](https://docs.microsoft.com/azure/azure-functions/functions-triggers-bindings#supported-bindings) examples in JavaScript.

## Settings and configuration

The *local.settings.example.json* file is provided for your convenience. Rename the file to *local.settings.json* and add your own connection and API values before trying to run the examples in this repo.

If you're using Visual Studio Code, you can use the [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) extension with the *routes.http* file. This file gives you the ability to call sample functions with a single click inside VS Code.

## Samples

The following samples are available in this repo.

| Name | Description  | Trigger | Input | Output |
|------|--------------|---------|-------|--------|
| [HttpTrigger](HttpTrigger) | Triggered by an HTTP request. | Http | N/A | Http |
| [HttpTriggerRoute](HttpTriggerRoute) | Triggered by an HTTP request, writes a queue message. | Http | N/A | Queue |
| [HttpAndTable](HttpAndTable) | Triggered by an HTTP request, writes a queue message. | Http | Table | Http |
| [QueueTrigger](QueueTrigger) | Reads a queue message | Queue | Queue | N/A |
