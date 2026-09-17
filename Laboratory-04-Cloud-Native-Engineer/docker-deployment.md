# Docker Deployment

## Checkpoint 4: Nginx Deployment

### 1. Pull the Nginx Image

Run the following command to download the official Nginx Docker image:

```bash
docker pull nginx
```

This command downloads the official Nginx Docker image.

### 2. Run the Nginx Container

Run the Nginx container using the following command:

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command runs the Nginx container in detached mode (`-d`) and maps port 8080 on the host to port 80 inside the container.

### 3. Test the Nginx Server

Use the following command to test whether the Nginx server is running:

```bash
curl http://localhost:8080
```

This command sends a request to the Nginx server through port `8080`. If the deployment is successful, it displays the Nginx welcome page HTML, confirming that the server is running successfully.
