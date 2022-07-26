A backend web service for a simple bank. It will provide APIs for the frontend to do the following things:

    Create and manage bank accounts.

    Record all balance changes to each of the accounts.

    Perform a money transfer between 2 accounts.
    
Based on the Udemy course from https://www.udemy.com/course/backend-master-class-golang-postgresql-kubernetes/
Majore lessons included:

    - Designing database schema using DBML and automatically generate SQL code from it
    - Automatically generating Golang code to interact with the database
    - Developing a RESTful backend web service using the Gin framework
    - Securing the APIs with user authentication, JWT and PASETO (PASETO was implemented in the final version)
    - Building a minimal Docker image for deployment and using Docker-compose for development
    - Setting up Github Action to automatically build and deploy the app to AWS Kubernetes cluster
    - Registering a domain and configuring Kubernetes ingress to route traffic to the web service
    - Enabling automatic issue & renew TLS certificate for the domain with Let's Encrypt
