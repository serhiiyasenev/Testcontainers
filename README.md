Testcontainers Demo (.NET + PostgreSQL)

https://dotnet.testcontainers.org/

This project demonstrates how to use Testcontainers for .NET to run integration tests with a PostgreSQL container.

Project Structure

Testcontainers/
├── CustomerService/           # Business logic
├── CustomerService.Tests/     # Integration tests
└── .github/workflows/test.yml # GitHub Actions workflow

Tech Stack

.NET 9

xUnit

Testcontainers

PostgreSQL (Docker)

GitHub Actions

Running Tests Locally

Make sure Docker is running:

dotnet test

CI/CD

Tests run on every push and PR via GitHub Actions.