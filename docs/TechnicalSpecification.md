# Technical Specification:

## 1. Architecture
- The application is built using React Native, offering a cross-platform solution for Android and iOS.
- Communication with the back-end is facilitated via API calls to a Spring Boot Java application.

## 2. Development Environment
- Developers use commonly available development tools and IDEs for React Native.
- Version control is managed using Git.
- Coding standards and conventions are adhered to for code consistency.

## 3. Front-End
- The front-end is developed using React Native, utilizing its built-in component libraries for native UI elements.
- Tailwind CSS may be used for UI styling, with consideration for leveraging React Native's native look and feel.

## 4. Back-End
- The back-end is developed in Spring Boot Java, running on a Linux server.
- The Spring Boot framework provides robust support for API development and scalability.

## 5. Database
- MariaDB is the chosen database management system for data storage.
- The database schema is designed to efficiently store image-related data.

## 6. Authentication and Authorization
- User authentication is handled through the issuance of JWT tokens.
- Users obtain API keys upon successful login, granting access to API endpoints.

## 7. Scalability
- The application is designed to handle a reasonable number of users and concurrent requests.
- Scaling considerations are minimal due to the simplicity of the app.

## 8. Deployment
- The application is hosted on a Linux server.
- Deployment scripts and procedures ensure smooth updates and maintenance.

## 9. Monitoring and Logging
- Monitoring and logging mechanisms are implemented to track key events and activities within the app.
- Image capture and upload events are logged for auditing and error tracking.

## 10. Maintenance
- Ongoing maintenance is performed by Charl Cronje.
- Maintenance tasks include staying up-to-date with app store requirements, ensuring compatibility with new Android and iOS versions, and addressing any issues that may arise.
