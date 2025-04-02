# QuestIQ

QuestIQ is a dynamic and interactive quiz application developed using **Spring Boot** following a **Microservices Architecture**. The application ensures high availability, scalability, and efficient load balancing to provide a seamless quiz-taking experience.

## 🎯 Features
- 🏗 **Microservices Architecture** - Each service is independently scalable and loosely coupled.
- ⚖ **Load Balancing** - Maintains efficient request distribution across microservices.
- 🔄 **Service Discovery** - Uses Eureka for dynamic service discovery.
- 💾 **Database Management** - Utilizes PostgreSQL/MySQL for structured quiz data storage.
- 🔗 **API Gateway** - Secure and optimized routing using Spring Cloud Gateway.
- 📊 **Real-Time Leaderboard** - Tracks and displays quiz scores dynamically.
- 🛡 **Authentication & Authorization** - Implemented using JWT security.
- 📡 **RESTful APIs** - Well-structured APIs to handle quizzes, users, and scoring.
- 🌍 **Frontend Compatibility** - Can be integrated with any frontend framework (React, Angular, etc.).

## 🏗 Tech Stack
- **Backend:** Java, Spring Boot
- **Database:** PostgreSQL/MySQL
- **Security:** JWT Authentication
- **Load Balancer:** Spring Cloud LoadBalancer
- **Containerization:** Docker (optional)

## 📂 Microservices Structure
- **User Service** - Manages user registration, login, and authentication.
- **Quiz Service** - Handles quiz creation, questions, and categories.
- **Leaderboard Service** - Stores and retrieves user scores and rankings.
- **Gateway Service** - Acts as the entry point for the system, ensuring secure API routing.
- **Config Server** - Centralized configuration management for all microservices.
- **Discovery Service** - Eureka-based service discovery for dynamic scaling.

## ⚡ Getting Started
### Prerequisites
- Java 17+
- Spring Boot
- PostgreSQL/MySQL
- Docker (Optional, for containerized deployment)


## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, create feature branches, and submit pull requests.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

🚀 **Let's build the best quiz experience together!**
