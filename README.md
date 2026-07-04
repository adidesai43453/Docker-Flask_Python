# Flask Docker Demo 🐳

A simple Flask web application containerized using Docker. This project demonstrates the fundamentals of Docker, including building images, running containers, exposing ports, and creating a reproducible development environment.

## 🚀 Features

* Simple Flask web application
* Dockerized using a custom `Dockerfile`
* Lightweight Python base image (`python:3.12-slim`)
* Easy to build and run
* Beginner-friendly project for learning Docker

---

## 📁 Project Structure

```text
flask-docker-demo/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
├── .gitignore
└── README.md
```

---

## 🛠️ Technologies Used

* Python 3.12
* Flask
* Docker

---

## ▶️ Running the Application Locally

### 1. Clone the repository

```bash
git clone https://github.com/adidesai43453/Docker-Flask_python.git
cd Docker-Flask_python
```

### 2. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Visit:

```
http://localhost:5000
```

---

## 🐳 Running with Docker

### Build the Docker image

```bash
docker build -t flask-demo .
```

### Run the Docker container

```bash
docker run -p 5000:5000 flask-demo
```

Open your browser and visit:

```
http://localhost:5000
```

---

## 📖 Docker Concepts Demonstrated

This project covers the following Docker fundamentals:

* Creating a Docker image
* Running containers
* Dockerfile instructions

  * `FROM`
  * `WORKDIR`
  * `COPY`
  * `RUN`
  * `EXPOSE`
  * `CMD`
* Port mapping
* Image vs Container
* Docker layer caching

---

## 📚 Learning Objectives

This repository was created as part of my Docker learning journey. The goal is to understand Docker by building real projects instead of only learning commands.

Topics planned for future updates include:

* Docker Volumes
* Docker Networks
* Docker Compose
* Environment Variables
* PostgreSQL Integration
* Multi-stage Docker Builds
* Container Deployment

---

## 🤝 Contributing

Contributions, suggestions, and feedback are always welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aditya**

If you found this project helpful, consider giving it a ⭐ on GitHub.
