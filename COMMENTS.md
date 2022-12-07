# Deploying App

To build and deploy the application just run `docker-compose up`

This will automatically build the Docker images for the node app and nginx and start both services after the build is successful

# Reason for Solution Architecture

Docker and Docker-Compose has been used to develop this mock/test environment because of the easy of testing changes to an application and quick feedback in using this architecture.

Another reason for this is that, thesame Docker image used for development can be used for staging and production maintaining consistency across environments to avoid environment drifts and misconfigurations.

Docker Compose also makes it easy to combine multiple services and orchestrate all related services with a simple command to start and stop the services. 