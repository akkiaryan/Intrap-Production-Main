# InTrap 🚀 - No-Code Workflow Automation

![InTrap Banner](https://media-hosting.imagekit.io//d012f55d210d48e5/Screenshot%202025-02-21%20at%2012.40.47%E2%80%AFAM.png?Expires=1834727377&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=vU1pqNO10zP4un8R3D4xtw0SE-D2lodwhKEQGZkpfJL2yJ1iAjeHmhD~Q-6jjkmqHeDnnJ3Bax5p~HrBNmXVUccjXto1TUJJhyVDKxILLhbaQsF1bMtgESDNA-9c2gE~0XEyaqozUGM6Yp0XWdkIQTABNtkfBaZSYDb07efpgTN4CiWaeoCUxd3U1RAIv4TtDi1BkmLqjn4rjuN~PWDcKzgM-Vd58AMkQr0odPoCyeGX-4PyxTvimOfuDILLiZsJNBL6X1ft4eHBeh322rbnoDG8aJgdY1Nwpib1liieRx06O80yEMb12bkv4XbdRrJPUqIYkX8joe0Nn2j0u~p63Q__)

## 🔥 Overview

**InTrap** is a no-code automation builder designed to streamline workflows and eliminate repetitive tasks. Whether you want to sync data, schedule tasks, or integrate services seamlessly, InTrap makes automation accessible to everyone—without writing a single line of code.

## 🏗️ Tech Stack

- **Frontend:** Next.js 15 (App Router) + TailwindCSS + Aceternity UI
- **Backend:** Prisma + PostgreSQL
- **Authentication:** Clerk
- **Payment & Subscriptions:** Stripe (Credit-based billing)
- **Automation Engine:** Node-based workflow builder with infinite canvas
- **Hosting:** Vercel / Railway
- **Package Manager:** Bun

## 🌟 Features

### 🔄 **Automation Capabilities**
- Drag-and-drop node builder for workflow automation
- Multi-platform integrations (Google Drive, Slack, Discord, Notion, Stripe, etc.)
- Custom event triggers for optimized efficiency
- Infinite canvas with a mini-map to visualize workflows

### 🔐 **Integrations**
- **Google Drive**: Watch for file changes & automate data flow
- **Slack & Discord**: Send real-time notifications & custom messages
- **Notion**: Create database entries automatically
- **Stripe**: Manage subscriptions & credit-based payments

### ⚙️ **Advanced Features**
- Beautifully redesigned node interface with an expandable sidebar
- Light & Dark mode support
- Secure authentication & user management
- Scalable backend with optimized database queries

## 🛠️ Installation & Setup

### 🔹 Prerequisites
Make sure you have the following installed:
- Node.js (v18+ recommended)
- Bun (for package management)
- PostgreSQL (local or cloud instance)

### 🔹 Clone the Repository
```sh
 git clone https://github.com/akkiaryan/Intrap-Production-Main.git
 cd Intrap-Production-Main
```

### 🔹 Install Dependencies
```sh
bun install
```

### 🔹 Setup Environment Variables
Create a `.env` file in the root directory and add:
```env
DATABASE_URL=your_postgresql_url
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_key
CLERK_SECRET_KEY=your_clerk_secret_key
STRIPE_SECRET_KEY=your_stripe_key
...
```

### 🔹 Run Migrations & Seed Database
```sh
bun run prisma migrate dev
bun run prisma db seed
```

### 🔹 Start the Development Server
```sh
bun run dev
```
The application will be available at `http://localhost:3000`

## 🏆 Roadmap
- [x] Implement node-based automation builder
- [x] Google Drive & Slack integrations
- [ ] Webhooks for custom triggers
- [ ] AI-based workflow recommendations
- [ ] Public API for third-party integrations

## 🤝 Contributors
- **Akki Aryan** ([@akkiaryan](https://github.com/akkiaryan)) - Creator & Lead Developer
- **Web Prodigies** - Supporting the project

## 📜 License
This project is licensed under **© Akki Aryan & Web Prodigies**.

## 🌍 Connect with Me
- **GitHub**: [akkiaryan](https://github.com/akkiaryan)
- **LinkedIn**: [Akki Aryan](https://www.linkedin.com/in/itsmeakki/)

---
🚀 **InTrap is redefining automation—one workflow at a time. Stay tuned!**
