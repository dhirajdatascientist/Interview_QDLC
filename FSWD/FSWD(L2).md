## Docker

1. **Introduction and Basics**
   1. **What is Docker and why is it popular?**  
      Docker is a platform for containerizing applications, popular for its efficiency and portability.
      
   2. **How does Docker differ from traditional virtualization?**  
      Docker virtualizes at the OS level, while traditional virtualization does it at the hardware level.
      
   3. **What is a Docker container?**  
      A Docker container is a lightweight, standalone executable software package that includes everything needed to run a piece of software.

2. **Core Components and Concepts**
   1. **What is a Docker image and how does it differ from a Docker container?**  
      A Docker image is a blueprint for a container, while a container is a running instance of an image.
      
   2. **Describe the differences between Docker Hub and Docker Registry.**  
      Docker Hub is a cloud-based registry service while Docker Registry is an open-source server-side tool to store and distribute Docker images.
      
   3. **What is a Dockerfile? Can you explain its basic structure?**  
      A Dockerfile is a script with instructions to create a Docker image, containing commands like `FROM`, `RUN`, and `CMD`.
      
   4. **What is the Docker daemon?**  
      It's a background process that manages Docker containers on a system.
      
   5. **How do you version Docker images?**  
      Using tags, typically in the format `repository:tag`.

3. **Docker Commands**
   1. **How do you run a Docker container?**  
      `docker run <image_name>`
      
   2. **How do you stop a running container?**  
      `docker stop <container_id>`
      
   3. **How can you list all the containers, both running and stopped, on your system?**  
      `docker ps -a`
      
   4. **How can you remove a Docker image from your system?**  
      `docker rmi <image_id>`
      
   5. **How would you copy files from a Docker container to the host system?**  
      `docker cp <container_id>:<path_in_container> <host_path>`

4. **Networking and Storage**
   1. **How do Docker containers communicate with each other?**  
      Via Docker networks.
      
   2. **What are Docker networks? Name some types of Docker networks.**  
      Docker networks enable container communication; types include `bridge`, `host`, and `overlay`.
      
   3. **How do you create a volume in Docker and attach it to a container?**  
      `docker volume create <volume_name>` and `docker run -v <volume_name>:<path_in_container> <image_name>`
      
   4. **How does Docker handle data persistence?**  
      Through volumes, which persist data outside of containers.

5. **Advanced Concepts**
   1. **What is Docker Compose? Why is it useful?**  
      It's a tool to define and manage multi-container Docker applications, useful for simplifying complex setups.
      
   2. **What are the differences between Docker Swarm and Kubernetes?**  
      Both are orchestration tools; Swarm is Docker-native and simpler, while Kubernetes is more powerful and feature-rich.
      
   3. **How do you manage secrets in Docker?**  
      Using `docker secret` commands in Docker Swarm.
      
   4. **What is a multi-stage build in Docker?**  
      A method to optimize Dockerfiles by using multiple intermediate images to reduce final image size.

6. **Best Practices and Security**
   1. **How can you ensure your Docker images and containers are secure?**  
      Regularly update, minimize base images, and use trusted sources.
      
   2. **What are some best practices for writing Dockerfiles?**  
      Keep them short, use official base images, and avoid storing secrets.
      
   3. **How can you minimize the size of a Docker image?**  
      Use alpine images, multi-stage builds, and remove unnecessary files.
      
   4. **What is the principle of least privilege and how does it apply to Docker?**  
      Only grant the minimum necessary permissions; in Docker, avoid running containers as root.

7. **Use Cases and Scenarios**
   1. **How would you handle a situation where a Docker container needs to be updated without losing its data?**  
      Use Docker volumes to persist data and update the container.
      
   2. **Describe a real-world scenario where you have used Docker to solve a problem.**  
      Docker is used to create a consistent development environment, ensuring code runs the same everywhere.
      
   3. **How would you deploy a multi-container application using Docker?**  
      Use Docker Compose or orchestration tools like Kubernetes.

8. **Diagnostics and Troubleshooting**
   1. **How can you monitor the resource usage of a Docker container?**  
      Use `docker stats`.
      
   2. **What do you do when a Docker container crashes?**  
      Check logs with `docker logs <container_id>`.
      
   3. **How can you view the logs of a running container?**  
      `docker logs <container_id>`.
