# Mission Reflection

## 1. Docker Container vs. Virtual Machine Setup

A Docker container is much faster to start and set up compared to installing an operating system on a Virtual Machine. A container uses the host operating system's kernel and only needs the required application and dependencies, while a Virtual Machine needs a complete guest operating system. Because of this, containers are lightweight and can start within seconds, while setting up a Virtual Machine can take much more time and resources.

## 2. Port Mapping

Port mapping such as `-p 8080:80` is necessary because it connects a port on the host machine to a port inside the container. In this activity, Nginx runs on port 80 inside the container, while port 8080 is exposed on the host. This allows users to access the Nginx web server through `http://localhost:8080`.

## 3. Docker rm and Container Data

The `docker rm` command removes a container completely. Any data stored only inside the container's writable layer is deleted when the container is removed. Data that needs to remain available should be stored using Docker volumes or other persistent storage methods.

## 4. Containerization and DevOps

Containerization can improve collaboration between software developers and IT operations teams because applications can run in consistent environments. Developers can package an application with its dependencies, while operations teams can deploy the same container without having to manually configure the environment. This can make development, testing, and deployment more consistent and efficient.

## 5. GitHub Portfolio Evolution

My GitHub portfolio is evolving as I continue documenting the skills and activities I learn in my IT studies. This activity helped me add practical experience with Docker, container deployment, port mapping, and container lifecycle management. By keeping my projects, documentation, and screenshots organized in GitHub, I can show my progress and build a portfolio that reflects both my technical skills and hands-on experience.
