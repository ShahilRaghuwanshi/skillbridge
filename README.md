# SkillBridge

SkillBridge is an intelligent team skill management and project allocation platform. It empowers organizations to map employee skills, track upskilling, and intelligently assign the right people to projects. Built with a modern full stack architecture using Java Spring Boot microservices, SQL databases, and a responsive JavaScript front end, SkillBridge is designed to be scalable, extensible, and easy to deploy.

---

## 🚀 Features

- **Role-Based Access:** Admin, HR, Manager, Employee workflows
- **Skill Profiles:** Employees can add skills, certifications, past project experience; endorse and be endorsed
- **Project Management:** Create projects, define required skills, assign team members
- **Intelligent Team Matching:** Automated, rule-based team recommendations for projects based on skills
- **Upskilling Paths:** Track progress, suggest learning paths, integrate with course providers
- **Analytics Dashboard:** Skill gap analysis, heatmaps, allocation efficiency, upskilling trends
- **Notifications:** Email/in-app notifications for endorsements, project assignments, and more
- **Microservices Architecture:** Modular, scalable, and suitable for real-world enterprise needs
- **API Gateway:** Centralized entry point for all services
- **Secure Authentication:** JWT-based authentication and Spring Security

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot, Spring Security, Spring Cloud Gateway, Microservices, REST APIs
- **Frontend:** HTML, CSS, JavaScript (extendable to React/Vue)
- **Database:** PostgreSQL (default), MySQL supported
- **Containerization:** Docker, Docker Compose
- **Testing:** JUnit (backend), Jest (frontend)
- **API Documentation:** Swagger/OpenAPI
- **DevOps:** GitHub Actions, Docker

---

## 📂 Project Structure

```
skillbridge/
  backend/
    api-gateway/
    user-service/
    skill-service/
    project-service/
    recommendation-service/
    notification-service/
    auth-service/
    common-library/
  frontend/
    public/
    src/
      components/
      pages/
      services/
      utils/
    index.html
    style.css
  docs/
    system-design.md
    erd.png
    sequence-diagrams/
    README.md
  docker/
    docker-compose.yml
```

---

## 🏁 Quick Start

### Prerequisites

- Java 17+
- Node.js 18+
- Docker & Docker Compose
- PostgreSQL or MySQL

### 1. Clone the repository

```bash
git clone https://github.com/ShahilRaghuwanshi/skillbridge.git
cd skillbridge
```

### 2. Setup backend microservices

- Each service is a Spring Boot project (see `/backend`)
- Configure DB credentials in each service's `application.yml`
- Run with Maven or use Docker Compose for all services:

```bash
cd docker
docker-compose up --build
```

### 3. Setup frontend

- Navigate to `/frontend`
- Install dependencies (if using React/Vue):
  ```bash
  npm install
  npm start
  ```
- Or open `public/index.html` directly for vanilla HTML/CSS/JS

### 4. API Documentation

- Each service exposes Swagger UI at `/swagger-ui.html`

---

## 📖 Documentation

- **System Design**: See `/docs/system-design.md`
- **ER Diagrams**: See `/docs/erd.png`
- **Sequence Diagrams**: See `/docs/sequence-diagrams/`
- **API Specifications**: Swagger/OpenAPI per microservice

---

## 👤 Author

- [Shahil Raghuwanshi](https://github.com/ShahilRaghuwanshi)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙋‍♂️ Why SkillBridge?

SkillBridge demonstrates enterprise-level system design, modern Java microservices, and full stack development. It's the perfect portfolio project for job applications, technical interviews, and showcasing your full stack engineering skills!

---
