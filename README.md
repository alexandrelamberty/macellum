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

## Requirements

- [Docker](https://www.docker.com/)

## Usage

1. Start the complete stack and initialize the services:

    ```shell
    docker compose up -d .
    ```

2. Register the main admin account:

    Copy the pairing key from the configuration created before. Navigate to the web client at [http://localhost:3000/auth/register?key=PAIRING_KEY](http://localhost:3000/auth/register?key=PAIRING_KEY) and replace `PAIRING_KEY` in the url with your key. You will be
