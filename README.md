# Dockerized React Static Login Page (Development Mode)

A Dockerized **React static login page** built with **Create React App** and configured for development mode using Node.js inside a container. This setup ensures a consistent development environment, enables **hot reloading**, and streamlines local testing.

---

## 🚀 Features
- **Dockerized** for consistent setup across machines
- **Hot Reloading** for instant UI updates during development
- Built with **Create React App**
- Runs inside a **Node.js** container
- Simple, clean static **login page UI**

---

## 🛠️ Prerequisites
- [Docker](https://www.docker.com/get-started) installed on your system

---

## 📂 Project Structure
LOGIN-SIGNUP/
├── node_modules/
├── public/
├── screenshots/
├── src/
├── .dockerignore
├── .gitignore
├── Dockerfile
├── package-lock.json
├── package.json
└── README.md


---

## 🐳 Running the App with Docker

### 1️⃣ Build the Docker image
```bash
docker build -t react-docker-login-page .
docker run -p 3000:3000 docker-demo
http://localhost:3000

## 📸 Screenshots

### 1️⃣ Login Page Running on Port 3000
![Login Page](https://github.com/omkarnerale18/dockerized-react-login-page/blob/master/screenshots/Login%20page.jpg?raw=etru)

### 2️⃣ Docker Desktop - Running Container
![Docker Container](https://github.com/your-username/your-repo-name/blob/main/screenshots/docker-container.png?raw=true)

### 3️⃣ Docker Desktop - Project Image
![Docker Image](https://github.com/your-username/your-repo-name/blob/main/screenshots/docker-image.png?raw=true)

### 4️⃣ Docker Commands in Terminal (Part 1)
![Docker Terminal Commands Part 1](https://github.com/your-username/your-repo-name/blob/main/screenshots/docker-terminal-1.png?raw=true)

### 5️⃣ Docker Commands in Terminal (Part 2)
![Docker Terminal Commands Part 2](https://github.com/your-username/your-repo-name/blob/main/screenshots/docker-terminal-2.png?raw=true)




