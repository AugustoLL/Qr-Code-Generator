[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](https://opensource.org/licenses/MIT)
![Docker Compose](https://img.shields.io/badge/docker-compose?style=for-the-badge&logo=docker&logoColor=%23f45283&color=%230898e8)


# Docker Compose Sample for QR Code Generator

This repository contains a Docker Compose file for running a sample QR code generator application using `qr-code-generator-backend` and `qr-code-generator-frontend` services. 

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository and move to the new directory
```sh
git clone https://github.com/AugustoLL/Qr-Code-Generator.git
```
2. Move to the new directory
```sh
cd Qr-Code-Generator
```
3. Create a .env file
```sh
FRONTEND_PORT=3000
BACKEND_PORT=8080
CACHE_EXPIRATION_TIME=3600
MAX_CACHE_SIZE=100
API_URL=http://localhost:8080/api/generate?
```
4. Run Docker Compose.
```sh
docker-compose up -d
```

## Services

This sample includes two services:

- `qr-code-generator-backend`: This service runs the Node.js backend application for generating QR codes.
- `qr-code-generator-frontend`: This service runs the Vue frontend application for the QR code generator.

## Accessing the Application

By default, the `qr-code-generator-frontend` service is configured to run on port 3000. You can access the application by navigating to `http://localhost:3000` in your web browser.


Here are the links to the repositories for each service:

- [Frontend Repository](https://github.com/AugustoLL/Qr-Code-Generator-Frontend)
- [Backend Repository](https://github.com/AugustoLL/Qr-Code-Generator-Backend)

## License

This project is licensed under the [MIT License](LICENSE).