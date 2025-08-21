# 🌐 Web Portfolio

Sebuah website portofolio pribadi berbasis **Next.js** untuk menampilkan profil, skill, dan project yang pernah saya kerjakan.  
Dibangun dengan desain modern, mendukung dark/light mode, dan mudah dikembangkan untuk menambahkan project baru di masa depan.  

---

## 🚀 Tech Stack
- **Next.js (App Router)**
- **Tailwind CSS**
- **Shadcn UI**
- **TypeScript**
- **Dark/Light Mode Support**
- **Sora Font (Google Fonts)**
- **PostCSS + Autoprefixer**
- **Framer Motion**
- **Spline / Three.js**
- **PostgreSQL**
- **Prisma**

---

## 🎨 Fitur Utama
- 🏠 **Landing Page**: Profil singkat, headline, dan call-to-action  
- 👨‍💻 **About Section**: Info tentang saya dan skill utama  
- 📂 **Projects Showcase**: Daftar project dengan deskripsi, screenshot, dan link ke repo/demo  
- 📊 **Experience/Stats**: Timeline pengalaman & GitHub stats integration  
- 📬 **Contact Form**: Form untuk langsung menghubungi saya via email  
- 🌗 **Dark/Light Mode**: Modern theme toggle untuk pengalaman pengguna yang lebih baik  

---

## 🧱 Struktur Proyek (Simplified)

/app  
├── layout.tsx → Root layout + Theme provider  
├── page.tsx → Landing page  
├── about/ → Tentang saya  
├── projects/ → Showcase project  
├── contact/ → Kontak form  
└── settings/ → Preferensi user  

/components  
├── Hero.tsx  
├── ProjectCard.tsx  
├── Navbar.tsx  
├── Footer.tsx  
├── ThemeToggle.tsx  
└── ContactForm.tsx  

/fonts  
└── sora.ts → Import Google Fonts Sora  

/styles  
└── globals.css  

---

## 🧩 Instalasi & Development

```bash
# Clone repo
git clone https://github.com/your-username/web-portfolio.git
cd web-portfolio

# Install dependencies
npm install

# Run development server
npm run dev
