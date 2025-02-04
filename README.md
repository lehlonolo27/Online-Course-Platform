# Online-Course-Enrollment-Platform (In Progress)

## Project Overview
The "Online Course Enrollment" platform is designed to provide a seamless and intuitive exprience for users to enroll in various courses. The application allows instructors to create and manage courses, while students can browse, enroll, and complete courses at their own pace or participate in live sessions.

## Key feautures
User Management: Secure user registration, authentication and profile management using Azure AD B2C.
Course Management: Instructions can create courses with multiple sessions, including videos, documents and other materials.
Enrollment:Students can enroll in courses, track progress and recieve certification upon completion.
Payment Integration: Secure payment processing for paid courses using payment gateway.
Real-time communication: Signal-R powered chat functionality for student-instructor interactions.
Notifications: Automated email notifications using Send-Grid for course updates, payment confirmation, reminders.
Content Delivery: Courses can delivered as live sessions or pre-recorded stored in storage account.
Monitoring and Insights: Application performance and user behavior tracked using application insights.
Security: Application sensitive data is securely stored in Azure Key Vault.
Scalability: The application is hosted on Azure Web app with CI/CD pipelines managed by Azure Devops.

## Technology Stack
Frontend: Angular 18
Backend: .NET Core 8 with Entity Framework Core 8
Database: Azure SQL Server
Authentication: Azure AD B2C
Storage: Azure Storage Account for media files
Caching: In-memory cache
Logging: Serilog and Application insights
Notifications: SendGrid
Real-time communication: SignalR
Deployment: Azure Web app
Serveless Functions: Azure Functions for specific tasks
Monitoring: Azure Monitor
Containerization: Docker
Workflow automation: Azure Logic Apps
Payment: Paypal
