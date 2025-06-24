# 💼 Wealthio – AI Finance Platform

**Wealthio** is a modern personal finance tracking platform powered by AI. It enables users to manage income, track expenses, analyze trends, and visualize financial health — all in a beautiful and responsive web app.

Built using **Next.js 15**, **React 19**, **Tailwind CSS**, **Prisma**, **Supabase**, and **Clerk Authentication**, Wealthio is designed for performance, security, and scalability.

---

## 🚀 Features

* 🔐 Secure Authentication with Clerk
* 💸 Expense & Income Tracking
* 📊 Dashboard with Real-Time Financial Insights
* 🧠 AI-Ready Backend for Analytics and Categorization
* 🗃️ Supabase PostgreSQL with Prisma ORM
* 🎨 Beautiful UI with Tailwind CSS & Shadcn UI
* ⚡️ Optimized for Speed with Turbopack

---

## 🛠️ Tech Stack

| Layer      | Technology              |
| ---------- | ----------------------- |
| Frontend   | Next.js 15, React 19    |
| Styling    | Tailwind CSS, Shadcn UI |
| Auth       | Clerk                   |
| Database   | Supabase PostgreSQL     |
| ORM        | Prisma                  |
| Deployment | Vercel (recommended)    |

---

## 📦 Folder Structure

```bash
wealthio/
├── app/                 # App routes and pages
│   ├── (auth)/          # Clerk Auth Pages
│   └── (main)/          # Main App Pages (Dashboard, Transactions)
├── lib/                 # Prisma Client and Utility Functions
├── prisma/              # Prisma Schema and Migrations
├── styles/              # Tailwind Configuration
├── public/              # Static Assets
├── .env                 # Environment Variables
└── README.md
```

---

## ⚙️ Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/wealthio.git
   cd wealthio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file:

   ```env
   DATABASE_URL="your-supabase-url"
   DIRECT_URL="your-supabase-direct-url"
   CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
   CLERK_SECRET_KEY="your-clerk-secret-key"
   ```

4. **Push Prisma schema to the database**

   ```bash
   npx prisma db push
   ```

5. **Run the development server**

   ```bash
   npm run dev
   ```

---

## 📈 Roadmap

* [ ] Add AI-Powered Insights
* [ ] Budget Goals & Reminders
* [ ] Visual Financial Reports
* [ ] Mobile-first PWA Experience

---

## 👤 Author

**Ayush Ranjan**
3rd Year, IIIT Allahabad
📫 [ayushranjan@iiita.ac.in](mailto:ayushranjan112400@Gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ayush-ranjan-a37955268/) • [GitHub](https://github.com/Darth-hub)

---

## 📄 License

Licensed under the [MIT License](LICENSE).
