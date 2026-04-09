# 🚀 Portfolio Website

A modern portfolio website for **Vanz Rey Alsado**, built with React, TypeScript, Three.js, GSAP, and TailwindCSS.

---

## ⚡ Installation & Setup

### Step 1 — Ensure Node.js is Installed
```bash
node -v
# Should display v18.x.x or newer
# If not installed: download from https://nodejs.org
```

### Step 2 — Extract the zip and navigate to the folder
```bash
cd portfolio
```

### Step 3 — Install all dependencies
```bash
npm install
```

### Step 4 — Start the development server
```bash
npm run dev
```
Open: **http://localhost:3000** 🎉

---

## 📦 Included Packages

| Package | Purpose |
|---------|---------|
| react + react-dom | UI Framework |
| typescript | Type Safety |
| vite | Build tool & dev server (port 3000) |
| three + postprocessing | PixelBlast WebGL background |
| gsap | Scroll & stagger animations |
| motion | Framer Motion animations |
| tailwindcss | CSS utilities |
| lucide-react | Icon library |

---

## 🌐 Free Deployment

**Vercel (Recommended):**
```bash
npm install -g vercel
vercel login
vercel
```

**Netlify:** Build first (`npm run build`), then drag-drop the `dist/` folder to netlify.com/drop

---

## 🎨 Customization

**Change profile photo (9:16 aspect):** Place your photo in `public/foto.jpg`, then update `AboutSection.tsx`:
```tsx
<TiltCard src="/foto.jpg" alt="Vanz Rey Alsado" className="w-56" style={{ aspectRatio: '9/16' }} />
```

**Social media links:** Edit the `href` values in the `SOCIAL` array in `ContactSection.tsx`

**Projects:** Edit the `PROJECTS` array in `ProjectsSection.tsx`

---

## Available Commands
```bash
npm run dev      # Start dev server at localhost:3000
npm run build    # Build for production
npm run preview  # Preview production build
```
