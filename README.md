# Go Clean Architecture Initializer (init_go)

This script is designed to rapidly scaffold new Go projects following a professional **Clean Architecture** structure.

## 🏗 Project Structure

When executed, the script automatically generates the following directory hierarchy:

```text
├── cmd/                # Application entry point (main.go)
├── internal/           # Private application code (Cannot be imported externally)
│   ├── controller/     # HTTP Handlers (Gin, Fiber, etc.)
│   ├── service/        # Business Logic (Service Layer)
│   ├── repository/     # Data Access Layer (Repository Pattern)
│   └── model/          # Data Models (Structs)
├── go.mod              # Project modules
└── README.md           # Project documentation
````

## ⚡️ Quick Start (No Installation Required)
To run the script directly without downloading it, execute the following command in your terminal:

```bash
curl -sL https://raw.githubusercontent.com/SanakulovDev/init_go/refs/heads/main/init_go.ssh| bash
