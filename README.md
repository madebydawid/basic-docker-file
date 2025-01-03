# Basic Docker File

## Project Overview
In this project, you will write a basic Dockerfile to create a Docker image. When this Docker image is run, it should print “Hello, Captain!” to the console before exiting.

## Requirements

For this project to work you need to have Docker installed on your system. This can be done by downloading and installing Docker from their official website found [here](https://www.docker.com/products/docker-desktop/).

## Instructions
### 1. Clone the repository:

```bash
git clone https://github.com/madebydawid/basic-docker-file.git
cd basic-docker-file
```

### 2. Build the Docker image:

The command below will build the Docker image using the Dockerfile in the root directory:

```bash
docker build -t hello-captain .
```

### 3. Run the Docker container:
To run the container use following command:

```bash
docker run hello-captain
```

### 4. Output:

After running the container, you should see the following output in your terminal:

```bash
Hello, Captain!
```












---
[Link to Roadmap.sh](https://roadmap.sh/projects/basic-dockerfile)