# CodePulse - Blog Management System

A full-stack blog management application built with .NET 8 Web API and Angular 18.

## Project Structure

```
CodePulse/
├── API/                    # .NET 8 Web API Backend
│   └── CodePulse.API/
├── UI/                     # Angular 18 Frontend
│   └── codepulse/
└── README.md
```

## Backend Features (.NET 8 Web API)
- Entity Framework Core with SQL Server
- Repository Pattern implementation
- Category management API endpoints
- Swagger/OpenAPI documentation
- Domain models and DTOs

## Frontend Features (Angular 18)
- Standalone components architecture
- Category management interface
- Responsive navigation
- Angular Router for SPA navigation
- Server-Side Rendering (SSR) support

## Getting Started

### Prerequisites
- .NET 8 SDK
- Node.js (v18+)
- SQL Server
- Angular CLI

### Backend Setup
1. Navigate to `API/CodePulse.API/CodePulse.API`
2. Update connection string in `appsettings.json`
3. Run migrations: `dotnet ef database update`
4. Start API: `dotnet run`

### Frontend Setup
1. Navigate to `UI/codepulse`
2. Install dependencies: `npm install`
3. Start development server: `ng serve`

## Current Status
- ✅ Backend API structure with Category management
- ✅ Frontend Angular components and routing
- ✅ Database models and migrations
- ✅ Repository pattern implementation
- 🚧 Frontend-Backend integration (in progress)
- 🚧 Complete CRUD operations (in progress)

## Technologies Used
- **Backend**: .NET 8, Entity Framework Core, SQL Server, Swagger
- **Frontend**: Angular 18, TypeScript, RxJS, Angular Router
- **Development**: Git, Visual Studio/VS Code