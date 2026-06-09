 🏙️  Organization  — Data Entry Portal

A production web application built for  Multistate Credit Co-op Society.

 🔗 Live App
👉 [Open Portal](https://aakashsontakke456-pixel.github.io/godavari-portal/index.html)

 🛠 Tech Stack
| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Authentication | Microsoft MSAL.js v3 + Azure AD (OAuth2) |
| Data Storage | Microsoft SharePoint List |
| API | Microsoft Graph API v1.0 |
| Hosting | GitHub Pages |

 ✨ Features
- 🔐 Microsoft 365 Login — only org accounts can sign in (single-tenant Azure AD)
- 📝 Data Entry Form — Title, Category, Description fields
- ☁️ Saves directly to SharePoint — via Microsoft Graph API POST request
- 📋 Reads recent entries — live table loaded from SharePoint list
- 👤 SubmittedBy auto-captured — from authenticated user identity
- 🔄 Session-based auth — each user must log in with their own account

 🏗️ Architecture
