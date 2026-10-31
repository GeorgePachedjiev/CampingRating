# 🏕️ CampingRating

**CampingRating** is an ASP.NET Core MVC web application designed to help users discover camping sites, explore available information, and share their experiences through ratings and reviews.

This project was developed independently as my **State Examination Project** for the IT Career National Program, as part of the requirements for obtaining a professional qualification.

## 🎓 Project Information

- **Project Type:** State Examination Project
- **Program:** IT Career – National Program
- **Purpose:** Obtaining a Professional Qualification
- **Professional Qualification:** Applied Programmer (Приложен програмист)
- **Development:** Individual Project
- **Framework:** ASP.NET Core MVC
- **.NET Version:** 8.0

## 🚀 Features

- **User Authentication** – Registration and login using ASP.NET Core Identity.
- **Role-Based Authorization** – Separate permissions for Admin and User roles.
- **Camping Site Management** – Create, view, edit, and delete camping site profiles.
- **Reviews & Ratings** – Users can share their experiences and rate camping sites.
- **User Management** – Administrative functionality for managing users.
- **Filtering & Sorting** – Find and organize camping sites.
- **Pagination** – Navigate through available camping sites.
- **Image Upload** – Upload and manage camping site images.

## 🛠️ Technologies Used

- C#
- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- ASP.NET Core Identity
- Microsoft SQL Server
- Razor Views
- HTML5 & CSS3
- Dependency Injection
- Service Layer Architecture

## 🏗️ Architecture

The application uses a structured architecture with separation of responsibilities through:
- Controllers
- Services and Interfaces
- ViewModels
- Data Models
- Entity Framework Core

## 👤 User Roles

**Admin**
- Manage users.
- Manage camping site profiles.
- Manage application content.

**User**
- Browse camping sites.
- Submit ratings and reviews.
- Manage permitted user interactions.

## ⚙️ Getting Started

1. Clone the repository:
   ```bash
   git clone YOUR_REPOSITORY_URL
   ```
2. Open the solution in Visual Studio.
3. Configure your database connection in `appsettings.json`.
4. Apply Entity Framework Core migrations:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```

## 📌 Purpose

The project demonstrates practical skills in ASP.NET Core development, database management, authentication, authorization, and building full-stack web applications.
