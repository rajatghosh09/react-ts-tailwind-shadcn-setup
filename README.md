#  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="React Logo" width="30" /> React + Vite + TypeScript + Tailwind + shadcn/ui
 react-ts-tailwind-shadcn-setup
This is a full setup for React with Vite and Tailwind CSS and shadcn

## 🚀 Tech Stack

- [Vite](https://vitejs.dev/) – Fast build tool  
- [React](https://reactjs.org/) – UI library  
- [TypeScript](https://www.typescriptlang.org/) – Type safety  
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling  
- [shadcn/ui](https://ui.shadcn.com/) – Re-usable UI components  

---

## 🧱 Installation & Setup

### 1. If you are in PowerShell, do this
```bash
cd 'directory name'
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### 2. Create project
```bash
npm create vite@latest
# Select: React
# Select: React + TypeScript
#Use rolldown-vite (Experimental)?:
#Select: No
#Install with npm and start now?
#Select: Yes
```

### Start a development server
```bash
npm run dev
```

### 2. Install Tailwind CSS
```bash
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p
```
### H1: Update tailwind.config.js:
