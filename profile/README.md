# 🏷️ TailTag

🏷️ **TailTag** – The ultimate way to mark your digital territory! 🌐✨ Create a sleek, shareable profile with all your links in one cozy den. No coding required—just sign in, customize, and share your unique URL:  
🔗 **[tailtag.link/@your-handle](https://tailtag.link)**! 🐾🚀

Self-hosted, open-source, and always ready to wag. Join the pack at **[tailtag.link](https://tailtag.link)**!

---

## 📂 GitHub Repository Structure

We follow a modular approach, with separate repositories for different components:

🔹 **[tailtag/landing-page](https://github.com/tailtag/landing-page)** – Temporary landing page (React, Tailwind, TypeScript, shadcn/ui)  
🔹 **[tailtag/server](https://github.com/tailtag/server)** – Backend server (Node.js, Express, PostgreSQL)  
🔹 **[tailtag/frontend](https://github.com/tailtag/frontend)** – Frontend (React, Tailwind, TypeScript)  
🔹 **tailtag/server-config** _(Private Repo)_ – Scripts & configuration files (environment variables, deployment scripts)  
🔹 **[tailtag/hey](https://github.com/tailtag/hey)** – Public documentation & guides for hosting TailTag

📌 **GitHub Organization**: [github.com/tailtag](https://github.com/tailtag)

---

## 🌟 Key Features

✅ **User Profiles**

- Personalize your page with:
  - 📛 Name & Username
  - ✍️ Short Bio
  - 🔗 Social Media Buttons
  - 🎵 Spotify Widget (optional)
  - 🖼️ Profile Picture & Image Gallery (optional)
  - 🏳️‍🌈 Age, Gender, Sexuality (optional)

✅ **Customization & Embeds**

- 🎨 Choose colors, themes, and layouts
- 🌐 OpenGraph/Twitter Card previews for shared links
- 📝 Customize metadata for link previews

✅ **Authentication & Security**

- 🔑 Keycloak SSO login
- 🔒 Only you can edit your page
- 🖼️ Secure image uploads (S3)

✅ **Analytics & Insights**

- 📊 Track profile views & clicks (powered by Umami)

✅ **Self-Hosting via Docker**

- 🛠️ Fully containerized (backend, frontend, database, storage)
- 📦 Simple `docker-compose up` deployment

---

## 🏗️ Project Stack

**Backend**: Node.js, Express, PostgreSQL, Drizzle ORM  
**Frontend**: React, Tailwind, ShadCN, TypeScript, Vite  
**Authentication**: Keycloak SSO  
**Storage**: Hetzner Object Storage (S3) (for profile pictures & gallery images)  
**Analytics**: Umami  
**Deployment**: Docker, Traefik

---

## 🚀 Project Roadmap

📌 **Current Status**: _Planning Phase - Development Not Yet Started_

### **📝 Phase 1: Project Setup (1-2 weeks)**

✅ Finalize project scope and technical stack  
✅ Set up project repository and documentation  
✅ Define database schema and API structure

### **⚙️ Phase 2: Backend Development (3-4 weeks)**

🔄 Implement Keycloak authentication  
🔄 Build user profile and storage APIs  
🔄 Set up Hetzner Object Storage for file storage  
🔄 Implement analytics tracking

### **🎨 Phase 3: Frontend Development (3-4 weeks)**

🔄 Design and develop UI components  
🔄 Create profile page rendering  
🔄 Implement the profile editor with real-time preview  
🔄 Add social media integrations

### **📦 Phase 4: Infrastructure & Deployment (2-3 weeks)**

🔄 Dockerize services  
🔄 Set up Traefik for reverse proxying  
🔄 Deploy and test self-hosting setup

### **🧪 Phase 5: Testing & Beta Release (2-3 weeks)**

🔄 Conduct internal testing  
🔄 Fix bugs and optimize performance  
🔄 Open beta release for early users

### **🌍 Phase 6: Public Launch & Future Features**

🔄 Official public release  
🔄 Continuous improvements based on user feedback

---

## 🔮 Future Features

💡 **Custom Domains** – Link your TailTag page to your own domain  
📹 **More Widgets** – YouTube, Twitch, Discord integration  
💎 **Premium Features** – Paid themes, advanced analytics, custom styles  
📌 **QR Code Generator** – Instantly generate QR codes for sharing

---

## 🎯 Contributing

Want to help make **TailTag** even better? PRs and suggestions are welcome! 🚀

📜 **License**: MIT  
📬 **Contact**: [GitHub Issues](https://github.com/tailtag/hey/issues)

👥 **Join us & create your personal link today!**

🔗 **[tailtag.link](https://tailtag.link)**

---
