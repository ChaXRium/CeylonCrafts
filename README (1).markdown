# CeylonCrafts

## Project Overview
**CeylonCrafts** is a desktop-based e-commerce platform developed by a team of 10 students for the CS1073 - Object-Oriented Programming with C# module. Built using C# and .NET Framework, it empowers Sri Lankan artisans to showcase crafts, manage orders, track materials, and facilitate direct sales. The **Cultural Storytelling Module** enhances engagement by sharing each craft’s cultural significance.

**Submission Date**: Last Week of July 2025  
**Group Members**: [To be finalized by 3rd August 2025]

## Problem Statement
Sri Lankan artisans face challenges like limited digital presence and inefficient order management. CeylonCrafts provides a tailored e-commerce solution to boost visibility, streamline operations, and promote sustainable growth.

## Features
- **Artisan Profiles**: Showcase crafts with images, descriptions, and cultural context.
- **Order Management**: Track order statuses, payments, and delivery schedules.
- **Material Sourcing Tracker**: Manage raw material inventories and ensure sustainable procurement.
- **Direct Sales**: Secure transactions between artisans and customers.
- **Cultural Storytelling Module**: Multimedia narratives highlighting craft heritage.

## System Requirements
### Functional Requirements
- User authentication (login, registration, password recovery).
- CRUD operations for profiles, listings, orders, and inventories.
- Search and filter crafts by category, price, or artisan.
- Order processing with status updates (e.g., pending, shipped).
- Material tracker with low inventory alerts.
- Cultural storytelling for enriched product descriptions.

### Non-Functional Requirements
- **Performance**: Supports 100 concurrent users with <2-second response times.
- **Security**: Uses encryption for data storage and transmission.
- **Usability**: Intuitive GUI with clear navigation and accessibility.
- **Scalability**: Supports expansion to thousands of users.

## System Design
The platform uses a **three-tier architecture**:
- **Presentation Layer**: Windows Forms or WPF for user interaction.
- **Business Logic Layer**: C# classes with OOP principles (encapsulation, inheritance, polymorphism, abstraction).
- **Data Access Layer**: SQLite or SQL Server with Entity Framework.

### OOP Concepts
- **Encapsulation**: Protects sensitive data with private fields and public methods.
- **Inheritance**: Base classes (e.g., `User`) with derived artisan/customer classes.
- **Polymorphism**: Interfaces for flexible order and payment processing.
- **Abstraction**: Simplifies complex operations via abstract classes.

## Development Process
The project follows an **Agile methodology** with two-week sprints, executed by our 10-member team:
1. **Planning (Week 1)**: Finalize roles, set up Git repository, define requirements.
2. **Design (Weeks 2-3)**: Create UML diagrams and database schema.
3. **Implementation (Weeks 4-7)**: Develop GUI, logic, and database in C#.
4. **Testing (Week 8)**: Unit, integration, and user acceptance testing.
5. **Documentation and Video (Week 9)**: Finalize report and demo video.

## Expected Outcomes
- Empower artisans with a digital marketplace.
- Enhance market reach and operational efficiency.
- Engage customers via cultural storytelling.
- Deliver a scalable system with over 40 hours of team effort.

## Resource Requirements
- **Development Tools**: Visual Studio 2022, .NET Framework, Entity Framework, SQLite/SQL Server.
- **Version Control**: Git and GitHub.
- **Testing Tools**: NUnit for unit testing, manual UI/UX testing.
- **Hardware**: Windows PCs for development and testing.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/ChaXRium/CeylonCrafts.git
   ```
2. Open in **Visual Studio 2022**.
3. Install **.NET Framework** and dependencies (e.g., Entity Framework).
4. Configure database connection (SQLite/SQL Server).
5. Build and run the solution.

## Usage
1. Launch and log in/register as an artisan or customer.
2. Artisans: Create profiles, add crafts, manage orders/materials.
3. Customers: Browse crafts, place orders, view cultural narratives.
4. Use material tracker for inventory monitoring and alerts.

## Contributing
Contributions are welcome, especially from team members. To contribute:
1. Fork the repository.
2. Create a branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add feature"`).
4. Push to branch (`git push origin feature-branch`).
5. Create a pull request for team review.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
Contact the team via GitHub Issues or the group coordinator (details by 3rd August 2025).

## Acknowledgements
Developed by a team of 10 students for CS1073. We thank our instructors and peers for their guidance.