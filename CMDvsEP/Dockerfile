# Example 1:
# # Use Ubuntu 20.04 as base image
# FROM ubuntu:20.04

# # Install Nginx, net-tools, and curl
# RUN apt update && \
# apt install -y net-tools && \
# apt install -y curl

# # Set working directory to /etc
# WORKDIR /etc

# # Define default command
# ENTRYPOINT ["hostname"]
# #CMD ["bash"]

# Example 2:
# Use an official lightweight Python image as base
FROM python:3.9-slim

# Set the working directory
WORKDIR /usr/src/app

# The ENTRYPOINT specifies the executable to run - 'ping' in this case.
ENTRYPOINT ["ping"]

# The CMD specifies the default argument to the ENTRYPOINT - 'localhost' here.
CMD ["localhost"]
