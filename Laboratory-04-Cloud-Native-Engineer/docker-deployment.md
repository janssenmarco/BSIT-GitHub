# Docker Deployment

## Checkpoint 4: Nginx Deployment

### 1. Pull the Nginx Image

```bash
docker pull nginx
This command downloads the official Nginx Docker image.

Run the Nginx Container

docker run -d --name nginx-server -p 8080:80 nginx

This command runs the Nginx container in detached mode and maps port 8080 on the host to port 80 in the container.


curl http://localhost:8080

This command tests the Nginx server and displays the Nginx welcome page to confirm that it is running successfully.
