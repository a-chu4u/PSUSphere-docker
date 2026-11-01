# 🐳 PSUSphere Docker

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Django](https://img.shields.io/badge/Django-6.1-092E20?logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)

## 📌 About the Project

PSUSphere is a Django-based web application for managing students, organizations, colleges, programs, and organization memberships.

This project uses Docker and Docker Compose to make the application easier to build and run on different computers.

## 🛠️ Technologies Used

- Python 3.13
- Django 6.1
- Docker and Docker Compose
- SQLite
- Git and GitHub

## 🚀 How to Run

**For Developers (Build from Source)**

1. Clone this repository.
2. Open a terminal inside the project folder.
3. Run:

   `docker compose up -d --build`

4. Visit http://localhost:8000

**For Clients (Pull from Docker Hub)**

1. Install Docker Desktop.
2. Download the `for_client/docker-compose.yml` file.
3. Open a terminal in the folder containing that file.
4. Run:

   `docker compose up -d`

5. Visit http://localhost:8000

## 📦 Docker Hub

Image: `achuuuu/psusphere-docker:latest`

[View Docker Image](https://hub.docker.com/r/achuuuu/psusphere-docker)

## 📁 Required Files

- `Dockerfile` — Builds the Docker image
- `docker-compose.yml` — Builds and runs the application
- `requirements.txt` — Python dependencies
- `.dockerignore` — Excluded files
- `for_client/docker-compose.yml` — Pulls the image from Docker Hub

---

**PSUSphere Docker | Django Containerization Activity**