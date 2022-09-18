# Eventbrite
EventBrite_MicroServices
Is an EventBrite website that allows users to create, browse, register and promote events.
It is an end-to-end shopping e-commerce like site where users can register,login to get Events.


This project is built using Microservices architecture, Docker Linux containers, Swagger, Entity framework, Redis, RabbitMQ, IdentityServer4, ASP.NET Core 
 and C#.                                                

List of API's and Containers in the project:
                     PicController
                     EventCatalogApi
                     TokenServiceApi
                     CartApi
                     OrderApi
                     WebMvc
                     Mssqlserver
                     RedisCache
                     RabbitMQ
 


Microservice EventCatalog was created to the project, also added MSMSqL to load data for API's in microservice.

WebMVC(Client for microservices) is added to the project which is to integrate with API's for User interface experience
.
TokenService API(microservice) that is on Identity service is added to authenticate & authorize User's deatils.

Microservice Cart was modified and it is using using RedisCache to save/update the user's cart and integrated with client(Web).

Microservice Order was added to the project and saving all orders to MSSQL Database.

Logging all the messages while creating cart and saving orders.

Integrated with StripeAPI for test Payment.

Communication between services via messaging using RabbitMQ.


Assignment 3a: Testing EventCatalog service and Pic srvice with Postman - https://youtu.be/OWZtvKkP0Z8

Assignment 3b : Swagger Documentation, Built MVC client for eventbrite, Added TokenService Microservice, Integrated with the client - https://youtu.be/oYooH315pHQ

Assignment 3c: Demo : https://youtu.be/B23E2mRf7Xc

