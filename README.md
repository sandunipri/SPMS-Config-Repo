# Smart Parking System – Config Repository

This is the centralized configuration repository for the **Smart Parking Management System**, designed to manage and serve externalized configuration properties to all microservices through the **Spring Cloud Config Server**.

Each configuration file is written in YAML format and maps to a corresponding microservice. The Config Server reads these files and delivers the configuration dynamically to services at runtime.

## Repository Structure

SPMS-Config-Repo/
- application.yml
- eureka-server.yml 
- user-service.yml
- vehicle-service.yml
- parking-space-service.yml
- parking-reservation-service.yml 
- security-service.yml

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/SPMS-Config-Repo.git
