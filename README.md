# rust-rest-api

> Rust REST API: Blazing-fast REST API with Axum, SQLx, JWT, and PostgreSQL

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Rust, Warp, PostgreSQL, Tokio, Docker

## 🏗️ Architecture
Three-tier architecture: Rust, Warp backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rust-rest-api
cd rust-rest-api

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
