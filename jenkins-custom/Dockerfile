FROM jenkins/jenkins:lts

USER root

# Install Python and utilities
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    python3-venv \
    curl

# Install Docker CLI
RUN curl -fsSL https://get.docker.com -o get-docker.sh
RUN sh get-docker.sh

USER jenkins