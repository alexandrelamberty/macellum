# Macellum

Grocery Management System designed to streamline the operations of a grocery store. The system encompasses various key components:

1. Client Management:
    - Efficiently manage client information, appointment.

2. Product Management:
    - Create new products.
    - Manage stock levels.
    - Facilitate product movement within the store.
    - Enable seamless product purchase by clients.
    - Automated price update ?

3. Order Management:
    - Validate and create orders for a smooth workflow.

4. Invoice Generation:
    - Generate invoices for transactions.

5. Reporting:
    - Detailed reports for better insights.
    - Sales reports to track revenue.
    - Order reports for monitoring transactions.
    - Client reports for customer analysis.

This Grocery Management System is designed to enhance the overall functionality and organization of a grocery store, providing a user-friendly interface for efficient day-to-day operations.

## Project Structure

- **Main Project ([macellum](https://github.com/alexandrelamberty/macellum/))**:
  
  Acting as the core repository of the project, "macellum" serves as the central hub for consolidating all components of the system as submodules.

- **Infrastructure ([macellum-infrastructure](https://github.com/alexandrelamberty/macellum/))**:
  
  This submodule includes the necessary infrastructure configurations using Docker Compose. It defines the services required to run the complete stack, including backend server APIs, frontend web applications, databases, and any other dependencies.

- **API Specification ([macellum-api-spec](https://github.com/alexandrelamberty/macellum-api-spec/))**:
  
  Here lies the OpenAPI specification for the project's RESTful API. This document serves as the contract between frontend and backend developers, detailing all endpoints, request/response formats, and authentication requirements. Additionally, the documentation for the API is available [here](https://alexandrelamberty.github.io/macellum-api-spec).

- **Client TypeScript API Library ([macellum-api-client-typescript](https://github.com/alexandrelamberty/macellum-api-client-lib-typescript/))**:
  
  This submodule houses the TypeScript API library generated from the API specification. It provides a convenient way to interact with the backend services from TypeScript applications.

- **API Server ([macellum-api-server](https://github.com/alexandrelamberty/macellum-api-server))**:
  
  This submodule contains the source code for a Golang implementation of the API specification. It provides the backend server application logic to handle API requests and business logic. The server is build using Fiber.

- **Web Application ([macellum-web-app](https://github.com/alexandrelamberty/macellum-web-app))**:
  
  Within this submodule resides the web application built using React and shadcn/ui.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

See the [Macellum Infrastructure](https://github.com/alexandrelamberty/macellum-infrastructure) project.
