# Docker Compose Sample for QR Code Generator

This repository contains a Docker Compose file for running a sample QR code generator application using `qr-code-generator-backend` and `qr-code-generator-frontend` services. 

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository.
2. Run `docker-compose up -d` in the root directory of this repository.

## Services

This sample includes two services:

- `qr-code-generator-backend`: This service runs the Node.js backend application for generating QR codes.
- `qr-code-generator-frontend`: This service runs the React frontend application for the QR code generator.

## Accessing the Application

By default, the `qr-code-generator-frontend` service is configured to run on port 3000. You can access the application by navigating to `http://localhost:3000` in your web browser.

Please note that this repository does not include the source code for the `qr-code-generator-backend` and `qr-code-generator-frontend` services. You will need to clone those repositories separately and configure them according to your needs.


Here are the links to the repositories:

- [Frontend Repository](https://github.com/AugustoLL/Qr-Code-Generator-Frontend)
- [Backend Repository](https://github.com/AugustoLL/Qr-Code-Generator-Backend)

## License

This project is licensed under the [MIT License](LICENSE).