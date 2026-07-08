# E-Commerce Website

An ASP.NET MVC e-commerce web application with separate **Admin** and **User** views — product catalog, cart, checkout, and PayPal Sandbox integration.

## Screenshots

<img width="959" height="368" alt="image" src="https://github.com/user-attachments/assets/4a0162c5-8dc0-49df-bb47-0fda18b08294" />
<img width="958" height="368" alt="image" src="https://github.com/user-attachments/assets/6c7f8b52-0cdd-4425-80a6-2f5255baa4cd" />
<img width="956" height="374" alt="image" src="https://github.com/user-attachments/assets/d0f807b2-e1e3-4679-8aa8-5c1498c66b01" />
<img width="956" height="373" alt="image" src="https://github.com/user-attachments/assets/58d0e913-e508-41f0-88d5-ead83d05708f" />
<img width="941" height="376" alt="image" src="https://github.com/user-attachments/assets/480966c7-b346-4cd8-aba4-4ed95c2406e6" />
<img width="946" height="374" alt="image" src="https://github.com/user-attachments/assets/6912a5b1-bad4-4749-871e-b5953011dab6" />
<img width="944" height="376" alt="image" src="https://github.com/user-attachments/assets/27af93cd-2b07-40e5-86d1-4b23d6a93119" />
<img width="948" height="304" alt="image" src="https://github.com/user-attachments/assets/196f7dff-730c-45bd-8386-3140fc1539d2" />


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
