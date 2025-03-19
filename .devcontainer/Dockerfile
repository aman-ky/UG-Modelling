FROM mcr.microsoft.com/devcontainers/python:3.11

# Install additional OS packages if needed (optional)
# RUN apt-get update && apt-get install -y <additional-packages>

# Copy requirements.txt and install Python packages
COPY requirements.txt /tmp/requirements.txt
RUN pip install --upgrade pip \
    && pip install -r /tmp/requirements.txt
