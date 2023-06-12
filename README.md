# Monorepo with Laravel and React

This is a monorepo containing a Laravel server and a React client, configured with Docker and PostgreSQL.

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
    npm run dev

3. Access the app

    ```shell
    Access the React client at http://localhost:3000.


