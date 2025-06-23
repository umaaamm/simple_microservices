# 🧩 Simple — Contact & Order Microservice with Go, gRPC, REST, Docker and MongoDB

This is a Contact microservice built with **Go**, using both **gRPC** and **RESTful API (Fiber)**, backed by **MongoDB**. Designed to be modular, scalable, and suitable for use in a microservice architecture.

## 🔧 Features

- 📞 Manage contacts (ID, name, phone number)
- 🛠 Dual API interface:
  - gRPC Server (port `50051`)
  - REST API SRV_CONTACT with Fiber (port `8080`)
  - REST API SRV_ORDER with Fiber (port `8082`)
- 📦 MongoDB for persistent storage
- 🐳 Docker & Docker Compose support

---

## 🚀 Tech Stack

- Language: [Go](https://golang.org/)
- REST Framework: [Fiber](https://gofiber.io/)
- RPC: [gRPC](https://grpc.io/)
- Database: [MongoDB](https://www.mongodb.com/)
- Container: [Docker](https://www.docker.com/)
- gRPC Gateway support (optional)

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/umaaamm/srv_contact_microservices.git
git clone https://github.com/umaaamm/srv_order_microservices.git
git clone https://github.com/umaaamm/simple_microservices.git

cd simple_microservices
