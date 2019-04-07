FROM nginx:1.15

# Install as root
USER root

# Install dependencies
RUN apt-get update && apt-get install -y nano

# Change current user
USER www
