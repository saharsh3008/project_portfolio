# 💼 Saharsh’s Developer Portfolio

A modern, high-performance developer portfolio built to showcase my projects, skills, and professional journey. 

Designed with **Next.js**, **TypeScript**, and **Tailwind CSS**, featuring immersive 3D elements and smooth animations.

---

## 🌟 Live Demo

🔗 **Live Site:** [https://saharshpro.vercel.app](https://saharshpro.vercel.app) 

📁 **Repo:** [https://github.com/saharsh3008/project_portfolio](https://github.com/saharsh3008/project_portfolio)

---

## 🚀 Features

- **Immersive 3D Visuals**: Powered by **Three.js** and **React Three Fiber**.
- **💥 Modern Animations**: Smooth transitions and effects using **Framer Motion**.
- **🎨 Responsive Design**: Fully responsive layout built with **Tailwind CSS**.
- **⚡ High Performance**: Optimized with **Next.js 14** best practices.
- **📊 Real-time Monitoring**: Integrated **Sentry** for error tracking and performance monitoring.
- **🧩 Dynamic Components**:
  - **Hero Section**: Engaging introduction with 3D elements.
  - **Grid / About**: Interactive bento-grid style layout.
  - **Projects**: Showcase of recent work with detailed cards.
  - **Experience**: Timeline view of professional history.
  - **Testimonials**: Client reviews and feedback.
  - **Contact**: Easy-to-use contact options.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animation**: [Framer Motion](https://www.framer.com/motion/)
- **3D Graphics**: [Three.js](https://threejs.org/) / [React Three Fiber](https://docs.pmnd.rs/react-three-fiber)
- **Monitoring**: [Sentry](https://sentry.io/)
- **UI Components**: [Aceternity UI](https://ui.aceternity.com/) (inspired), React Icons

---

## ⚙️ Local Setup

Follow these steps to run the project locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/saharsh3008/project_portfolio.git
    cd project_portfolio
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables:**
    Create a `.env.local` file in the root directory and add your required keys (e.g., Sentry DSN).

4.  **Run the development server:**
    ```bash
    npm run dev
    ```

5.  **Open in Browser:**
    Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

---

## 📂 Project Structure

```bash
├── app/                  # Next.js App Router pages and layouts
├── components/           # Reusable UI components (Hero, Grid, Projects, etc.)
│   └── ui/               # Primitive UI elements
├── data/                 # Static data files
├── public/               # Static assets (images, icons)
├── utils/                # Utility functions
├── sentry.*.config.ts    # Sentry configuration files
├── tailwind.config.ts    # Tailwind CSS configuration
└── tsconfig.json         # TypeScript configuration
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/saharsh3008/project_portfolio/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
