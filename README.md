# 🖼️ Imigfy – AI Image Generator

<img width="1897" height="902" alt="Screenshot 2025-07-14 094920" src="https://github.com/user-attachments/assets/9654826b-05ca-4073-80e4-852b9e254f5e" />
<img width="1893" height="895" alt="Screenshot 2025-07-14 095025" src="https://github.com/user-attachments/assets/1f0c78a0-fe43-4d1f-b2bb-835edf95db74" />
<img width="1892" height="887" alt="Screenshot 2025-07-14 094939" src="https://github.com/user-attachments/assets/79a0d91e-4690-49c5-afec-116df44a48c8" />


Imigfy is a full-stack AI image generator that lets users create images from text prompts using a credit system. Built with **React**, **Node.js**, **Express**, and **MongoDB**.

---

## 🚀 Features

- JWT Auth (Register/Login)
- AI image generation from prompts
- Credit system per image
- Protected routes with middleware
- React + Tailwind UI

---

## ⚙️ Setup

### 1. Clone & Install

```bash
git clone https://github.com/Gregamoo/imigfy.git
cd imigfy

# Install server
cd server && npm install

# Install client
cd ../client && npm install

2. Env Setup
Create .env files:

server/.env
MONGODB_URI = "your_mongo_uri"
JWT_SECRET = "Your_secret"
CLIPDROP_API = "Clipdrop_api"

client/.env
VITE_BACKEND_URL=http://localhost:4000

3. Run App

# Start server
cd server && npm run dev

# Start client
cd ../client && npm run dev

📌 Main Routes
Method	Route	Auth
POST	/api/user/register	No
POST	/api/user/login	No
GET	/api/user/credits	Yes
POST	/api/image/generate-image	Yes

🛠️ Tech
React · Node · Express · MongoDB · Tailwind · JWT · Vite

Project was developed by following GreatStack YouTube tutorial "https://www.youtube.com/watch?v=DSGFZb8KiO8"
