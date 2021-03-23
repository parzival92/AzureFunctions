#### 1. Create Azure function project with no template

##### npm install durable-functions

The most basic Durable Functions app contains three functions:

* **Orchestrator function - describes a workflow that orchestrates other functions.**
* **Activity function - called by the orchestrator function, performs work, and optionally returns a value.**
* **Client function - a regular Azure Function that starts an orchestrator function. This example uses an HTTP triggered function.**

##### 2. Create Orchestrator function(Durable Functions orchestrator)

##### 3. Create Orchestrator Activity function(Durable Functions activity)

##### 4. Create client function(Durable Functions HTTP starter)

##### 5. F5 to debug locally,Will prompt you for storage account or you can use local emulator storage.

##### npm install @types/node --save-dev for tsc 

