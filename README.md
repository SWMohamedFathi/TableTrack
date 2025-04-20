# 🍽️ TableTrack – Restaurant Booking System

TableTrack is a full-featured restaurant booking system that allows users to discover restaurants, make reservations, and manage bookings easily. Built with a modern fullstack architecture, it includes authentication, role-based access, real-time updates, and admin dashboard.

---

## 🚀 Features

- 🔐 User Authentication & Authorization (JWT)
- 🏢 Admin dashboard to manage restaurants & bookings
- 📅 Bookings system with availability check
- 🗺️ Interactive map to locate restaurants (Leaflet.js)
- 📧 Email notifications for confirmations and reminders
- ⚙️ RESTful API with full CRUD operations
- 🧠 Redis caching for performance boost
- 🧪 Unit testing (Jest)
- 🐳 Dockerized app
- 🛡️ Rate limiting & input validation
- 🚀 CI/CD pipeline with GitHub Actions

---

## 🧱 Tech Stack

| Layer        | Technology                    |
|--------------|-------------------------------|
| Frontend     | Angular, HTML, SCSS, RxJS     |
| Backend      | NestJS (Node.js), TypeScript  |
| Database     | PostgreSQL, Redis             |
| Authentication | JWT, Bcrypt                  |
| DevOps       | Docker, GitHub Actions        |
| Mapping      | Leaflet.js + OpenStreetMap    |
| Testing      | Jest, Supertest               |

---

## 🧭 Project Structure

```bash
TableTrack/
├── backend/
│   ├── src/
│   │   ├── modules/
│   │   ├── auth/
│   │   └── main.ts
├── frontend/
│   └── src/
│       ├── app/
│       ├── components/
│       └── environments/
├── docker/
│   ├── Dockerfile
│   └── docker-compose.yml
└── .github/
    └── workflows/
        └── ci.yml
