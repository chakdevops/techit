# Use Ubuntu 20.04 as base image
FROM ubuntu:20.04

# Install Nginx, net-tools, and curl
RUN apt update && \
apt install -y net-tools && \
apt install -y curl

# Set working directory to /etc
WORKDIR /etc

# Define default command
CMD ["bash"]