Docker Modules 🚀

A collection of Docker modules and practical examples designed to help developers and DevOps engineers understand containerization concepts and build containerized applications.

This repository demonstrates how to create, build, and run Docker containers for different environments and use cases.

📌 Project Overview

This repository contains multiple Docker-based modules that showcase:

Docker fundamentals

Dockerfile creation

Container management

Image building and optimization

Running applications inside containers

The goal of this project is to provide hands-on learning for Docker and containerization, which are essential skills for modern DevOps and Cloud engineering.

🧰 Technologies Used

Docker

Linux

Shell scripting

Git & GitHub

📂 Repository Structure
docker-modules/
│
├── module-1/
│   ├── Dockerfile
│   ├── app files
│   └── instructions
│
├── module-2/
│   ├── Dockerfile
│   ├── configuration
│   └── scripts
│
└── README.md

Each module demonstrates a different Docker concept such as building images, running containers, or containerizing applications.

⚙️ Prerequisites

Before running the modules, make sure the following are installed:

Docker

Git

Linux or Windows with Docker support

Check Docker installation:

docker --version
🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/Surajsuthar01/docker-modules.git
2️⃣ Navigate to the project directory
cd docker-modules
3️⃣ Build Docker image
docker build -t my-docker-image .
4️⃣ Run the container
docker run -d -p 8080:80 my-docker-image
🐳 Docker Commands Used
Command	Description
docker build	Builds Docker image
docker run	Runs a container
docker ps	Shows running containers
docker images	Lists Docker images
docker stop	Stops container
🎯 Learning Objectives

After completing these modules you will understand:

How Docker containers work

How to write Dockerfiles

Building and running container images

Container lifecycle management

Practical Docker usage in DevOps workflows

📸 Example Output

Example running container:

CONTAINER ID   IMAGE            STATUS        PORTS
abc123         my-docker-app    Up 2 minutes  0.0.0.0:8080->80/tcp
🤝 Contributing

Contributions are welcome!

If you'd like to improve the modules:

Fork the repository

Create a new branch

Commit your changes

Submit a Pull Request

👨‍💻 Author

Suraj Suthar

DevOps Engineer | Cloud Enthusiast

GitHub:
https://github.com/Surajsuthar01

⭐ Support

If you found this repository helpful, please consider starring the repo ⭐
