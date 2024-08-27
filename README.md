# **irlhub-api**

## **Overview**

This is the `irlhub-api` project, a Fastify-based web application that provides a robust and scalable API for managing real-world events and activities.

## **Features**

- **Event Management**: The application provides a set of API endpoints for managing events, including creating, updating, and deleting events.
- **User Authentication**: The application includes user authentication and authorization for secure access to the API.
- **CORS Support**: The application includes CORS support for cross-origin resource sharing.
- **Database Integration**: The application uses Prisma as an ORM to interact with the database.
- **Email Sending**: The application uses Nodemailer to send emails.
- **Date and Time Handling**: The application uses Dayjs for date and time handling.
- **Validation and Serialization**: The application uses Zod for validation and serialization.

## **Technologies Used**

- **Fastify**: A fast and low-latency web framework for Node.js.
- **Prisma**: A modern ORM for Node.js and TypeScript.
- **Dayjs**: A lightweight JavaScript date library.
- **Nodemailer**: A popular email sending library for Node.js.
- **Zod**: A TypeScript-first schema validation library.
- **@fastify/cors**: A Fastify plugin for CORS support.
- **@fastify/type-provider-zod**: A Fastify plugin for Zod validation and serialization.

## **Getting Started**

To get started with the application, follow these steps:

1. Clone the repository.
2. Install the dependencies using `npm install` or `yarn install`.
3. Create a `.env` file in the root directory and add the following environment variables:
   - `DATABASE_URL`: The connection URL for the database.
   - `EMAIL_HOST`: The hostname of the email server.
   - `EMAIL_PORT`: The port of the email server.
   - `EMAIL_USERNAME`: The username for the email server.
   - `EMAIL_PASSWORD`: The password for the email server.
   - `EMAIL_FROM`: The email address to send emails from.
4. Start the application using `npm start` or `yarn start`.

## **API Documentation**

API documentation is available at [insert API documentation URL].

## **Contributing**

Contributions are welcome! Please submit a pull request with your changes.

## **License**

[Insert license information]
