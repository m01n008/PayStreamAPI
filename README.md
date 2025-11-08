# PayStreamAPI

A mock payment and fund transfer microservice built with Spring Boot to simulate payment processing workflows. Features rate-limiting to prevent abuse and asynchronous transaction processing for better performance.

## Features

- Simulated payment and fund transfer endpoints  
- Rate-limiting using Bucket4j to control API usage  
- Asynchronous transaction processing to improve responsiveness  
- RESTful API design with input validation and error handling  
- Dockerized deployment for consistent environments  

## Tech Stack

- Java 17  
- Spring Boot  
- Bucket4j for rate limiting  
- Docker  

## Getting Started

### Prerequisites

- Java 17+  
- Docker  
- Maven  

### Running Locally

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/PayStreamAPI.git
   cd PayStreamAPI
Build the project:

bash
Copy code
mvn clean install
Run the application:

bash
Copy code
mvn spring-boot:run
Running with Docker
Build the Docker image:

bash
Copy code
docker build -t paystreamapi .
Run the Docker container:

bash
Copy code
docker run -p 8081:8080 paystreamapi
API Endpoints
/api/payments/initiate - Initiate a mock payment

/api/payments/status - Check payment status

/api/transfers - Simulate fund transfers

License
MIT License
