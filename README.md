# CTSE-Assignment

## ☁️ Cloud Computing Assignment – DevOps Microservice

This project demonstrates the implementation of a secure and scalable microservice using modern **DevOps** and **cloud-native practices**. CI/CD is automated with **GitHub Actions**, and the application is deployed on **AWS ECS (Fargate)** using containerized infrastructure.

The microservice is developed using **Node.js and Express**, offering secure **user authentication** and **role-based access control**, making it suitable for real-world multi-user systems.

---

## 🔐 Key Features

- 🔑 **JWT-based authentication** with user roles: `admin`, `instructor`, `learner`
- 🐳 Containerized using **Docker**
- 🔁 **CI/CD pipeline** with **GitHub Actions**:
  - Builds and pushes Docker images to Docker Hub
  - Automatically deploys to AWS ECS upon changes to `main` branch
- ☁️ Deployed on **AWS ECS with Fargate** (serverless containers)
- 🔐 Security best practices:
  - IAM roles for least-privilege access
  - Custom **security groups** to restrict inbound traffic
  - Secrets managed via **GitHub Secrets**
- 🛡️ Integrated **Snyk** to scan for vulnerabilities in:
  - Node.js dependencies (`package.json`)
  - Docker image layers
- 📦 Modular, RESTful API architecture with clear route separation

---

## 🧰 Technologies Used

| Layer              | Tech Stack                      |
|--------------------|---------------------------------|
| Backend            | Node.js, Express.js             |
| Authentication     | JWT, bcrypt                     |
| Containerization   | Docker                          |
| Cloud Platform     | AWS ECS + Fargate               |
| CI/CD              | GitHub Actions                  |
| Security           | IAM, Security Groups, Snyk      |
| Dev Tools          | Postman, Git, GitHub            |
| Validation         | express-validator               |
| Database           | MongoDB (cloud-hosted via Atlas)|

---

## 🧠 Learning Outcomes Demonstrated

- **LO1** – Design and implement a secure microservice
- **LO2** – Apply cloud computing and deployment strategies
- **LO3** – Implement CI/CD using modern DevOps tools
- **LO4** – Apply security best practices and DevSecOps principles

---

## ✅ Conclusion

Through this project, we successfully designed, developed, containerized, and deployed a secure microservice using modern DevOps tools and cloud technologies. We implemented authentication, role-based access, and CI/CD pipelines, while enforcing security practices like secret management and vulnerability scanning via Snyk. This hands-on experience has deepened our understanding of microservices architecture, cloud infrastructure (AWS), and automation workflows, aligning directly with the learning outcomes of the CTSE module.

---

Thank you! 
Happy coding!!!!!
