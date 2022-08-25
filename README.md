# TicketSystemDemo4WatsonAssistantIntegration REST API

A demo Flask REST API for my exam. 
It provides endpoints for creation, update, list and deletion of tickets.

The aim of this app is to server as back end for a Watson Assistant(WA) chatbot. WA can communicate with REST API app via custom extensions. 
A custom extension can be created using app's Swagger documentation(specificaly Open API3). So in the app creation is used [flask_restx](https://flask-restx.readthedocs.io/en/latest/) 
Flask extension for swagger documentation. 

The application uses a DB2 cloud service for persitant store. 
It is deployed to a Cloud Foundry service instance which expose its swager documentation and can be seen [here](https://wa2ticketapi.eu-gb.cf.appdomain.cloud/)
