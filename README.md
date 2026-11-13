# Mining Intelligence Platform

The collective objective is to deliver an enterprise-grade, scalable, and extensible **Mining Intelligence Platform**. Real-time operational visibility, AI-driven insights, predictive analytics, safety monitoring, and blast intelligence must all be accessible from a single dashboard.

## 🎯 Final Integration Goal

At project completion, all six modules must interoperate through **secure REST APIs and shared authentication**, feeding into the Mining Operations Dashboard — the executive control centre of the entire platform.

## 🏗️ Architecture & Infrastructure

The platform is built using a modern, scalable tech stack:

### Services and Databases
- **PostgreSQL**: Relational database for structured operational data.
- **MongoDB**: NoSQL database for unstructured telemetry and logs.

### Core Structure
- `frontend/`: Next.js web application providing the executive command centre UI with Tailwind CSS.
- `backend/`: Core API services handling business logic, telemetry ingestion, and communication with the databases.
- `model/`: AI/ML models responsible for rock classification and predictive insights.
- `docs/`: Additional project documentation.

## 🛠️ Getting Started

### Prerequisites

Ensure you have [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) installed on your machine.

### Infrastructure Setup

Start the core infrastructure (PostgreSQL, MongoDB, MinIO, Redis) using Docker Compose:

```bash
docker-compose up -d
```

### Services Available on Localhost:
- **PostgreSQL**: `localhost:5432`
- **MongoDB**: `localhost:27017`

### Development

To run the frontend dashboard:

```bash
cd frontend
npm install
npm run dev
```

The frontend will be accessible at [http://localhost:3000](http://localhost:3000).

## 📄 License

© 2026 Mining Intelligence Platform. All rights reserved.
