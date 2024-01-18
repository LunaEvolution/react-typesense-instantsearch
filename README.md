# Typesense

Brief project description.

## Prerequisites

Make sure you have the following installed on your machine:

- Docker
- Node.js
- Yarn

## Getting Started

### Step 1: Set up Docker Compose

1. Open a terminal in the project directory.
2. Run the following command to start Docker Compose:

    ```bash
    docker-compose up -d
    ```

### Step 2: Start Typesense Server

1. Open a new terminal window.
2. Run the following command to start the Typesense server:

    ```bash
    yarn start-typesense-server
    ```

### Step 3: Populate Typesense Index

1. Open another terminal window.
2. Run the following command to populate the Typesense index:

    ```bash
    yarn populate
    ```

### Step 4: Start the Project

1. Finally, start the React project:

    ```bash
    yarn start
    ```

This will launch the development server, and you can view your project in your web browser at `http://localhost:3000`.

## Available Scripts

In the project directory, you can run the following scripts:

- `start`: Run the development server.
- `build`: Build the project for production.
- `test`: Run tests.
- `eject`: Eject from Create React App.
- `start-typesense-server`: Start the Typesense server.
- `populate`: Populate the Typesense index.

## Additional Information

Any additional information or special instructions can be added here.

# by Zied Bousnina
