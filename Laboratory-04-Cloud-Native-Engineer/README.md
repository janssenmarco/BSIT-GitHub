# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

This laboratory activity focuses on understanding the differences between traditional Virtual Machines (VMs) and containers. It also provides hands-on experience using Docker through the KillerCoda Playground.

## Objectives

- Differentiate between Virtual Machines and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute fundamental Docker CLI commands.
- Pull, run, manage, and terminate a containerized Nginx application.
- Create technical documentation using Markdown.
- Continue developing a GitHub Cloud Computing Portfolio.

## Docker Commands Executed
- docker --version
- docker info
- docker pull nginx
- docker run -d --name nginx-server -p 8080:80 nginx
- docker ps
- curl http://localhost:8080
- docker stop nginx-server
- docker ps -a
- docker rm nginx-server

## Skills Learned

Through this activity, I learned how to use Docker to pull images, create and run containers, map ports, test a web server, and manage the container lifecycle. I also learned how to document technical procedures and results using Markdown and GitHub.

## Challenges Encountered

One challenge was understanding how Docker containers use port mapping to make services accessible from the host environment. I also had to make sure that the Nginx container was properly stopped and removed after testing. Following the Docker commands step by step helped me understand the container lifecycle and complete the deployment successfully.
