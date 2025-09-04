# AI Dashboard – Angular 20 & .NET 8

## Overview
This is a **full-stack AI-powered dashboard** demonstrating integration of **Angular 20 frontend**, **.NET 8 backend**, and **Azure cloud services**.  
The dashboard showcases **real-time data visualization** and simple **predictive AI insights**.

## Tech Stack
- **Frontend:** Angular 20, HTML5, CSS3, TypeScript  
- **Backend:** .NET 8, CQRS/MediatR, RESTful APIs  
- **Database:** CosmosDB / SQL Server  
- **Caching:** Redis  
- **Cloud:** Azure Functions, Azure Cognitive Search  
- **DevOps:** GitHub Actions / Azure DevOps CI/CD  

## Features
- Display real-time metrics using charts  
- Sample predictive analytics using a simple ML model  
- CQRS pattern for commands and queries  
- Fully documented architecture and deployment instructions  

## Project Structure
```plaintext
/AI-Dashboard
│
├── backend/           # .NET 8 API
│   ├── Controllers/
│   ├── CQRS/
│   ├── Models/
│   └── Services/
│
├── frontend/          # Angular 20 App
│   ├── components/
│   ├── services/
│   └── assets/
│
├── docs/              # Architecture & deployment docs
└── README.md
````

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/AI-Dashboard.git
   ```
2. **Backend:** Open solution in Visual Studio → Restore NuGet packages → Run API.
3. **Frontend:** Navigate to `frontend/` → `npm install` → `ng serve`.
4. Access the dashboard at [http://localhost:4200](http://localhost:4200).

## Future Enhancements

* Integrate real ML model for predictive insights
* Add authentication using OAuth 2.0
* Deploy fully to Azure with CI/CD pipeline
