<!-- Animated Banner -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   🏎️  SPEED CODER  •  FULL STACK  •  OPEN SOURCE  🏁        ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

<!-- SVG Animatsiya - Mashina yo'lda harakatlanadi -->
<svg width="800" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="roadGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#1a1a2e;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#16213e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0f3460;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="carBody" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#e94560;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#c0392b;stop-opacity:1" />
    </linearGradient>
  </defs>

  <!-- Road -->
  <rect width="800" height="120" fill="url(#roadGrad)" rx="8"/>
  
  <!-- Road markings - animated -->
  <g>
    <rect x="0" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="130" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="260" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="390" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="520" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="650" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="780" y="58" width="60" height="4" fill="#f39c12" rx="2" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" 
        values="0,0; -800,0" dur="2s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Stars in background -->
  <circle cx="50" cy="15" r="1.5" fill="white" opacity="0.6"/>
  <circle cx="150" cy="25" r="1" fill="white" opacity="0.4"/>
  <circle cx="300" cy="10" r="1.5" fill="white" opacity="0.7"/>
  <circle cx="500" cy="20" r="1" fill="white" opacity="0.5"/>
  <circle cx="650" cy="12" r="1.5" fill="white" opacity="0.6"/>
  <circle cx="750" cy="30" r="1" fill="white" opacity="0.4"/>

  <!-- Car Group - Racing car shape -->
  <g transform="translate(320, 20)">
    <!-- Exhaust smoke -->
    <circle cx="-20" cy="60" r="4" fill="#888" opacity="0.3">
      <animate attributeName="cx" values="-20;-50" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="r" values="4;8" dur="0.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-20" cy="60" r="3" fill="#aaa" opacity="0.2">
      <animate attributeName="cx" values="-20;-60" dur="0.7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0" dur="0.7s" repeatCount="indefinite"/>
      <animate attributeName="r" values="3;10" dur="0.7s" repeatCount="indefinite"/>
    </circle>

    <!-- Car body -->
    <rect x="0" y="40" width="140" height="30" fill="url(#carBody)" rx="6"/>
    <!-- Car top/cabin -->
    <path d="M 25 40 L 45 15 L 100 15 L 115 40 Z" fill="#c0392b"/>
    <!-- Windshield -->
    <path d="M 48 18 L 50 38 L 95 38 L 100 18 Z" fill="#85c1e9" opacity="0.7"/>
    <!-- Side window -->
    <rect x="30" y="22" width="16" height="16" fill="#85c1e9" opacity="0.5" rx="3"/>
    
    <!-- Headlights -->
    <rect x="133" y="45" width="8" height="8" fill="#f9e79f" rx="2"/>
    <circle cx="137" cy="49" r="3" fill="#f4d03f">
      <animate attributeName="opacity" values="1;0.6;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Taillights -->
    <rect x="0" y="48" width="6" height="10" fill="#e74c3c" rx="2">
      <animate attributeName="opacity" values="1;0.5;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    
    <!-- Wheels -->
    <!-- Front wheel -->
    <circle cx="105" cy="72" r="14" fill="#2c3e50"/>
    <circle cx="105" cy="72" r="9" fill="#95a5a6">
      <animateTransform attributeName="transform" type="rotate"
        from="0 105 72" to="360 105 72" dur="0.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="105" cy="72" r="4" fill="#bdc3c7"/>
    
    <!-- Rear wheel -->
    <circle cx="35" cy="72" r="14" fill="#2c3e50"/>
    <circle cx="35" cy="72" r="9" fill="#95a5a6">
      <animateTransform attributeName="transform" type="rotate"
        from="0 35 72" to="360 35 72" dur="0.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="35" cy="72" r="4" fill="#bdc3c7"/>
    
    <!-- Speed lines -->
    <line x1="-5" y1="30" x2="-25" y2="30" stroke="#e74c3c" stroke-width="2" opacity="0.7">
      <animate attributeName="x1" values="-5;-15" dur="0.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0" dur="0.3s" repeatCount="indefinite"/>
    </line>
    <line x1="-5" y1="50" x2="-30" y2="50" stroke="#e74c3c" stroke-width="2" opacity="0.5">
      <animate attributeName="x1" values="-5;-18" dur="0.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0" dur="0.3s" repeatCount="indefinite"/>
    </line>
    <line x1="-5" y1="42" x2="-20" y2="42" stroke="#f39c12" stroke-width="1.5" opacity="0.6">
      <animate attributeName="x1" values="-5;-20" dur="0.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0" dur="0.4s" repeatCount="indefinite"/>
    </line>
  </g>
</svg>

# 👋 Salom! Men [ISMINGIZ]

### 🚀 Tezkor Dasturchi | 💻 Full Stack Developer | 🌍 Toshkent, O'zbekiston

</div>

---

## 🏎️ Men Haqimda

```javascript
const developer = {
  ism:        "Ismingiz",
  joylashuv:  "Toshkent, O'zbekiston 🇺🇿",
  rol:        "Full Stack Developer",
  kod_yozish: "☕ Qahva ichib",
  maqsad:     "Har kuni yangi narsa o'rganish",
  qiziqish:   ["Coding", "Mashina", "Texnologiya", "AI"]
};
```

---

## ⚙️ Texnologiyalar

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 📊 GitHub Statistikam

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=e94560&icon_color=e94560&text_color=ffffff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=e94560&text_color=ffffff)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&theme=radical&hide_border=true&background=0D1117&ring=e94560&fire=e94560&currStreakLabel=e94560)

</div>

---

## 🏁 Loyihalarim

| 🚗 Loyiha | 📝 Tavsif | 🔧 Texnologiya |
|-----------|-----------|----------------|
| [Loyiha 1](https://github.com/USERNAME) | Qisqa tavsif | React, Node.js |
| [Loyiha 2](https://github.com/USERNAME) | Qisqa tavsif | Python, FastAPI |
| [Loyiha 3](https://github.com/USERNAME) | Qisqa tavsif | JavaScript, CSS |

---

## 📡 Bog'lanish

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/USERNAME)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/USERNAME)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:email@gmail.com)

</div>

---

<div align="center">

```
🏎️ Kod yozish - bu marafon emas, sprint! 🏁
```

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=USERNAME.USERNAME&color=e94560)

</div>
