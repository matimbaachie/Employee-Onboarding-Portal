# Employee Onboarding Portal

## Project Summary  
I developed a comprehensive Employee Onboarding Portal designed to streamline the onboarding process by managing employee profiles, tasks, and documentation within a secure environment. The project integrates Azure Active Directory (Azure AD) for authentication, ensuring only authorized HR personnel and new hires access sensitive data.

The backend is built with ASP.NET Core, exposing RESTful APIs secured with Azure AD tokens. Data persistence is handled using Entity Framework Core with a SQL Server database hosted on Azure. The frontend is a React SPA with Azure AD login implemented via MSAL.js.

## Key Features  
- Secure login using Azure AD with role-based access control.  
- Employee profile and document management.  
- Onboarding task tracking and status updates.  
- Responsive React UI with React Router for navigation.  
- Robust backend APIs secured by Azure AD middleware.  
- SQL Server integration using EF Core migrations and seed data.  
- Full deployment on Azure App Service with CI/CD pipelines.

## Technologies Used  
- React, MSAL.js for authentication  
- ASP.NET Core Web API with Azure AD integration  
- Entity Framework Core with Azure SQL Database  
- Azure App Service for hosting  
- GitHub for version control and pipeline automation  

## How I Delivered It  
- Set up Azure AD tenant, registered frontend and backend apps, and configured permissions.  
- Designed and implemented the SQL Server database schema and EF Core data models.  
- Developed secure ASP.NET Core API with JWT Bearer authentication against Azure AD.  
- Built React frontend integrating MSAL.js for seamless SSO experience.  
- Deployed all components to Azure App Service, ensuring production-ready scalability and security.  
- Created comprehensive documentation and runbooks for ongoing maintenance.

---

This project gave me hands-on experience delivering end-to-end Azure AD secured full-stack solutions deployed in the cloud.

