# 🧑‍🤝‍🧑 Team Manager
### 📌 Project Description
Team Manager is a single-page application developed as part of the SoftUni "JS Applications" course. It is designed to simplify the creation and management of teams. It provides a smooth and interactive interface where users can explore existing teams, create their own, and manage membership workflows in real time.

The application supports role-based functionality, allowing registered users to participate in team activities while guests have read-only access to public team information. Team owners have full control over membership requests and team composition, ensuring proper team management and organization.
## ✨ Features
### 👀 Guest Users
* 🔎 Browse all available teams
* 📄 View team details
* 🚫 Cannot create or join teams
* 🚫 Cannot interact with membership actions
### 🔐 Registered Users
* ➕ Create new teams
* 🔎 Browse and search teams
* 📩 Send join requests to teams
* ❌ Cancel join requests
* 🚪 Leave teams they are part of
### 🧑‍💼 Team Owners
* ✅ Approve membership requests
* ❌ Decline membership requests
* 🗑️ Remove existing team members
* ⚙️ Manage team membership structure
## 🛠️ Tech Stack
* 🌐 HTML  
* 🎨 CSS  
* ⚡ JavaScript  
* 🧩 lit-html – for templating  
* 🛣️ page.js – for client-side routing  
## 🚀 Getting Started
#### 1. Clone the repository
```bash
git clone <repo-url>
cd team_manager
```
#### 2. Start the backend server
```bash
cd server
node server.js
```
#### 3. Start the frontend application
Open a new terminal window and run:
```bash
npm start
```
#### 4. Open the application
Once both servers are running, open your browser and visit:

👉 http://localhost:3000
## 📸 Screenshots 
### 🏠 Home
<img width="350" height="606" alt="home" src="https://github.com/user-attachments/assets/71a69c4c-82ed-428f-8518-7f5da2406faa" />

### 🔍 Recipe Details
<img width="350" alt="details" src="https://github.com/user-attachments/assets/e5553c5f-54fa-4705-b856-3185a411ea8f" />

### 🍽️ Catalog
<img width="350" alt="catalog" src="https://github.com/user-attachments/assets/aef89d36-e63c-48fa-9d25-fb0b5e03f333" />

### 💬 Comments
<img width="400" alt="comments" src="https://github.com/user-attachments/assets/d04f3154-ffe1-4ac6-bbe3-e35a1edbf56c" />
