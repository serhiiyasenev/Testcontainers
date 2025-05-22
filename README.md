Testcontainers Demo (.NET + PostgreSQL) 

https://dotnet.testcontainers.org/

This project demonstrates using Testcontainers for .NET to run integration tests with a PostgreSQL container.

🗂️ **Project Structure**

```mermaid
graph TD
  A[Testcontainers]
  A --> B[CustomerService]
  B --> B1[Customer.cs]
  B --> B2[CustomerService.cs]
  B --> B3[DbConnectionProvider.cs]
  A --> C[CustomerService.Tests]
  C --> C1[CustomerServiceTest.cs]
  A --> E[.github/workflows]
  E --> E1[test.yml]
```

Tech Stack: .NET 9, xUnit, Testcontainers, PostgreSQL (Docker), GitHub Actions

Running Tests Locally:
1. Make sure Docker is running
2. Execute "dotnet test"

CI/CD: Tests run on every push and PR via GitHub Actions.

[![Tests](https://github.com/serhiiyasenev/Testcontainers/actions/workflows/test.yml/badge.svg)](https://github.com/serhiiyasenev/Testcontainers/actions/workflows/test.yml)
