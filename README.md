# QuickAI – Full Stack AI SaaS App


Build a fully functional **AI SaaS application** with subscriptions and AI-powered features using the **PERN stack** (PostgreSQL, Express, React, Node.js).

---

## 🚀 Features

### User Authentication
- Secure sign-up, sign-in, and profile management using **Clerk**.  
- Role-based access for standard and premium users.

### Subscription Billing
- Premium subscription plans to unlock advanced AI features.
- Integrated subscription billing with seamless management.

### Database
- Serverless **PostgreSQL** database powered by **Neon**.

---

## 🤖 AI Features

- **Article Generator** – Generate full articles by providing a title and length.  
- **Blog Title Generator** – Generate blog titles based on keywords and category.  
- **Image Generator** – Generate AI images using custom prompts.  
- **Background Remover** – Remove backgrounds from uploaded images.  
- **Image Object Remover** – Remove objects from images effortlessly.  

---

## 🛠️ Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express  
- **Database:** PostgreSQL (via Neon)  
- **Authentication:** Clerk  
- **Deployment:** Vercel  

---

## 📥 Installation

```bash
# Clone the repository
git clone : https://github.com/raisulislambup/quickai-saas.git
cd quickai-saas

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Run the development server
npm run dev
