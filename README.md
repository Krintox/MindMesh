# 🧠 MindMesh – The Digital Brain for Ideas & Execution  
> Built by [Shashank Suggala (Krintox)](https://github.com/Krintox) · 📧 shashanktsx@gmail.com

![MindMesh Banner](https://your-own-banner-image.com/mindmesh.png)

**MindMesh** is a next-gen digital thinking environment — a connected space to build your thoughts, documents, and workflows as living, evolving branches of your digital brain.

Designed for thinkers, makers, and doers — MindMesh gives you fluid knowledge organization, multi-layered pages, and a deeply personal yet collaborative experience.

---

## 🚀 Core Capabilities

- ⚡ **LiveSync Engine**  
  Your ideas update in real-time across devices — powered by a reactive backend.

- 🧩 **Node-Based Workspace**  
  Create multi-level, linked knowledge nodes instead of traditional folders or files.

- 🌓 **Dual Light & Night Modes**  
  Tailor your workspace to your mood or setting with immersive color themes.

- 🧵 **Threaded Mind Pages**  
  Pages can contain infinitely connected sub-thoughts, letting you drill down contextually.

- 🗂️ **Archive & Revive**  
  Soft-delete lets you stash content in a separate zone until you're ready to bring it back.

- 🧑‍🚀 **Secure Identity Layers**  
  Integrated auth ensures your thoughts stay yours — safe and personal.

- 📎 **Drag & Drop Attachments**  
  Instantly enhance your nodes with media and files — replace, rename, delete seamlessly.

- 🎭 **Smart Node Icons**  
  Add icons to your ideas to make them more visually scannable — updated in real-time.

- 📱 **Responsive Neural Grid**  
  Use it fluidly on desktop, mobile, or tablets — your Mesh follows your flow.

- 🌍 **Public Brain Links**  
  Publish nodes to the world via sharable links, ideal for blogs, pages, or documentation.

- 🧱 **Collapsable Mind Zones**  
  Collapse layers of thoughts and re-expand later to reduce clutter.

- 🎨 **Visual Entry Pages**  
  Each mesh node can have a beautiful cover to help personalize your knowledge space.

---

## 🧰 Tech Stack

- **Frontend**: Next.js 13, TailwindCSS, React
- **Backend**: Convex (for real-time data sync)
- **Auth**: Clerk
- **Media Uploads**: Edge Store

---

## 📦 Setup Instructions

### 1. Clone the MindMesh Repo

```bash
git clone https://github.com/Krintox/mindmesh.git
cd mindmesh
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file and include the following:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### 4. Initialize Convex

```bash
npx convex dev
```

### 5. Run the App

```bash
npm run dev
```

App runs on `http://localhost:3000`

---

## 🤝 Contribute or Connect

Want to contribute ideas or enhancements? Open an issue or reach out!

* GitHub: [Krintox](https://github.com/Krintox)
* Email: [shashanktsx@gmail.com](mailto:shashanktsx@gmail.com)

---

## 🔮 Future Roadmap

* AI-powered mind expansion suggestions
* Team-level node sharing
* Plugin integrations (calendars, to-dos, trackers)

---

## ⚖️ License

MIT – free for personal & commercial use.
