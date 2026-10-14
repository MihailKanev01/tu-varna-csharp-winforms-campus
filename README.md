# Campus Management

A C# Windows Forms desktop application organised around account access and campus-related record workflows.

## Overview

The solution contains a multi-form interface, including access, registration, recovery, create, manage, update, view, archive and payment screens. The project demonstrates how a desktop application can separate related user flows across dedicated forms.

## Technical Focus

- C#
- Windows Forms
- Event-driven user-interface logic
- Multi-form application structure
- Separation of UI forms and supporting database code

## Project Structure

```text
Campus.sln
Campus/
├── Database/
├── Forms/
└── Program.cs
```

## Run Locally

**Requirements:** Windows and Visual Studio with the .NET desktop development workload.

1. Clone the repository:
   ```bash
   git clone https://github.com/MihailKanev01/tu-varna-csharp-winforms-campus.git
   ```
2. Open `Campus.sln` in Visual Studio.
3. Review the database configuration and required local dependencies.
4. Build the solution and run the application.

## Project Status

An educational desktop application demonstrating Windows Forms, navigation between screens and database-oriented workflows. Database configuration may need to be adapted to the local environment.
