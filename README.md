# SwArth
Personal Financial Agent.

A personal assistant to track all types of personal financial transactions like daily expenses, investments, family expenses etc.

## Project Scaffold: C# Application

This project is a C#-based personal financial agent. The application will help you track:
- Daily expenses
- Investments
- Family expenses
- Other personal financial transactions

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) or later
- Git

### Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd SwArth
   ```

2. **Create the solution and main project:**
   ```bash
   dotnet new sln -n SwArth
   dotnet new console -n SwArth.App
   dotnet sln add SwArth.App/SwArth.App.csproj
   ```

3. **Run the application:**
   ```bash
   dotnet run --project SwArth.App
   ```

### Suggested Project Structure

```
SwArth/
├── SwArth.sln
├── SwArth.App/
│   ├── Program.cs
│   └── ...
└── README.md
```

### Next Steps

- Implement features for tracking expenses, investments, and reports
- Add data persistence (e.g., using a database or local files)
- Create a simple CLI or UI for user interaction

---
Feel free to contribute or suggest features!
