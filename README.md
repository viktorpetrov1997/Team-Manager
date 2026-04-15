# 🧑‍🤝‍🧑 Team Manager
### 📌 Project Description
Team Manager is a single-page application developed as part of the SoftUni "JS Applications" course. It is designed to simplify the creation and management of teams. It provides a smooth and interactive interface where users can explore existing teams, create their own, and manage membership workflows in real time.

The application supports role-based functionality, allowing registered users to participate in team activities while guests have read-only access to public team information. Team owners have full control over membership requests and team composition, ensuring proper team management and organization.
## ✨ Features
### 👀 Guest Users
* 🔎 Browse all available teams
* 📄 View team details
* 🚫 Cannot create teams
* 🚫 Cannot interact with membership actions
### 🔐 Registered Users
* ➕ Create new teams
* 📩 Send join requests to teams
* ❌ Cancel join requests
* 🚪 Leave teams they are part of
* 🔎 Browse all available teams
* 📄 View team details
### 🧑‍💼 Team Owners
* ✅ Approve membership requests
* ❌ Decline membership requests
* 🗑️ Remove existing team members
## 🛠️ Tech Stack
* 🌐 HTML  
* 🎨 CSS  
* ⚡ JavaScript  
* 🧩 lit-html – for templating  
* 🛣️ page.js – for client-side routing  
## 🚀 Getting Started
#### 1. Clone the repository
```bash
git clone <repository-url>
```
#### 2. Navigate to the project folder
```bash
cd team_manager
```
#### 3. Start the backend server
```bash
cd server
node server.js
```
#### 4. Open the application
- Open the frontend using **VS Code Live Server**.  
- Right-click `index.html` and select **Open with Live Server**.
## 📸 Screenshots 
### 🏠 Home
<img width="400" alt="home_view" src="https://github.com/user-attachments/assets/6529f40a-3347-4deb-9ef4-054172891fac" />

### 🔎 Browse Teams
<img width="400" alt="browse_teams_view" src="https://github.com/user-attachments/assets/c6e2faa0-fb54-4800-abeb-92ba7467b7cc" />

### 📄 Team Details (User View)
<img width="400" alt="team_details_user_view" src="https://github.com/user-attachments/assets/f9e47317-f36c-4a50-ae34-022a1f14b478" />

### 👑 Team Details (Owner View)
<img width="400" alt="team_details_owner_view" src="https://github.com/user-attachments/assets/22c768f3-cc74-46d3-9686-00e52548e131" />
