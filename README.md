# Happening

**Discover your city. Find your people. Make it happen.**

Happening is a full-stack event discovery and booking platform that helps users explore local events, connect with new experiences, and book events across different categories.

## Features

- **Event Discovery:** Browse, search, and filter events by category and city.
- **Event Booking:** View event details, pricing, and availability.
- **User Accounts:** Register, sign in, and manage bookings.
- **Role-Based Access:** Separate functionality for users, organizers, and administrators.
- **Categories and Cities:** Discover events based on interests and locations.
- **Reviews and Favorites:** Save events and share feedback.
- **Responsive Interface:** Navigate events through a clean, user-friendly interface.

## Tech Stack

| Component | Technologies |
|---|---|
| Frontend | React, Vite, JavaScript, CSS |
| Backend | Java, Spring Boot, REST API |
| Database | MySQL |
| Security | Spring Security, JWT |
| ORM | Spring Data JPA, Hibernate |
| Tools | Maven, Docker, Git, GitHub |

## Architecture

React Frontend → Spring Boot REST API → MySQL Database

## Getting Started

### Prerequisites

- Java JDK
- Node.js and npm
- MySQL 8.x
- Maven
- Docker Desktop (optional)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/adulasreenidhi/happening-platform.git
   cd happening-platform
   ```

2. Create a local `.env` file using `.env.example` as a reference. Configure the required database credentials and JWT secret.

3. Start the application using Docker Compose:

   ```bash
   docker compose up --build -d
   ```

4. Access the application:

   - **Frontend:** `http://localhost:8081`
   - **Backend:** `http://localhost:8080`

### Development Mode

- Start the Spring Boot backend using Maven from the `backend` directory.
- Install frontend dependencies by running `npm install` inside `frontend`.
- Start the React development server with `npm run dev`.

## Security

- JWT-based authentication.
- Role-based authorization.
- Environment-based configuration for credentials and secrets.

Never commit actual environment files, passwords, or JWT secrets to version control.

## Author

**Sreenidhi Adula**

GitHub: [@adulasreenidhi](https://github.com/adulasreenidhi)

## License

No license has been specified yet.
