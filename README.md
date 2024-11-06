# Airbnb Clone - Backend (Spring Boot 3)

This is the backend for an Airbnb clone project built with Spring Boot 3, following a domain-driven design architecture. It provides booking management for travelers, reservation management for landlords, and features authentication and authorization with OAuth2 using Auth0.

## Key Features
- 📅 **Booking Management**: Travelers can book available properties.
- 🏠 **Reservation Management**: Landlords can manage property reservations.
- 🔍 **Search Functionality**: Search for properties based on various criteria like location, date, number of guests, beds, etc.
- 🔐 **Authentication & Authorization**: Role-based access control using Auth0 (OAuth2).
- 🏢 **Domain-Driven Design (DDD)**: The application is structured following DDD principles.

## Prerequisites
Ensure you have the following tools installed:
- [JDK 21](https://adoptium.net/temurin/releases/)
- [PostgreSQL](https://www.postgresql.org/download/)
- An IDE such as [VSCode](https://code.visualstudio.com/download) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)

## Getting Started

### 1. Clone the repository

\`\`\`bash
git clone https://github.com/arodriguez78/AirbnbSpringBackend
cd AirbnbSpringBackend
\`\`\`

### 2. Configuration
Before running the project, set up the environment variables for Auth0.

- \`AUTH0_CLIENT_ID\`: Your Auth0 Client ID
- \`AUTH0_CLIENT_SECRET\`: Your Auth0 Client Secret

You can add these variables either via command line or in your IDE.

### 3. Running the Project

#### Using Maven
\`\`\`bash
./mvnw spring-boot:run -Dspring-boot.run.arguments="--AUTH0_CLIENT_ID= --AUTH0_CLIENT_SECRET="
\`\`\`

## Database Setup

This project uses PostgreSQL. Ensure that you have PostgreSQL installed and running on your machine. You can modify the \`application.properties\` or \`application.yml\` file to set your PostgreSQL credentials (e.g., username, password, database name).


