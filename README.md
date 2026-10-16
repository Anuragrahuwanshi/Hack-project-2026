# 🌾 FarmConnect
### Direct Farmer-to-Consumer Digital Marketplace

**Connecting farmers directly with consumers through a digital marketplace.**

<p align="center">
  <img src="https://img.shields.io/badge/BGI-Hackathon%202026-2e7d32?style=for-the-badge" alt="BGI Hackathon 2026" />
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-blue?style=for-the-badge" alt="Frontend technologies" />
  <img src="https://img.shields.io/badge/Backend-Node.js%20%7C%20Express.js-green?style=for-the-badge" alt="Backend technologies" />
  <img src="https://img.shields.io/badge/Status-Prototype-orange?style=for-the-badge" alt="Prototype status" />
</p>

---

## 📌 About the Project

**FarmConnect** is a hackathon project that aims to connect farmers directly with consumers through a digital agricultural marketplace.

The project focuses on improving product discovery, encouraging transparent pricing, and helping farmers reach potential buyers through a digital platform.

## 🎯 Problem Statement

Farmers can face challenges reaching customers directly, while consumers may have difficulty discovering locally available agricultural produce and comparing prices.

Traditional supply chains can involve multiple intermediaries, making direct communication between farmers and buyers more difficult.

## 💡 Proposed Solution

FarmConnect aims to provide a common digital platform where:

- 🌱 Farmers can showcase their agricultural produce.
- 🛒 Consumers can discover available products.
- 💰 Buyers can view product prices.
- 🤝 Farmers and consumers can connect more directly.
- 📦 Order and delivery processes can be managed as the platform develops.

## ✨ Key Features

The following checklist should reflect the **actual implementation status** of the current prototype.

- [ ] Farmer and consumer registration
- [ ] Product listing and availability management
- [ ] Product search and browsing
- [ ] Product pricing display
- [ ] Order management
- [ ] Payment integration
- [ ] Delivery tracking

> Update these checkboxes after testing each feature. Do not mark a feature complete just because it is part of the project plan.

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication and Security Libraries
- bcryptjs — password hashing
- JSON Web Token (JWT) — token-based authentication

### Other Libraries and Tools
- Multer — file uploads
- dotenv — environment variable configuration
- CORS — cross-origin request handling
- Cookie Parser — cookie handling
- Nodemon — development server restart
- npm — dependency management
- Git and GitHub — version control

## 📂 Project Structure

```text
Hack-project-2026/
├── .cursor/
├── HOME/
│   ├── FARMER/
│   ├── Home Page/
│   │   ├── index.html
│   │   ├── Style.css
│   │   └── Script.js
│   ├── _admin/
│   ├── help/
│   └── shared/
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── .env.example
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
├── LICENSE
├── README.md
└── package-lock.json
```

### Main Components

- **Frontend:** User interface files organized under `HOME/`.
- **Backend:** Node.js and Express server code organized under `server/`.
- **Routes and Controllers:** Backend request-handling modules.
- **Models:** Database-related model files.
- **Configuration:** Server configuration and environment variable template.
- **Documentation:** Project overview, setup instructions, and license.

## 🚀 Getting Started

### Prerequisites

- Git
- Node.js and npm
- MongoDB configured for the backend
- A code editor such as Visual Studio Code

### 1. Clone the repository

```bash
git clone https://github.com/Anuragrahuwanshi/Hack-project-2026.git
cd Hack-project-2026
```

### 2. Install backend dependencies

```bash
cd server
npm install
```

### 3. Configure environment variables

Create a `.env` file inside the `server/` directory using `.env.example` as a reference.

On Windows PowerShell, you can use:

```powershell
Copy-Item .env.example .env
```

Open `.env` and fill in the required values according to the existing project configuration. Do not commit secrets, passwords, or private database credentials to GitHub.

### 4. Start the backend

For development:

```bash
npm run dev
```

Or use:

```bash
npm start
```

Ensure MongoDB and the required environment variables are configured before starting the server.

### 5. Open the frontend

Open `HOME/Home Page/index.html` in your browser, or use the VS Code Live Server extension if appropriate for the project.

**Note:** The frontend and backend may require additional configuration to communicate correctly. Verify the application's actual startup flow before describing these instructions as fully tested.

## 📸 Screenshots and Demo

Add screenshots from the actual project to help visitors understand the interface.

Suggested screenshots, if implemented:

- Home page
- Farmer interface
- Product listing page
- Admin interface
- Consumer browsing experience

## 👥 Project Contributors

- **Anurag Raghuwanshi** — [GitHub Profile](https://github.com/Anuragrahuwanshi)
- **Aryan Kharwar** — [GitHub Profile](https://github.com/aryankhrwar964-sudo)
- **Chetan Patel** — [GitHub Profile](https://github.com/CHETAN-PATEL-1)
- **Harsh Dubey** — [GitHub Profile](https://github.com/harshdubey-ops)
- **Priya Lowanshi** — [GitHub Profile](https://github.com/priyalowanshi60-123)

## 🔮 Future Scope

- Improved accessibility for rural users
- Better product discovery and price comparison
- Secure payment integration
- Order and delivery tracking
- Responsive, mobile-friendly interface
- Further improvements to the farmer and consumer experience

## 📄 License

See the [LICENSE](LICENSE) file for the project's licensing terms.

---

<p align="center">
  <strong>Building a more connected agricultural marketplace 🌱</strong>
  <br />
  Made with 💚 by the FarmConnect project team for BGI Hackathon 2026.
</p>
