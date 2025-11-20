🎲 Board Game Database – Full-Stack Web Application

A full-stack web platform for exploring board games and sharing reviews. Visitors can browse all games and reviews, while authenticated users can contribute new games and write reviews. Manager–level users receive extended permissions to moderate reviews.

🚀 Features


🌐 Full-Stack Architecture


Built with Spring Boot, Spring MVC, and Thymeleaf for a clean MVC structure.

UI constructed using Thymeleaf templates and styled with Bootstrap.


🔐 Authentication & Authorization


Secure login system powered by Spring Security.

Role-based access:

Non-members: browse games and read reviews.

Users: add new games and submit reviews.

Managers: full review management—edit and delete reviews.


🛠 Application Capabilities


CRUD operations for managing board games and user reviews.

JDBC used for database connectivity.

schema.sql initializes the database schema and seeds sample data.

Reusable Thymeleaf Fragments for shared layout elements (header, footer, navigation).

Organized package structure following Spring MVC best practices.


🧪 Testing


Unit testing implemented with JUnit to ensure reliability.


☁️ Deployment


Application deployed and tested on an AWS EC2 instance.
