# 🌟 Rezappt Backend

Welcome to the **Rezappt Backend** repository! This is the powerhouse that drives the backend operations for **Rezappt**, an innovative application that allows users to store, maintain, and share their own recipes. Users can vote on recipes, and the platform also supports exporting recipes as PDFs, making it easy to share your culinary creations.

---

## 📊 Project Overview

**Current Sprint**: Sprint 12 (⏳ 2024-09-15 - 2024-09-29)

- **Project Manager**:
  - [Jane Doe](https://fake-link/jane) 👩‍💼 (Organized, Detail-Oriented)
- **Developers**:
  - [John Smith](https://fake-link/john) 👨‍💻 (Innovative, Quick Problem-Solver)
  - [Sarah Lee](https://fake-link/sarah) 👩‍💻 (Meticulous, API Expert)

---

## 📝 Methodology

We follow a **Scrumban** methodology 📝, combining elements of Scrum and Kanban to ensure flexibility and continuous delivery.

- **Sprint Type**: 🛠️ Organizational
- **Sprint Duration**: 2 weeks ⏱️  
- **Sprint Daily**: 15 minutes, [Join the meeting here](https://teams.microsoft.com/fake-link) 💬  
- **Sprint Planning**: First day of the sprint, [Sprint planning link](https://teams.microsoft.com/fake-link) 📅  
- **Sprint Retro**: Last day of the sprint, [Retro link](https://teams.microsoft.com/fake-link) 🔄  

---

## ⚙️ Tech Stack

- **C# .NET 8**
- **ASP.NET Web API**
- **Entity Framework Core**
- **PostgreSQL**
- **OpenAPI**

---

## 🚀 Getting Started

### Prerequisites

- [.NET SDK 8.0+](https://dotnet.microsoft.com/download/dotnet/8.0)
- [PostgreSQL](https://www.postgresql.org/download/)
- IDE: Visual Studio, Rider, or VS Code

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://your-private-repo-url.git
   cd rezappt-backend
   ```

2. **Set up the PostgreSQL database**:
   ```sql
   CREATE DATABASE rezappt_db;
   ```

3. **Configure the connection string** in `appsettings.json`:
   ```json
   {
     "ConnectionStrings": {
       "DefaultConnection": "Host=localhost;Database=rezappt_db;Username=yourusername;Password=yourpassword"
     }
   }
   ```

4. **Restore dependencies**:
   ```bash
   dotnet restore
   ```

5. **Apply database migrations**:
   ```bash
   dotnet ef database update
   ```

6. **Build and run the project**:
   ```bash
   dotnet run
   ```
---

## 🛠️ Key Features

- **Authentication & Authorization**
- **Entity Framework Core**
- **Modular & Extensible API**
- **Centralized Exception Handling**
- **Swagger Documentation**

---

## 🧪 Testing

We are using **xUnit** for unit and integration testing.

### Running Tests

1. Ensure the database is running and migrations are applied.
2. Run the tests using the following command:
   ```bash
   dotnet test
   ```

Our testing strategy includes:

- **Unit Tests**: Validating individual components.
- **Integration Tests**: Testing API endpoints and database operations.

Test results are automatically included in the CI pipeline.

---

## 🚀 Release Management

Our release process is automated using GitHub Actions, deploying Docker images to GitHub Packages. We follow **semantic versioning** to tag each release.

### Docker Image

Docker images are built and pushed automatically to the GitHub Packages registry. You can pull the latest version of the backend with:
   ```bash
   docker pull ghcr.io/your-organization/rezappt-backend:latest
   ```

To specify a version:
   ```bash
   docker pull ghcr.io/your-organization/rezappt-backend:v1.2.3
   ```

---

## 🔀 Branching Model

We follow **GitHub Flow**, which emphasizes:

1. **Feature Branches**: Create a branch for each feature or bug fix.
2. **Pull Requests**: Use PRs for peer review and quality control.
3. **Continuous Deployment**: Every PR merged into `main` triggers an automatic deployment.

---

## 🧑‍💻 Contributing

This is a private repository. For collaboration, please contact the project manager directly:

- **Project Manager**: [Jane Doe](https://fake-link/jane) 👩‍💼

---

Thank you for checking out the **Rezappt Backend**! 🎉
