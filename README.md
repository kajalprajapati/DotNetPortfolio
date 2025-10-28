# AINotesHub

A **.NET 8** solution combining **WPF**, **ASP.NET Core REST API**, and a **shared class library**.  
This project demonstrates a real-world architecture where both the desktop app and API communicate using shared models.

## 🧩 Structure
WCF+.netcoreRestAPI\AINotesHub\ ← Root solution folder
│
│ AINotesHub.sln ← Solution file
│ (Created by selecting Blank Solution in Visual Studio 2022)
│
├── AINotesHub.Shared ← Class Library (.NET 8) → Shared Models & Helpers
├── AINotesHub.API ← ASP.NET Core Web API (.NET 8) → Backend Services
└── AINotesHub.WPF ← WPF Application (.NET 8) → Desktop Client

## 🧠 Notes

- Each project is part of a single solution (`AINotesHub.sln`).  
- You can **start multiple projects** simultaneously — for example, run both **API** and **WPF** together.  
- Or select a **single project** as the startup project (API or WPF individually).  
- Shared models are used across API and WPF for consistent data representation.

## ⚙️ How to Run
1. Clone the repo  
   `git clone https://github.com/<your-username>/AINotesHub.git`
2. Open `AINotesHub.sln` in Visual Studio
3. Set **Multiple Startup Projects** → Start both **API** & **WPF**
4. Run the solution 🎯

## 🧰 Tech Stack
- .NET 8 / C#
- ASP.NET Core Web API
- WPF (MVVM)
- Entity Framework Core
- Clean Architecture
- Visual Studio 2022
