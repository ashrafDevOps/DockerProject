
This project demonstrates a three-tier application architecture using Docker containers. The architecture consists of three layers:

Backend Layer: Handles application logic and business processing.
Database Layer: Manages the data storage and retrieval operations.
Proxy Layer: Acts as a load balancer or reverse proxy to route requests to the backend services.
By using Docker, we ensure that each tier is isolated in its own container, making the application modular, scalable, and easy to deploy.

Architecture
1. Backend
The backend consists of an application written in Node.js/Python/Java (or any language of your choice).
It handles user requests, processes the business logic, and interacts with the database.
It runs inside a Docker container.
2. Database
We use a relational database like MySQL or PostgreSQL to store data.
The database also runs in a separate Docker container.
3. Proxy (Nginx)
The proxy layer uses Nginx to load balance and route requests to the backend application.
The proxy is configured inside a Docker container to handle incoming HTTP traffic.
Prerequisites
  1-Docker
  2-Docker Compose
  3-Git
