---
tags: [Getting started]
---

# User-management-service-overview


- User management service(UMS) is a robust service with OAuth functionality.
- This service provides functionality for authentication with third party authentication (i.e google, facebook, twitter)
seamlessly.
>


###### UMS CHANNELS
This is a list of the channels readily available in the UMS service: 
1. Web
2. Mobile
3. Web_Service
4. {{ApplicationName}}-admin - this channel is created by default when an application is created on the UMS service.

> Other **platforms** that is not listed above can be added on UMS based on request
> 
##### UMS AUTHENTICATION TYPES
They are various authentication type that the UMS service provides peculiar to applications.
1. Email and password 
2. Username and password
3. PhoneNumber and Pin
4. Email Only i.e when integrating with platforms that already has an in-app authentication.
5. PhoneNumber Only 
6. Username Only

> **UMS provides specific for each of the channels registered with the application.**

##### UMS ROLES
The UMS Service has roles defined for every user. 
1. Admin
2. SuperAdmin
3. User
4. Support

> By default, every user created will have a user role

### **IMPORTANT NOTICE**
- Before an application can use this service, the application needs to register with the UMS service.
- After registration, this application gets an apiKey to have access to the resources/ functionalities of the user management service.

- After the application has been registered successfully, you can register channels/clients(e.g Mobile, Web) for this application
- Every platform tied to this application will also get a thier apiKey's as well.


> ** It is required that any integrating application connects to the UMS service with a web service/API.**