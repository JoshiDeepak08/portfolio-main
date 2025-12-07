# Portfolio — Deepak Joshi


A modern developer portfolio built using **TypeScript**, **React**, and **Tailwind CSS**.
This portfolio showcases my projects, skills, experiences, and achievements with clean UI design, smooth animations, and modular components — optimized for performance and scalability.

---

## **Live Demo**

**Website:** [https://your-portfolio-link-here.com]([https://your-portfolio-link-here.com](https://portfolio-main-tan-three.vercel.app/))


---

##  **Project Screenshot**

<img width="525" height="635" alt="image" src="https://github.com/user-attachments/assets/7502de03-ef58-4879-b14b-2315e3effae8" />

---

# **How to Run the Project Locally**

### **1. Clone the Repository**

```bash
git clone https://github.com/JoshiDeepak08/portfolio-main.git
cd portfolio-main
```

### **2. Install Dependencies**

```bash
npm install
```

### **3. Start Development Server**

```bash
npm run dev
```

Your app will now run at:

```
http://localhost:5173
```

### **4. Build for Production**

```bash
npm run build
```

---

# **Architecture & Key Decisions**

### **Tech Stack**

* **React + TypeScript** → type safety & scalable component structure
* **Tailwind CSS** → utility-first styling for rapid UI development
* **ShadCN UI Components** → consistent, accessible UI building blocks
* **Framer Motion** → smooth animations and transition effects
* **Vite** → blazing-fast bundler for modern frontend apps

### **Key Decisions**

1. **Component-driven architecture** → clean separation of UI sections like Hero, Projects, Skills, Contact.
2. **Config-based project list** → All projects are stored as objects, making them easy to update & manage.
3. **Tailwind theming** → Enables consistent brand colors, dark/light modes, and responsive layouts.
4. **Minimal dependencies** → Ensures fast load times & high Lighthouse scores.
5. **Mobile-first design** → The portfolio is fully optimized for phones, tablets, and desktop screens.

---

# **Approach**

The goal was to build a **high-performance, aesthetically modern**, and **flexible** portfolio that can:

* Display key projects with screenshots, stack icons, and external links
* Present skills using categorized badges
* Highlight achievements and real-world experience
* Provide a clean and elegant first impression to recruiters & clients
* Remain easy to update as new projects or experiences are added

Every section is modular and driven by JSON-like config files, making the portfolio maintainable and future-proof.

---

# **Flow Design**

### **User → Browser → React UI → Project Config → Render Components**

1. **React loads configuration** (projects, skills, links).
2. UI components dynamically render cards, grids, buttons, and animations.
3. Images + icons are optimized via Vite.
4. Components rely on Tailwind for instant styling.
5. Deployments (e.g., Vercel) bundle and serve static assets efficiently.

This ensures:

* Near-instant load times
* SEO-friendly metadata
* Mobile-responsiveness
* Highly customizable visual layout

---

# **Challenges & Trade-offs**

### **Challenges**

* Ensuring consistent animations across devices
* Managing responsive design for complex grid layouts
* Choosing a UI library that integrates smoothly with Tailwind
* Balancing aesthetic design with maintainable structure

### **Trade-offs**

* Using **many animations** can impact initial load time on low-end devices
* Heavy reliance on Tailwind means less CSS flexibility for newcomers
* Static project config requires manual updates — no CMS integration (by design for speed)


