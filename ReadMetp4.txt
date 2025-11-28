1-Create Dockerfile for the Server
1-1-Use a Node base image (node:lts-alpine).
1-2-Copy dependency files (package.json, package-lock.json).
1-3-Install dependencies.
1-4-Copy the rest of the server code.
1-5-Expose the server port (9000).
1-6-Set the startup command (npm start).
1-7-Build the server image:
docker build -t my-server ./server

2️-Create Dockerfile for the Client
2-1-Use a Node base image (node:lts-alpine).
2-2-Copy dependency files.
2-3-Install dependencies.
2-4-Copy the client code.
2-5-Build the app (npm run build).
2-6-Expose the client port (3000).
2-7-Build the client image:
docker build -t my-client ./client

3️-Create Docker Compose File

4-create a docker network
