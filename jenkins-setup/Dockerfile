# Use official Jenkins LTS base image
FROM jenkins/jenkins:lts

# Switch to root user to install extra packages
USER root

# Optional: install Docker CLI if you want Jenkins to run Docker commands
RUN apt-get update && \
    apt-get install -y docker.io

# Expose Jenkins UI port
EXPOSE 8080

# Default command to run Jenkins (already included in base image)
# So no need to define CMD manually
