# Ticket System Demo for Watson Assistant Integration REST API

A demo Flask REST API for my exam. 
It provides endpoints for creation, update, list and deletion of tickets.

The aim of this app is to server as back end for a Watson Assistant(WA) chatbot. WA can communicate with REST API app via custom extensions. 
A custom extension can be created using app's Swagger documentation(specificaly Open API3). So in the app creation is used [flask_restx](https://flask-restx.readthedocs.io/en/latest/) 
Flask extension for swagger documentation. 

The application uses a DB2 cloud service for persitant store.

It is deployed to a Cloud Foundry service instance which expose its swager documentation and can be seen [here](https://wa2ticketapi.eu-gb.cf.appdomain.cloud/)

You can see the preview of the chatbot [here](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Feu-gb.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fhttps%3A~s~ssoftuni.bg~strainings~s3815~sweb-applications-with-flask-june-2022&integrationID=0a994076-7b3b-418b-8a25-a06ffb293549&region=eu-gb&serviceInstanceID=76b15cb2-6024-46a5-8975-bb6f02b7194e)

Please navigate to bottom right corner to start the chat bot.

![chat bot navigatio - bottom right corner](https://github.com/GMGeor/TicketSystemDemo4WatsonAssistantIntegration/blob/master/img/screenshot_chatbot.JPG)
