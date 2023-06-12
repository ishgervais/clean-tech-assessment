# Newzz (Clean-tech-assessment)

This is a monorepo containing a Laravel server and a React client, configured with Docker and PostgreSQL.

## Screenshots
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/17193327-6b6e-47bd-aac3-0ec06976a91d)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/39f10020-e99a-4fd3-9e9e-45c7a4f211e6)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/e7188c95-97da-4a44-9bfc-869d7a317c19)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/f02a992c-d698-440d-a071-4a7710596148)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/2d9b7021-047a-42f6-bbe7-198e31ae857b)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/38508489-0d60-4168-9276-cc37958c709e)
![image](https://github.com/ishgervais/clean-tech-assessment/assets/54812621/5516008d-fc4b-47d1-8a6d-07485c99d7a4)




## Prerequisites

Before getting started, make sure you have the following tools installed on your system:

- Docker
- Docker Compose

## Getting Started

Follow the steps below to run the application:

1. Clone the repository:

   ```shell
   git clone https://github.com/ishgervais/clean-tech-assessment.git
2. Navigate to the root root

    ```shell
    cd your-repo

## Laravel server

1. Navigate the server

    ```shell
    cd server
    composer install
    ```
2. Generate an application key

    ```shell
    php artisan key:generate
3. Start the server
    ```shell
    php artisan serve

4. Access the server

    ```shell
    Access the React client at http://localhost:8000.

## React client (vite)

1. Navigate and install dependencies

    ```shell
    cd client
    pnpm install
2. Start the server
    ```shell
    pnpm run dev

3. Access the app

    ```shell
    Access the React client at http://localhost:3000.


## Docker compose

1. Navigate to the project root:

    ```shell
    cd clean-tech-assessment
2. Start the Docker containers

    ```shell
    docker-compose up -d

## Docker Compose Configuration
The docker-compose.yml file defines the services and their configurations for the application. It includes:

## A PostgreSQL database service for the Laravel server.
Environment variables for the PostgreSQL service.
Laravel Server
The Laravel server is located in the server directory. It comes with a Dockerfile for containerization.

## Dockerfile
The Dockerfile for the Laravel server is included in the server directory. It sets up the necessary dependencies and exposes port 8000.

## React Client (Vite)
The React client is located in the client directory. It comes with a Dockerfile for containerization.

## Dockerfile
The Dockerfile for the React client is included in the client directory. It installs dependencies and builds the React application, exposing port 3000.

## PostgreSQL Database
The PostgreSQL database is set up as a service using Docker Compose. It is pre-configured with default credentials and accessible on port 5432.

