# 📋 Task Management Application

A full-featured task management application with a **React** frontend and **.NET** backend.

---

## 🛠 Technologies

### 🔹 Backend
- **.NET 9**
- **ASP.NET Core Web API**
- **PostgreSQL**
- **Entity Framework Core**
- **MediatR**
- **FluentValidation**
- **CQRS** pattern
- **Clean Architecture**
- **Serilog** for structured logging

### 🔹 Frontend
- **React**
- **TypeScript**
- **Vite**
- **Axios**
- **MobX** for state management
- **Feature-Sliced Design (FSD)** architecture

---

## 📦 Requirements

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/notyado/Taskify.git
cd ./Taskify
```

### 2. Build and run with Docker Compose
```bash
docker-compose up --build
```

### 3. Access the application

| Service | URL |
|---------|-----|
| 🌐 Frontend | [http://localhost:3000](http://localhost:3000) |
| ⚙️ Backend API | [http://localhost:5000](http://localhost:5000) |
| 📚 Swagger UI | [http://localhost:5000/swagger](http://localhost:5000/swagger) |
| 🗄️ PostgreSQL | `localhost:5432` |

---

## 🛑 Stopping the Project

### Stop containers
```bash
docker-compose down
```

### Stop containers and remove volumes (⚠️ deletes database data)
```bash
docker-compose down -v
```

---

## 📁 Project Structure (Overview)

```
📦 Taskify
 ┣ 📂 backend          # .NET Web API (Clean Architecture)
 ┣ 📂 frontend         # React + TypeScript (FSD)
 ┣ 📜 docker-compose.yml
 ┗ 📄 README.md
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
---

*Built with ❤️ using .NET 9 and React*
