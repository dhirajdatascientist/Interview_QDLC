## Docker

1. **Introduction and Basics**
   1. What is Docker and why is it popular?
   2. How does Docker differ from traditional virtualization?
   3. What is a Docker container?

2. **Core Components and Concepts**
   1. What is a Docker image and how does it differ from a Docker container?
   2. Describe the differences between Docker Hub and Docker Registry.
   3. What is a Dockerfile? Can you explain its basic structure?
   4. What is the Docker daemon?
   5. How do you version Docker images?

3. **Docker Commands**
   1. How do you run a Docker container?
   2. How do you stop a running container?
   3. How can you list all the containers, both running and stopped, on your system?
   4. How can you remove a Docker image from your system?
   5. How would you copy files from a Docker container to the host system?

4. **Networking and Storage**
   1. How do Docker containers communicate with each other?
   2. What are Docker networks? Name some types of Docker networks.
   3. How do you create a volume in Docker and attach it to a container?
   4. How does Docker handle data persistence?

5. **Advanced Concepts**
   1. What is Docker Compose? Why is it useful?
   2. What are the differences between Docker Swarm and Kubernetes?
   3. How do you manage secrets in Docker?
   4. What is a multi-stage build in Docker?

6. **Best Practices and Security**
   1. How can you ensure your Docker images and containers are secure?
   2. What are some best practices for writing Dockerfiles?
   3. How can you minimize the size of a Docker image?
   4. What is the principle of least privilege and how does it apply to Docker?

7. **Use Cases and Scenarios**
   1. How would you handle a situation where a Docker container needs to be updated without losing its data?
   2. Describe a real-world scenario where you have used Docker to solve a problem.
   3. How would you deploy a multi-container application using Docker?

8. **Diagnostics and Troubleshooting**
   1. How can you monitor the resource usage of a Docker container?
   2. What do you do when a Docker container crashes?
   3. How can you view the logs of a running container?

## Flask

1. **Introduction and Basics**
   1. What is Flask? How does it differ from other web frameworks like Django or Pyramid?
   2. What is a micro-framework?
   3. Describe the Flask application structure.

2. **Core Components and Concepts**
   1. What is a route in Flask?
   2. How do you define URL patterns in Flask?
   3. Explain the concept of request and response in Flask.
   4. How can you handle query parameters in Flask?

3. **Templates and Views**
   1. What templating engine does Flask use by default?
   2. How do you pass context data to templates?
   3. What is Jinja2? Can you provide a basic example?
   4. Explain the difference between a function view and a class-based view in Flask.

4. **Forms and Data Handling**
   1. How do you handle form submissions in Flask?
   2. What is Flask-WTF? How is it used in conjunction with Flask forms?
   3. How do you handle file uploads in Flask?
   4. What is a CSRF token and why is it important?

5. **Database Interaction**
   1. How can Flask integrate with databases?
   2. What is Flask-SQLAlchemy? How does it simplify database operations?
   3. How do you handle database migrations in Flask?

6. **Extensions and Plugins**
   1. What is Flask-Login? How is it used for user authentication?
   2. Name a few popular Flask extensions and their purposes.
   3. How do you handle user sessions in Flask?

7. **Deployment and Production**
   1. How do you deploy a Flask application to production?
   2. What is a WSGI server? Name some popular WSGI servers compatible with Flask.
   3. How would you ensure the security of a Flask application in a production environment?

8. **Best Practices and Patterns**
   1. How do you structure a large Flask application?
   2. What are blueprints in Flask?
   3. Describe the Factory pattern in Flask and why it's beneficial.

9. **Advanced Concepts**
   1. How do you create an API using Flask?
   2. How can Flask be used in conjunction with WebSockets?
   3. What are Flask context globals like `request`, `session`, and `g`?

10. **Diagnostics and Troubleshooting**
   1. How do you debug a Flask application?
   2. How can you log errors or events in Flask?
   3. Describe Flask's error handling mechanism.