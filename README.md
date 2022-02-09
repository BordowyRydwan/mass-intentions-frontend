# Mass Intentions Management Tool - Frontend

It's my university project for *Software Architecture* subject. This tool is intended to help people connected with Catholic Church in organising the data of masses.

## Main features:

- adjustment to elderly people - bigger fonts, simplier design than usual that decreases amount of things to do in order to get particular things done.
- role / permissions system
- account registration and management
- editing, deleting and adding masses, users and their categories
- other typical CRUD operations

## Tech stack:

### Frontend
- Vue 2
- Vue CLI
- Vue Router
- Axios

### Backend
- .NET Core 6
- ASP.NET
- Entity Framework Core
- Automapper
- SQL Server

## Project setup

### Requirements
- SQL Server
- IIS Server or anything that will handle ASP.NET backend
- Node.js 14

### In order to run it

1. Go [HERE](https://github.com/RafalKedziora/dotnet-massintentions) in order to get ASP.NET backend files
2. Create a revelant SQL Server database
3. Run the backend
4. Clone this repo and run `npm install`
5. Run the frontend - `npm run serve`

To build the repo run `npm run build`

