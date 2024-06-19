# Express TypeScript Backend

## Description
This is a simple backend server built with Express and TypeScript. It provides APIs to submit and read form submissions, using a JSON file as a database.

## Endpoints
- `GET /ping`: Returns `true` to check if the server is running.
- `POST /submit`: Submits a form with parameters `name`, `email`, `phone`, `github_link`, and `stopwatch_time`.
- `GET /read`: Reads a form submission at a given index (query parameter `index`).

## Running the Server
1. Clone the repository:
    ```sh
    git clone <repository_url>
    cd express-ts-backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Run the server:
    ```sh
    npm start
    ```

The server will be running on `http://localhost:3000`.
