# E-Commerce Website

An ASP.NET MVC e-commerce web application with separate **Admin** and **User** views — product catalog, cart, checkout, and PayPal Sandbox integration.

## Screenshots
<img width="959" height="368" alt="Screenshot 2026-07-08 053616" src="https://github.com/user-attachments/assets/186a192f-4d47-4539-8fca-a7322d8e3bd2" />
<img width="956" height="374" alt="Screenshot 2026-07-08 053635" src="https://github.com/user-attachments/assets/45987c46-28e3-4b7c-8b63-deba826dd532" />
<img width="958" height="368" alt="Screenshot 2026-07-08 053646" src="https://github.com/user-attachments/assets/062298b5-4a8e-4002-84be-c0494272113e" />
<img width="956" height="373" alt="Screenshot 2026-07-08 053659" src="https://github.com/user-attachments/assets/58b21ec5-fbcf-4632-b99c-766891c5203b" />
<img width="944" height="375" alt="Screenshot 2026-07-08 053918" src="https://github.com/user-attachments/assets/f188cee4-4bd7-44f1-aa4c-0219da793181" />
<img width="941" height="376" alt="Screenshot 2026-07-08 053929" src="https://github.com/user-attachments/assets/9a5418a5-df19-4b7f-9fa0-3b216007b004" />
<img width="946" height="374" alt="Screenshot 2026-07-08 053955" src="https://github.com/user-attachments/assets/9a94a949-6121-4ffa-8487-3a41c0f701e6" />
<img width="948" height="304" alt="Screenshot 2026-07-08 054025" src="https://github.com/user-attachments/assets/65aedcf3-cb9c-41f8-8c9a-3915b583c638" />
<img width="944" height="376" alt="Screenshot 2026-07-08 054009" src="https://github.com/user-attachments/assets/95ebbdd7-4cea-41e6-9b9b-e499efb74230" />

## Features

- **User Space** — browse products, add to cart, checkout with PayPal Sandbox
- **Admin Space** — manage products, orders, and store data
- Session-based authentication
- Entity Framework for data access

## Tech Stack

ASP.NET MVC · C# · Entity Framework · SQL Server  · Bootstrap

## Structure

- `Views/` — MVC views (User + Admin pages)
- `Scripts/` — client-side JS
- `Content/` — CSS/static assets
- `Global.asax` — application entry point
- `Web.config` — app configuration (fill in your own PayPal Sandbox keys and DB credentials before running)

## Running Locally

1. Open the project in Visual Studio
2. Restore NuGet packages
3. Update `Web.config` with your own database connection string and PayPal Sandbox credentials
4. Run via IIS Express
