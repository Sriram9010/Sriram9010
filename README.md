# 👋 Hi, I'm Sriram Penumala

<!-- Animated 3D-style cube -->
<svg width="320" height="180" viewBox="0 0 320 180" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#00C9FF"/>
      <stop offset="1" stop-color="#92FE9D"/>
    </linearGradient>
    <linearGradient id="g2" x1="0" x2="1">
      <stop offset="0" stop-color="#7F7FD5"/>
      <stop offset="1" stop-color="#86A8E7"/>
    </linearGradient>
    <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="0" dy="6" stdDeviation="10" flood-color="#000" flood-opacity="0.25"/>
    </filter>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" rx="12" fill="transparent"/>

  <!-- cube group (isometric-look) -->
  <g transform="translate(160,90)">
    <!-- animate rotation around center -->
    <animateTransform attributeName="transform"
                      type="rotate"
                      from="0 0 0"
                      to="360 0 0"
                      dur="6s"
                      repeatCount="indefinite"/>
    <!-- shadow -->
    <ellipse cx="0" cy="70" rx="70" ry="18" fill="#000" opacity="0.12"/>

    <!-- top face -->
    <polygon points="-60,-30 0,-70 60,-30 0,10"
             fill="url(#g1)" stroke="#ffffff" stroke-opacity="0.15" stroke-width="1" filter="url(#shadow)"/>

    <!-- left face -->
    <polygon points="-60,-30 0,10 0,60 -60,20"
             fill="url(#g2)" stroke="#ffffff" stroke-opacity="0.10" stroke-width="1"/>

    <!-- right face -->
    <polygon points="60,-30 0,10 0,60 60,20"
             fill="#2b2b2b" fill-opacity="0.90" stroke="#ffffff" stroke-opacity="0.10" stroke-width="1"/>

    <!-- subtle highlight -->
    <path d="M-20,-20 L0,-10 L20,-20" stroke="rgba(255,255,255,0.18)" stroke-width="2" fill="none" />

    <!-- small rotation accent -->
    <g transform="scale(0.8)">
      <circle cx="0" cy="0" r="2.8" fill="#fff" opacity="0.06"/>
    </g>
  </g>

  <!-- label -->
  <text x="10" y="165" font-family="Segoe UI, Roboto, Arial" font-size="12" fill="#666">
    Full-Stack · Java · React · Firebase · MySQL
  </text>
</svg>

---

## 🌟 About Me
- 🎓 **B.Tech in Information Technology** — DRK College of Engineering and Technology (2021–2025)  
- 💻 **Full Stack Developer** building web apps with React, Spring Boot, Firebase and MySQL.  
- ⚡️ I enjoy turning ideas into fast, clean user experiences.

## 🛠️ Tech Stack
**Languages:** `Java` | `JavaScript` | `HTML` | `CSS` | `SQL`  
**Frameworks & Libs:** `React.js` | `Spring Boot` | `Bootstrap`  
**Databases & Platforms:** `MySQL` | `Firebase` | `Node.js`  
**Tools:** `Git` | `GitHub` | `VSCode` | `Eclipse` | `Maven`

## 📂 Projects
- 🍽️ **Catering Reservation App** — A web app to streamline catering bookings & orders.  
  *Tech:* Firebase, JavaScript, HTML, CSS

- 📊 **Exam Result Portal** — A React app to look up and view exam results.  
  *Tech:* React (Vite), HTML, CSS, JavaScript

## 🏅 Certifications
- Full Stack Web Development Internship — **Unified Mentor**  
- Python Certification — **Naresh IT**

## 📫 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhirasamalla/)  
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)](https://github.com/Abhiramrasamalla)

---

> ⭐ Tip: to make the cube even fancier, we can:
> - export a GIF of a 3D model rotating (higher realism), or  
> - host a small WebGL/Three.js demo in GitHub Pages and link it from the README.

Would you like me to (pick one):
1. Export a **high-quality GIF** (3D-look) you can upload to the repo, or  
2. Create a **Three.js** mini-demo page (HTML + JS) and README snippet to embed/link to it?  

If you pick 1 or 2 I’ll produce the full files you can copy into your repo.
