# Microservices Demo Application

This Java microservices demo application includes an API Gateway, Eureka Netflix, Department Service, and Employee Service. These services can be used to manage department and employee data for a company.

## Getting Started

To run this application in a local development environment, you can follow the steps below.

### Requirements

- Java 11 or higher
- Maven
- Docker (optional)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/microservices-demo.git
   cd microservices-demo
2. Build the project and install dependencies:
  mvn clean install
3. Start each service.
4. After the services have started, you can visit http://localhost:8761 to access the Eureka Netflix Console. Here, you should see the registered services.
5. You can access all services combined with the API Gateway.

# Contributing

If you'd like to contribute to this project, please open an issue for a new feature or bug fix before submitting a pull request. We welcome all contributions.

# License

This README provides a comprehensive guide for understanding how to use the project and how to contribute to it. Please make sure to customize this template according to the specific requirements and structure of your project. Also, don't forget to add an appropriate license file to provide information about your project's licensing terms.
