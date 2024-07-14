
# Sim Service Project

## Overview

The Sim Service Project is a full-stack application designed to manage SIM customers and validate their details efficiently. By leveraging Java, Spring Boot, REST APIs, Docker, and a frontend built with React and TypeScript, this project achieved a 30% increase in operational efficiency.

## Features

- **Customer Management:** View and manage all registered SIM customers.
- **SIM Validation:** Validate SIM cards and retrieve data seamlessly.
- **ID Proof Validation:** Verify customer ID proofs accurately.
- **Offer Display:** Display current offers associated with SIM cards.

## Technologies

- **Backend:** Java, Spring Boot, REST API
- **Frontend:** React, TypeScript
- **Containerization:** Docker
- **Database:** postgresql

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/sim-service-project.git
   cd sim-service-project
   ```

2. **Docker Setup:**
   - Build and run the Docker containers:
     ```bash
     docker-compose up --build
     ```

3. **Backend Setup:**
   - If not using Docker, navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Build the backend project:
     ```bash
     mvn clean install
     ```
   - Run the Spring Boot application:
     ```bash
     mvn spring-boot:run
     ```

4. **Frontend Setup:**
   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the React application:
     ```bash
     npm start
     ```

## Usage

- Access the application at `http://localhost:3000`.
- Use the customer management interface to view and manage SIM customers.
- Validate SIM cards and ID proofs through the respective sections.
- Check out the latest offers on the offers page.

## Contributing

Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README provides an attractive, structured, and concise summary of your project for potential employers or collaborators viewing your GitHub repository.
