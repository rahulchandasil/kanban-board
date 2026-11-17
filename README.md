# 📋 Kanban Board — Full-Stack Task Management Application

A modern, full-stack **Kanban task management application** built with **Next.js**, **TypeScript**, and **dnd-kit**. Designed for smooth productivity workflows, it enables users to organize tasks across customizable columns with intuitive drag-and-drop interactions, real-time persistence, and secure authentication.

🌐 **Live Demo:** [https://vercel.app](https://vercel.app)  
💻 **Repository:** [://github.com](https://://github.com)

---

## ✨ Key Features

- **Drag-and-Drop Workflow:** Smooth, accessible card and column reordering powered by **`@dnd-kit`**.
- **Board & Task Management:** Create, edit, organize, and delete tasks across workflow stages (e.g., *To Do*, *In Progress*, *Done*).
- **Due Dates & Task Details:** Assign due dates, descriptions, and priority tracking to stay on top of deadlines.
- **Secure Authentication:** Sign up and log in using email/password authentication or **Google OAuth**.
- **Real-Time Database Persistence:** Instant synchronization of board states and task updates across sessions.
- **Type-Safe Architecture:** Built end-to-end with **TypeScript** for cleaner code maintainability and fewer runtime bugs.

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Language:** TypeScript
- **Drag & Drop:** `@dnd-kit/core`, `@dnd-kit/sortable`
- **Styling:** Tailwind CSS
- **Authentication:** Google OAuth / Session Auth
- **Deployment:** Vercel

---

## 📂 Project Structure

```text
kanban-board/
├── public/                 # Static assets & preview screenshots
├── src/
│   ├── app/                # Next.js App Router pages & API routes
│   ├── components/         # Kanban Board, Column, TaskCard, Modals
│   ├── hooks/              # Custom hooks for drag-and-drop & state
│   ├── lib/                # Database & Auth configuration
│   └── types/              # TypeScript interfaces for Boards & Tasks
├── package.json
└── tsconfig.json
```

---

## 🚀 Run Locally

### Prerequisites
- Node.js (v18 or higher)

### 1. Clone the Repository
```bash
git clone https://://github.com.git
cd kanban-board
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create a `.env.local` file in the root directory and add your database and authentication keys:
```env
# Add your required environment variables here (e.g., DATABASE_URL, GOOGLE_CLIENT_ID, etc.)
```

### 4. Start the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## 📸 Project Preview

*(Delete this line and drag-and-drop a screenshot of your live Kanban board directly into the GitHub editor here so the broken image icon disappears!)*

---

## 👨‍💻 Author

**Rahul Chanda Sil**  
- **GitHub:** [@rahulchandasil](https://github.com)  
- **LinkedIn:** [Rahul Chanda Sil](https://linkedin.com)  
- **Location:** Kolkata, West Bengal, India
