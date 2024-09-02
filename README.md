# Backend Part of a Social Media App

The app designed for emergency help, providing a platform for users to quickly connect with emergency responders, volunteers, and community members in times of crisis. The app enables real-time location sharing and provides a platform for donations.

## Microservice Architecture
- System has two microservices and a gateway for them:
    - User Service
    - Post Service
      
- These services communicate with each other using FeignClient, which is an HttpClient.
- Each microservice uses a layered architecture.
- Each microservice has its own separate MongoDB database.
