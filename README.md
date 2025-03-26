# 👗 MyFashionShop - Full Stack Fashion Affiliate Site

Welcome to **MyFashionShop**, a full-stack web application showcasing top fashion picks with real affiliate product links,
 a backend API, PostgreSQL database, interactive MVC views, and a modern static frontend deployed to Azure.

---

## 🌐 Live Site
➡️ [Visit the Site](https://victorious-dune-048530810.6.azurestaticapps.net)

---

## 🧱 Project Architecture

- `MyFashionShop.API` – ASP.NET Core Web API (CRUD + Swagger)
- `MyFashionShop.Web` – ASP.NET Core MVC (GUI for browsing products)
- `StaticSite` – HTML/CSS-based landing page with affiliate links
- PostgreSQL – Database with `Products` and `AffiliateLinks` tables
- GitHub Actions – Deploy static site automatically to Azure Static Web Apps

---

## 💡 Features

✅ ASP.NET Core Web API for product/affiliate data  
✅ PostgreSQL database with EF Core (2 tables: `Products`, `AffiliateLinks`)  
✅ Swagger UI for testing endpoints  
✅ ASP.NET MVC project with server-rendered product views (GUI)  
✅ Responsive static website with Amazon affiliate links  
✅ GitHub Actions CI/CD → Azure Static Web Apps  

---

## 🖥️ GUI & MVC Application

The **MVC Web App** (`MyFashionShop.Web`) allows users to interact with product listings in a more dynamic, server-rendered way.

- 🧾 View products and details via Razor pages  
- 🔄 Integrated with the API backend  
- 🎨 Clean, styled layout powered by Bootstrap or custom CSS  

---

## 📸 UI Preview

> Here's how the static site looks (hosted on Azure):

![MyFashionShop UI](StaticSite/screenshot.png)

---

## ⚙️ Technologies Used

- ASP.NET Core 8 (Web API + MVC)
- Entity Framework Core
- PostgreSQL
- Swagger / OpenAPI
- Azure Static Web Apps
- GitHub Actions
- HTML / CSS / Razor Pages

---

## 🚀 Run the Project Locally

### 🧩 Backend (API)

1. Clone the repo  
2. Update `appsettings.json` in `MyFashionShop.API`  
3. Apply migrations and run:

```bash
cd MyFashionShop.API
dotnet ef database update
dotnet run

Built by [Janeth Blevins] — Spring 2025 Full Stack Project
Powered by Azure, GitHub, and a love for clean code & fashion 💅
