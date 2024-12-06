# DotNet-Angular-Keycloak-Demo

This project is a simple demo on how **Keycloak** is integrated for authentication in an Angular 18+ frontend and a .NET Core backend.

## Tutorials Used

- Step-by-step guide for setting up Keycloak OAuth2 in Angular and .NET Core:  
  [Miloš Željko's Tutorial](https://miloszeljko.com/step-by-step-guide-setting-up-keycloak-oauth2-in-angular-and-net-core-for-secure-authentication/)

- Help for implementing Keycloak in Angular 18+:  
  [Pretius Blog on Keycloak Angular Integration](https://pretius.com/blog/keycloak-angular-integration/)

## Keycloak Angular Package

This project uses the **Keycloak Angular** package for integration with Angular.  
NPM Package: [keycloak-angular](https://www.npmjs.com/package/keycloak-angular)

## Features

- Secure authentication using OAuth2 with Keycloak
- Integration with Angular's standalone components
- Backend API secured with Keycloak

## Setup Instructions

### 1. Backend API (ASP.NET Core)

The backend API is set up in Visual Studio. To get started, follow these steps:

1. Open the solution file (`.sln`) in **Visual Studio**.
2. Build and run the solution via the IDE.

### 2. Frontend (Angular)

To start the Angular app:

1. Open a terminal in the Angular project directory.
2. Run `ng serve` to start the Angular development server.
3. The Angular app should be accessible at `http://localhost:4200`.

### 3. Keycloak Setup with Docker

To start Keycloak using Docker:

1. Ensure you have Docker installed and running on your machine.
2. In the root directory of the project, run the following command to start Keycloak:

   ```bash
   docker-compose up -d
3. This will start the Keycloak container in detached mode. Once running, you can access Keycloak at `http://localhost:8080`.
4 .Follow the step-by-step guide linked above to configure Keycloak for authentication
