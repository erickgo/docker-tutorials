# docker-tutorials

| **Topic**               | **Topics Covered**                                                                                                         | **Labs**                                                                                                      |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **Introduction to Docker** | - What is Docker, and why use it? <br> - Key concepts: Images, Containers, Registries, Orchestration <br> - Docker ecosystem | - Install Docker on your system. <br> - Run your first container and explore basic Docker CLI commands.       |
| **Building Docker Images**  | - Writing Dockerfiles and best practices <br> - Multi-stage builds <br> - Tagging and pushing images to a registry         | - Create a Dockerfile for a simple app (e.g., Flask/Node.js). <br> - Build, tag, and push the image to a registry. |
| **Networking & Storage**    | - Docker networking: Bridge, host, and overlay <br> - Persistent storage: Bind mounts vs. named volumes                   | - Create a custom network for containers. <br> - Use volumes to persist data for a database container.         |
| **Orchestration**           | - Overview and use cases of Docker Compose <br> - Defining multi-service applications in `docker-compose.yml`              | - Write a `docker-compose.yml` file for a web app with a database. <br> - Deploy the app using Docker Compose. |
| **Production Best Practices** | - Security best practices (e.g., non-root users) <br> - Optimizing images <br> - Resource constraints: CPU and memory      | - Create a secure Dockerfile using non-root users. <br> - Configure resource limits for a container.           |
| **Debugging & Logging**      | - Inspecting containers and troubleshooting <br> - Managing logs and integrating with logging tools (e.g., Loki)          | - Debug a broken containerized app. <br> - Forward logs to a logging tool.                                    |
| **Advanced Topics**          | - Multi-architecture builds with Buildx <br> - Docker Swarm or Kubernetes basics <br> - CI/CD pipeline integration        | - Build a multi-architecture image. <br> - Set up a CI/CD pipeline to build and deploy a Dockerized app.      |
| **Wrap-Up & Evaluation**     | - Review of key concepts <br> - Q&A and participant feedback                                                              | - Final project: Deploy a full-stack app using Docker Compose.                                                |
