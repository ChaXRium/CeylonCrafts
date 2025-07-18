# Local Artisan & Craft Market Platform

## Project Overview
The **Local Artisan & Craft Market Platform** is a desktop-based e-commerce and management system designed to empower Sri Lankan artisans. Developed as a group project for the **CS1073 - Object-Oriented Programming with C#** module, this project is a collaborative effort by a team of 10 students. Built using **C#** and the **.NET Framework**, the platform leverages Object-Oriented Programming (OOP) principles to enable artisans to showcase traditional crafts, manage orders, track material sourcing, and facilitate direct sales to customers. A unique **Cultural Storytelling Module** enhances consumer engagement by sharing the cultural significance and production process of each craft.

**Submission Date**: Last Week of July 2025  
**Group Members**: [To be finalized by 3rd August 2025]

## Problem Statement
Sri Lankan artisans face challenges such as limited digital presence, inefficient order management, and lack of streamlined tools for showcasing their crafts and managing supply chains. This platform addresses these issues by providing a tailored e-commerce solution to enhance visibility, streamline operations, and promote sustainable growth for artisans.

## Features
- **Artisan Profiles**: Artisans can create profiles to showcase their crafts with images, descriptions, and cultural context.
- **Order Management**: Supports customers placing orders and artisans tracking order statuses, payments, and delivery schedules.
- **Material Sourcing Tracker**: Tools to manage raw material inventories, track sourcing details, and ensure sustainable procurement.
- **Direct Sales**: Secure transaction processing for direct sales between artisans and customers.
- **Cultural Storytelling Module**: Allows artisans to attach multimedia narratives (text and images) to each craft, highlighting its cultural significance and production process.

## System Requirements
### Functional Requirements
- User authentication (login, registration, password recovery).
- CRUD operations for artisan profiles, product listings, orders, and material inventories.
- Search and filter functionality for browsing crafts by category, price, or artisan.
- Order processing with status updates (e.g., pending, confirmed, shipped).
- Material sourcing tracker with low inventory alerts.
- Cultural storytelling module for enriched product descriptions.

### Non-Functional Requirements
- **Performance**: Supports up to 100 concurrent users with response times under 2 seconds.
- **Security**: Implements encryption for secure data storage and transmission.
- **Usability**: Provides an intuitive GUI with clear navigation and accessibility features.
- **Scalability**: Designed to support future expansion to thousands of artisans and customers.

## System Design
The platform follows a **three-tier architecture**:
- **Presentation Layer**: Built using Windows Forms or WPF for user interaction.
- **Business Logic Layer**: C# classes implementing OOP principles (encapsulation, inheritance, polymorphism, abstraction) for application logic.
- **Data Access Layer**: Integrates with a relational database (SQLite or SQL Server) using Entity Framework for data persistence.

### OOP Concepts
- **Encapsulation**: Protects sensitive data (e.g., user credentials) using private fields and public methods.
- **Inheritance**: Uses base classes (e.g., `User`) with derived classes for artisans and customers.
- **Polymorphism**: Implements interfaces for flexible order processing and payment methods.
- **Abstraction**: Simplifies complex operations (e.g., material sourcing) through abstract classes.

## Development Process
The project follows an **Agile methodology** with two-week sprints, collaboratively executed by our team of 10:
1. **Planning (Week 1)**: Finalize group roles, set up Git repository, and define requirements.
2. **Design (Weeks 2-3)**: Create UML diagrams (class, use case, sequence) and database schema.
3. **Implementation (Weeks 4-7)**: Develop the application in C#, integrating GUI, business logic, and database, with tasks distributed among team members.
4. **Testing (Week 8)**: Conduct unit, integration, and user acceptance testing to ensure functionality and reliability.
5. **Documentation and Video (Week 9)**: Prepare the final report and demonstration video for submission.

## Expected Outcomes
- Empower Sri Lankan artisans with a dedicated digital marketplace.
- Improve market reach and operational efficiency.
- Enhance customer engagement through the cultural storytelling module.
- Deliver a scalable, maintainable system reflecting over 40 hours of collective work by the 10-member team.

## Resource Requirements
- **Development Tools**: Visual Studio 2022, .NET Framework, Entity Framework, SQLite or SQL Server.
- **Version Control**: Git and GitHub for collaborative development among the team.
- **Testing Tools**: NUnit for unit testing, manual testing for UI/UX validation.
- **Hardware**: Standard PCs with Windows OS for development and testing.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/[your-repo]/local-artisan-craft-platform.git
   ```
2. Open the project in **Visual Studio 2022**.
3. Ensure the **.NET Framework** and required dependencies (e.g., Entity Framework) are installed.
4. Configure the database connection (SQLite or SQL Server) in the project settings.
5. Build and run the solution.

## Usage
1. Launch the application and log in or register as an artisan or customer.
2. Artisans can create profiles, add crafts, and manage orders/materials.
3. Customers can browse crafts, place orders, and view cultural narratives.
4. Use the material sourcing tracker to monitor inventory levels and receive alerts.

## Contributing
Contributions are welcome, particularly from project team members. To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request for review by the team.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For inquiries, please contact the project team via the GitHub Issues section or reach out to the group coordinator (details to be finalized by 3rd August 2025).

## Acknowledgements
This project is a collaborative effort by a dedicated team of 10 students in the CS1073 - Object-Oriented Programming with C# module. We thank our instructors and peers for their guidance and support throughout the development process.