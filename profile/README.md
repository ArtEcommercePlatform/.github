# Artztall 🎨

Artztall is a platform where artisans can showcase and sell their paintings, host auctions for their artwork, and buyers can purchase or bid on these creations. Our mission is to empower artists and connect them with art enthusiasts around the globe.

## Features

- **Microservices Architecture**:

  - User Service: Manage user authentication and profiles.
  - Product Service: Handle painting listings and related details.
  - Order Service: Manage buyer orders and transactions.
  - Payment Service: Integrated with Stripe for secure payment processing.
  - Notification Service: Send updates and notifications to users.
  - Auction Service: Host and manage painting auctions.

- **Technologies Used**:

  - **Backend**: Spring Boot for microservices.
  - **Frontend**: Vite, React, and TypeScript.
  - **Databases**: Each microservice has its own MongoDB database for scalability and data isolation.
  - **Styling**: Tailwind CSS for modern and responsive design.
  - **Icons**: Lucide Icons for a clean and consistent UI.

- **Infrastructure**:

  - API Gateway for unified entry points to services.
  - Eureka Service Discovery for service registration and discovery.
  - JWT Authentication for secure access control.
  - Swagger Documentation available for each service.

## Getting Started

### Prerequisites

1. **Backend**:

   - Install Java 17+.
   - Set up MongoDB instances for each service.

2. **Frontend**:

   - Node.js (v16+).
   - Install dependencies with `npm install`.

3. **Stripe**:

   - Create a Stripe account and obtain your API keys.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Artztall/organization-repo.git
   ```

2. Navigate to individual services and install dependencies as needed.

3. Start the services:

   ```bash
   # Example for user-service
   cd user-service
   ./mvnw spring-boot:run
   ```

4. Run the frontend:

   ```bash
   cd frontend
   npm run dev
   ```

5. Access the application at `http://localhost:3000`.

## Contributing

We welcome contributions to make Artztall better! Here’s how you can get involved:

- Report bugs or request features via [Issues](https://github.com/Artztall/organization-repo/issues).
- Fork the repository and submit a pull request with improvements.
- Check our [Contribution Guidelines](CONTRIBUTING.md) for more details.

## Documentation

- Find detailed documentation for each service and setup guide in the `/docs` folder of the repository.
- Swagger documentation is available for each service to explore and test APIs interactively.

## Community

Join our community to connect with other contributors and artisans:

- **Slack**: [Join our Slack channel](https://join.slack.com/Artztall).
- **Discussions**: Engage in conversations via [GitHub Discussions](https://github.com/Artztall/organization-repo/discussions).

## License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by the Artztall Team.

