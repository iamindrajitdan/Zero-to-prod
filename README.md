# Zero-to-prod

This repository contains a full-stack web application project structured for deployment using Docker and Docker Compose. It includes a backend server and a frontend client, both set up to run in isolated containers.

## Project Structure
- `backend/`: Contains the backend server code (e.g., Node.js, Express).
- `frontend/`: Contains the frontend client code (e.g., React).
- `docker-compose.yml`: Docker Compose configuration file to orchestrate the multi-container application.
- `.dockerignore`: Files and directories to be ignored by Docker during the build process.

## Prerequisites
- Docker installed on your machine.
- Docker Compose installed on your machine.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/iamindrajitdan/Zero-to-prod.git
    cd Zero-to-prod
    ```
2. Build and run the application using Docker Compose:
    ```bash
    docker-compose up --build
    ```
3. Access the application:
    -Frontend:
    Open your web browser and navigate to `http://your-ip:3000`.
    -Backend:
    The backend server will be accessible at `http://your-ip:4000`.

## Stopping the Application
To stop the application, run:
```bash
docker-compose down
```
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Inspired by best practices in Docker and full-stack development.
- Thanks to the open-source community for their contributions and support.

