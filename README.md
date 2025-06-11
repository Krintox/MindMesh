# 🧠 MindMesh – Your Second Brain for Work & Ideas  
> Built by [Shashank Suggala (Krintox)](https://github.com/Krintox) · 📧 shashanktsx@gmail.com

**MindMesh** is a powerful workspace for note-taking, task management, and knowledge organization — all in one place. It lets you build documents and dashboards using blocks, pages, and drag-and-drop flexibility.

Whether you're planning a project, documenting ideas, or collaborating with a team — MindMesh gives you the structure and freedom to do it your way.

---

## 🚀 Features at a Glance

- 🧱 **Block-Based Editor**  
  Mix and match text, images, lists, tables, and more — every page is built from flexible blocks.

- 🔁 **Real-Time Collaboration**  
  Work together live, with instant syncing and conflict-free editing across devices.

- 🧭 **Nested Pages & Linked References**  
  Organize your thoughts with hierarchical pages or interconnect them with backlinks.

- 🌗 **Light & Dark Themes**  
  Switch effortlessly between modes to reduce eye strain and fit your vibe.

- 🧾 **Databases with Views**  
  Build tables, kanban boards, calendars, and gallery views — filter and sort like a pro.

- 🔐 **Authentication & Access Control**  
  Sign in securely and manage who can view or edit your content.

- 📤 **Drag-and-Drop File Uploads**  
  Embed images, PDFs, videos, and other files directly into your workspace.

- 🎯 **Icons, Covers & Customization**  
  Personalize every page with icons and covers to visually structure your workspace.

- 📱 **Responsive Design**  
  Fully optimized for desktops, tablets, and smartphones — always ready to go.

- 🌐 **Sharable Public Pages**  
  Publish any page with a public link — perfect for blogs, docs, or portfolios.

---

## 🧰 Tech Stack

- **Frontend**: Next.js 13, TailwindCSS, React
- **Backend**: Convex (real-time syncing)
- **Auth**: Clerk
- **File Uploads**: Edge Store

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Krintox/mindmesh.git
cd mindmesh
````

### 2. Install Packages

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file with the following keys:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### 4. Start Convex Locally

```bash
npx convex dev
```

### 5. Run the Development Server

```bash
npm run dev
```

Visit: `http://localhost:3000`

---

## 🤝 Get Involved

Have feedback or want to contribute? Open a PR, report an issue, or just drop a message!

* GitHub: [Krintox](https://github.com/Krintox)
* Email: [shashanktsx@gmail.com](mailto:shashanktsx@gmail.com)

---

## 🧭 Roadmap Highlights

* AI-assisted writing & task generation
* Role-based team workspaces
* Plugin system for extensibility (Notion-style integrations)

---

## 📄 License

MIT License — Free to use and adapt.
