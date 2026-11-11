<div align="center">

<!--
  ╔══════════════════════════════════════════════════════════╗
  ║           CLINTMADEIT — GITHUB PROFILE README            ║
  ║         John Clinton Luseno · Full Stack Engineer        ║
  ╚══════════════════════════════════════════════════════════╝
-->

<!-- ═══════════════ ANIMATED HERO BANNER ═══════════════ -->
<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="heroBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a"/>
      <stop offset="60%" style="stop-color:#0f0f23"/>
      <stop offset="100%" style="stop-color:#12122e"/>
    </linearGradient>
    <!-- Brand gradient left→right -->
    <linearGradient id="brandGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4"/>
      <stop offset="45%" style="stop-color:#3b82f6"/>
      <stop offset="100%" style="stop-color:#8b5cf6"/>
    </linearGradient>
    <!-- Brand gradient diagonal for accents -->
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0.1"/>
    </linearGradient>
    <!-- Glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Soft glow for name text -->
    <filter id="nameGlow" x="-10%" y="-40%" width="120%" height="180%">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Particle glow -->
    <filter id="dotGlow" x="-100%" y="-100%" width="300%" height="300%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#heroBg)" rx="20"/>

  <!-- Subtle grid -->
  <g opacity="0.04" stroke="#06b6d4" stroke-width="0.8">
    <line x1="0" y1="56" x2="900" y2="56"/>
    <line x1="0" y1="112" x2="900" y2="112"/>
    <line x1="0" y1="168" x2="900" y2="168"/>
    <line x1="0" y1="224" x2="900" y2="224"/>
    <line x1="112" y1="0" x2="112" y2="280"/>
    <line x1="225" y1="0" x2="225" y2="280"/>
    <line x1="337" y1="0" x2="337" y2="280"/>
    <line x1="450" y1="0" x2="450" y2="280"/>
    <line x1="562" y1="0" x2="562" y2="280"/>
    <line x1="675" y1="0" x2="675" y2="280"/>
    <line x1="787" y1="0" x2="787" y2="280"/>
  </g>

  <!-- Animated particles -->
  <circle cx="112" cy="56" r="2.5" fill="#06b6d4" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="337" cy="112" r="2" fill="#3b82f6" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.6;0" dur="4s" begin="0.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="562" cy="56" r="2.5" fill="#8b5cf6" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.7;0" dur="3.5s" begin="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="787" cy="168" r="2" fill="#ec4899" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.6;0" dur="2.8s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="225" cy="224" r="1.8" fill="#06b6d4" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.5;0" dur="4.2s" begin="1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="675" cy="224" r="2" fill="#8b5cf6" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.6;0" dur="3.2s" begin="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="168" r="1.5" fill="#ec4899" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.5;0" dur="5s" begin="0.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Animated scanning line -->
  <rect x="0" y="0" width="900" height="1.5" fill="url(#brandGrad)" opacity="0">
    <animate attributeName="y" from="0" to="278" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0.15;0.15;0" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- Left decorative circuit -->
  <g opacity="0.5" filter="url(#glow)">
    <path d="M 60,100 L 60,140 L 100,140" stroke="#06b6d4" stroke-width="1.5" fill="none" stroke-dasharray="4,2">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="2s" repeatCount="indefinite"/>
    </path>
    <circle cx="60" cy="100" r="3" fill="#06b6d4" opacity="0.8"/>
    <circle cx="100" cy="140" r="3" fill="#06b6d4" opacity="0.8"/>
    <path d="M 40,160 L 80,160 L 80,180" stroke="#3b82f6" stroke-width="1.5" fill="none" stroke-dasharray="4,2">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="2.5s" repeatCount="indefinite"/>
    </path>
    <circle cx="40" cy="160" r="2.5" fill="#3b82f6" opacity="0.7"/>
  </g>

  <!-- Right decorative circuit -->
  <g opacity="0.5" filter="url(#glow)">
    <path d="M 840,100 L 840,140 L 800,140" stroke="#8b5cf6" stroke-width="1.5" fill="none" stroke-dasharray="4,2">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="2.2s" repeatCount="indefinite"/>
    </path>
    <circle cx="840" cy="100" r="3" fill="#8b5cf6" opacity="0.8"/>
    <circle cx="800" cy="140" r="3" fill="#8b5cf6" opacity="0.8"/>
    <path d="M 860,160 L 820,160 L 820,180" stroke="#ec4899" stroke-width="1.5" fill="none" stroke-dasharray="4,2">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="3s" repeatCount="indefinite"/>
    </path>
    <circle cx="860" cy="160" r="2.5" fill="#ec4899" opacity="0.7"/>
  </g>

  <!-- Animated sound bars (bottom left) -->
  <g transform="translate(130, 230)" opacity="0.6">
    <rect x="0"  y="0" width="4" height="20" fill="#06b6d4" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.3;1,1;1,0.6;1,0.9;1,0.3" dur="1.4s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="8"  y="0" width="4" height="20" fill="#3b82f6" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.9;1,0.4;1,1;1,0.5;1,0.9" dur="1.1s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="16" y="0" width="4" height="20" fill="#8b5cf6" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.5;1,1;1,0.3;1,0.8;1,0.5" dur="1.6s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="24" y="0" width="4" height="20" fill="#ec4899" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.7;1,0.3;1,0.9;1,0.4;1,0.7" dur="0.9s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="32" y="0" width="4" height="20" fill="#06b6d4" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.4;1,0.8;1,0.2;1,1;1,0.4" dur="1.3s" repeatCount="indefinite" additive="sum"/>
    </rect>
  </g>

  <!-- Animated sound bars (bottom right, mirrored) -->
  <g transform="translate(734, 230)" opacity="0.6">
    <rect x="0"  y="0" width="4" height="20" fill="#06b6d4" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.4;1,0.8;1,0.2;1,1;1,0.4" dur="1.3s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="8"  y="0" width="4" height="20" fill="#3b82f6" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.7;1,0.3;1,0.9;1,0.4;1,0.7" dur="0.9s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="16" y="0" width="4" height="20" fill="#8b5cf6" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.5;1,1;1,0.3;1,0.8;1,0.5" dur="1.6s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="24" y="0" width="4" height="20" fill="#ec4899" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.9;1,0.4;1,1;1,0.5;1,0.9" dur="1.1s" repeatCount="indefinite" additive="sum"/>
    </rect>
    <rect x="32" y="0" width="4" height="20" fill="#06b6d4" rx="2" transform-origin="2 20" transform="scale(1,-1) translate(0,-20)">
      <animateTransform attributeName="transform" type="scale" values="1,0.3;1,1;1,0.6;1,0.9;1,0.3" dur="1.4s" repeatCount="indefinite" additive="sum"/>
    </rect>
  </g>

  <!-- Main name text -->
  <text x="450" y="118" text-anchor="middle"
    font-family="'Courier New', Courier, monospace"
    font-size="42" font-weight="900" letter-spacing="2"
    fill="url(#brandGrad)" filter="url(#nameGlow)">
    John Clinton Luseno
  </text>

  <!-- Handle -->
  <text x="450" y="148" text-anchor="middle"
    font-family="'Courier New', Courier, monospace"
    font-size="14" fill="#64748b" letter-spacing="6">
    @clintmadeit
  </text>

  <!-- Animated divider line -->
  <line x1="300" y1="162" x2="600" y2="162" stroke="url(#brandGrad)" stroke-width="1" opacity="0.6">
    <animate attributeName="x1" values="300;250;300" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="600;650;600" dur="4s" repeatCount="indefinite"/>
  </line>

  <!-- Roles tagline -->
  <text x="450" y="186" text-anchor="middle"
    font-family="'Courier New', Courier, monospace"
    font-size="13" fill="#94a3b8" letter-spacing="1">
    &lt; Full Stack · Sound Engineering · UI/UX Design /&gt;
  </text>

  <!-- Bottom brand strip -->
  <rect x="0" y="260" width="900" height="20" fill="url(#accentGrad)" rx="0"/>
  <rect x="0" y="260" width="900" height="20" fill="none" rx="0"/>
  <text x="450" y="274" text-anchor="middle"
    font-family="'Courier New', Courier, monospace"
    font-size="9" fill="#475569" letter-spacing="8">
    CLINTMADEIT · KENYA · BUILDING WHAT MATTERS
  </text>

  <!-- Corner ornaments -->
  <g opacity="0.4" stroke="url(#brandGrad)" stroke-width="1.5" fill="none">
    <path d="M 20,20 L 20,8 L 32,8"/>
    <path d="M 880,20 L 880,8 L 868,8"/>
    <path d="M 20,260 L 20,252 L 32,252"/>
    <path d="M 880,260 L 880,252 L 868,252"/>
  </g>
</svg>

<br/>

<!-- Typing animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=2800&pause=900&color=8B5CF6&center=true&vCenter=true&multiline=false&width=650&height=40&lines=Building+production-ready+systems+from+Kenya+%F0%9F%87%B0%F0%9F%87%AA;Next.js+%7C+NestJS+%7C+React+Native+%7C+PostgreSQL+%7C+Docker;Crafting+interfaces+that+feel+inevitable+%E2%9C%A8;Live+sound+%E2%80%94+where+physics+meets+feeling+%F0%9F%8E%9B%EF%B8%8F;Systems+that+scale%2C+UX+that+flows%2C+sound+that+moves)](https://git.io/typing-svg)

<br/>

<!-- Profile view counter + social proof -->
[![Profile Views](https://komarev.com/ghpvc/?username=clintmadeit&color=8b5cf6&style=flat-square&label=Profile+Views)](https://github.com/clintmadeit)
&nbsp;&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/clintmadeit?style=flat-square&color=06b6d4&labelColor=0f0f23&label=Followers&logo=github&logoColor=white)](https://github.com/clintmadeit?tab=followers)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/Let's_connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johnclinton-luseno/)

</div>

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#06b6d4;stop-opacity:0.6"/>
      <stop offset="50%" style="stop-color:#8b5cf6;stop-opacity:0.8"/>
      <stop offset="70%" style="stop-color:#ec4899;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#ec4899;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q112,5 225,20 T450,20 T675,20 T900,20" stroke="url(#waveGrad)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q112,5 225,20 T450,20 T675,20 T900,20;
              M0,20 Q112,35 225,20 T450,20 T675,20 T900,20;
              M0,20 Q112,5 225,20 T450,20 T675,20 T900,20"
      dur="4s" repeatCount="indefinite"/>
  </path>
  <path d="M0,22 Q225,10 450,22 T900,22" stroke="url(#waveGrad)" stroke-width="0.8" fill="none" opacity="0.4">
    <animate attributeName="d"
      values="M0,22 Q225,10 450,22 T900,22;
              M0,22 Q225,34 450,22 T900,22;
              M0,22 Q225,10 450,22 T900,22"
      dur="5s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## 👨‍💻 About Me

```typescript
const clintmadeit = {
  name     : "John Clinton Luseno",
  handle   : "@clintmadeit",
  location : "Kenya 🇰🇪",

  craft: [
    "Full Stack Engineering  — web, mobile, and cloud-native systems",
    "Live Sound Engineering  — concerts, events, studio sessions",
    "UI/UX Design            — interfaces that feel inevitable",
  ],

  currently_building: [
    "Luzora     — cloud-native travel booking platform",
    "e-Poultry  — agri-tech marketplace (web + mobile + API)",
    "JnB        — multi-tenant cleaning services platform",
  ],

  stack: {
    frontend  : ["Next.js 15", "React", "Vite", "TypeScript", "Tailwind CSS", "Framer Motion"],
    backend   : ["NestJS", "Node.js", "Express", "REST", "WebSockets"],
    mobile    : ["React Native", "Expo"],
    data      : ["PostgreSQL", "MongoDB", "Supabase", "Redis"],
    devops    : ["Docker", "GitHub Actions", "Render", "Vercel", "Caddy"],
    design    : ["Figma", "Design Systems", "Accessibility", "Motion Design"],
    sound     : ["Live Mixing", "Studio Recording", "FOH Engineering"],
  },

  philosophy: "Build systems that scale, craft UX that flows, mix sound that moves.",
};
```

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#8b5cf6;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#8b5cf6;stop-opacity:0.5"/>
      <stop offset="50%" style="stop-color:#06b6d4;stop-opacity:0.7"/>
      <stop offset="75%" style="stop-color:#3b82f6;stop-opacity:0.5"/>
      <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q225,8 450,20 T900,20" stroke="url(#waveGrad2)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q225,8 450,20 T900,20;M0,20 Q225,32 450,20 T900,20;M0,20 Q225,8 450,20 T900,20"
      dur="5s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## ⚡ Tech Stack

<div align="center">

**— Frontend & Mobile —**

![Next.js](https://img.shields.io/badge/Next.js-0a0a1a?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-0a0a1a?style=for-the-badge&logo=react&logoColor=06b6d4)
![React Native](https://img.shields.io/badge/React_Native-0a0a1a?style=for-the-badge&logo=react&logoColor=3b82f6)
![TypeScript](https://img.shields.io/badge/TypeScript-0a0a1a?style=for-the-badge&logo=typescript&logoColor=3b82f6)
![Vite](https://img.shields.io/badge/Vite-0a0a1a?style=for-the-badge&logo=vite&logoColor=8b5cf6)
![Tailwind](https://img.shields.io/badge/Tailwind-0a0a1a?style=for-the-badge&logo=tailwindcss&logoColor=06b6d4)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0a0a1a?style=for-the-badge&logo=framer&logoColor=ec4899)
![Expo](https://img.shields.io/badge/Expo-0a0a1a?style=for-the-badge&logo=expo&logoColor=white)

**— Backend & Data —**

![NestJS](https://img.shields.io/badge/NestJS-0a0a1a?style=for-the-badge&logo=nestjs&logoColor=ec4899)
![Node.js](https://img.shields.io/badge/Node.js-0a0a1a?style=for-the-badge&logo=node.js&logoColor=4ade80)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a0a1a?style=for-the-badge&logo=postgresql&logoColor=3b82f6)
![MongoDB](https://img.shields.io/badge/MongoDB-0a0a1a?style=for-the-badge&logo=mongodb&logoColor=4ade80)
![Supabase](https://img.shields.io/badge/Supabase-0a0a1a?style=for-the-badge&logo=supabase&logoColor=4ade80)
![Redis](https://img.shields.io/badge/Redis-0a0a1a?style=for-the-badge&logo=redis&logoColor=ec4899)
![Prisma](https://img.shields.io/badge/Prisma-0a0a1a?style=for-the-badge&logo=prisma&logoColor=white)

**— DevOps & Cloud —**

![Docker](https://img.shields.io/badge/Docker-0a0a1a?style=for-the-badge&logo=docker&logoColor=06b6d4)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0a0a1a?style=for-the-badge&logo=githubactions&logoColor=8b5cf6)
![Vercel](https://img.shields.io/badge/Vercel-0a0a1a?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-0a0a1a?style=for-the-badge&logo=render&logoColor=4ade80)
![Nginx](https://img.shields.io/badge/Nginx-0a0a1a?style=for-the-badge&logo=nginx&logoColor=4ade80)
![Caddy](https://img.shields.io/badge/Caddy-0a0a1a?style=for-the-badge&logo=caddy&logoColor=06b6d4)

**— Design & Sound —**

![Figma](https://img.shields.io/badge/Figma-0a0a1a?style=for-the-badge&logo=figma&logoColor=ec4899)
![Sound Engineering](https://img.shields.io/badge/🎛️_FOH_Engineering-0a0a1a?style=for-the-badge&logoColor=f59e0b)
![Studio Recording](https://img.shields.io/badge/🎙️_Studio_Recording-0a0a1a?style=for-the-badge&logoColor=f59e0b)

</div>

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#06b6d4;stop-opacity:0.6"/>
      <stop offset="60%" style="stop-color:#8b5cf6;stop-opacity:0.7"/>
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q150,32 300,20 T600,20 T900,20" stroke="url(#waveGrad3)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q150,32 300,20 T600,20 T900,20;M0,20 Q150,8 300,20 T600,20 T900,20;M0,20 Q150,32 300,20 T600,20 T900,20"
      dur="4.5s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## 🚀 Featured Projects

<div align="center">

<!-- Row 1 -->
<table>
<tr>
<td width="50%" valign="top">

<div align="center">

### ✈️ Luzora Travel Platform

</div>

Cloud-native travel booking platform — hotels, flights, SGR ticketing, Airbnb-style listings, AI recommendations, loyalty program, and corporate travel tools.

<br/>

![Next.js](https://img.shields.io/badge/-Next.js-0a0a1a?style=flat-square&logo=next.js&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-0a0a1a?style=flat-square&logo=nestjs&logoColor=ec4899)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-0a0a1a?style=flat-square&logo=postgresql&logoColor=3b82f6)
![Docker](https://img.shields.io/badge/-Docker-0a0a1a?style=flat-square&logo=docker&logoColor=06b6d4)
![Redis](https://img.shields.io/badge/-Redis-0a0a1a?style=flat-square&logo=redis&logoColor=ec4899)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/luzora)
[![Live Site](https://img.shields.io/badge/🌐_luzoratravel.com-06b6d4?style=flat-square&logoColor=white)](https://luzoratravel.com)

</td>
<td width="50%" valign="top">

<div align="center">

### 🏥 Hali Health & Wellness

</div>

Concierge healthcare platform for a US-based clinic — in-home visits, telemedicine, booking, patient portal, and QR-code scheduling. Live in production.

<br/>

![Next.js](https://img.shields.io/badge/-Next.js-0a0a1a?style=flat-square&logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-0a0a1a?style=flat-square&logo=supabase&logoColor=4ade80)
![TypeScript](https://img.shields.io/badge/-TypeScript-0a0a1a?style=flat-square&logo=typescript&logoColor=3b82f6)
![Vercel](https://img.shields.io/badge/-Vercel-0a0a1a?style=flat-square&logo=vercel&logoColor=white)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/halihealth)
[![Live Site](https://img.shields.io/badge/🌐_halihealth.net-06b6d4?style=flat-square&logoColor=white)](https://halihealth.net)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<div align="center">

### 🐔 e-Poultry

</div>

Agri-tech e-marketplace for poultry farmers — mobile app, e-commerce website, admin dashboard, NestJS API, WhatsApp integration, and farmer group management.

<br/>

![React Native](https://img.shields.io/badge/-React_Native-0a0a1a?style=flat-square&logo=react&logoColor=06b6d4)
![NestJS](https://img.shields.io/badge/-NestJS-0a0a1a?style=flat-square&logo=nestjs&logoColor=ec4899)
![MongoDB](https://img.shields.io/badge/-MongoDB-0a0a1a?style=flat-square&logo=mongodb&logoColor=4ade80)
![Expo](https://img.shields.io/badge/-Expo-0a0a1a?style=flat-square&logo=expo&logoColor=white)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/e-poultry)
[![Live Site](https://img.shields.io/badge/🌐_e--poultry.com-06b6d4?style=flat-square&logoColor=white)](https://e-poultry.com)

</td>
<td width="50%" valign="top">

<div align="center">

### 🧹 JnB Cleaners

</div>

Multi-tenant cleaning services platform — customer PWA, field tech PWA, owner dashboard, and NestJS API in a Turborepo monorepo with Docker + Caddy deployment.

<br/>

![NestJS](https://img.shields.io/badge/-NestJS-0a0a1a?style=flat-square&logo=nestjs&logoColor=ec4899)
![Docker](https://img.shields.io/badge/-Docker-0a0a1a?style=flat-square&logo=docker&logoColor=06b6d4)
![Turborepo](https://img.shields.io/badge/-Turborepo-0a0a1a?style=flat-square&logo=turborepo&logoColor=ec4899)
![pnpm](https://img.shields.io/badge/-pnpm-0a0a1a?style=flat-square&logo=pnpm&logoColor=f59e0b)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/jnbcleaners)
[![Live Site](https://img.shields.io/badge/🌐_app.jnbcleaners.com-06b6d4?style=flat-square&logoColor=white)](https://app.jnbcleaners.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<div align="center">

### 🚚 Smart Drop / TrukFlow

</div>

Logistics and delivery platform — merchant mobile app for managing shipments, live tracking, delivery invoicing, and push notifications. Built with Expo.

<br/>

![Expo](https://img.shields.io/badge/-Expo-0a0a1a?style=flat-square&logo=expo&logoColor=white)
![React Native](https://img.shields.io/badge/-React_Native-0a0a1a?style=flat-square&logo=react&logoColor=06b6d4)
![Node.js](https://img.shields.io/badge/-Node.js-0a0a1a?style=flat-square&logo=node.js&logoColor=4ade80)
![TypeScript](https://img.shields.io/badge/-TypeScript-0a0a1a?style=flat-square&logo=typescript&logoColor=3b82f6)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/smart-drop)

</td>
<td width="50%" valign="top">

<div align="center">

### 🛡️ Soteria E-Commerce

</div>

Production e-commerce platform built for the Kenyan market — M-Pesa STK Push, Google OAuth, guest cart merge, admin dashboard. Deployed on Render + Vercel.

<br/>

![React](https://img.shields.io/badge/-React-0a0a1a?style=flat-square&logo=react&logoColor=06b6d4)
![Node.js](https://img.shields.io/badge/-Node.js-0a0a1a?style=flat-square&logo=node.js&logoColor=4ade80)
![MongoDB](https://img.shields.io/badge/-MongoDB-0a0a1a?style=flat-square&logo=mongodb&logoColor=4ade80)
![M-Pesa](https://img.shields.io/badge/-M--Pesa-0a0a1a?style=flat-square&logoColor=4ade80)

<br/>

[![View Repo](https://img.shields.io/badge/View_Repo-8b5cf6?style=flat-square&logo=github&logoColor=white)](https://github.com/clintmadeit/soteria)
[![Live Site](https://img.shields.io/badge/🌐_soteriaelectronics.co.ke-06b6d4?style=flat-square&logoColor=white)](https://soteriaelectronics.co.ke)

</td>
</tr>
</table>

</div>

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ec4899;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#8b5cf6;stop-opacity:0.5"/>
      <stop offset="60%" style="stop-color:#06b6d4;stop-opacity:0.7"/>
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q300,8 450,20 T900,20" stroke="url(#waveGrad4)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q300,8 450,20 T900,20;M0,20 Q300,32 450,20 T900,20;M0,20 Q300,8 450,20 T900,20"
      dur="6s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## 📊 GitHub Stats

<div align="center">

<!-- Stats via shields.io — always renders on GitHub -->
![Total Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fclintmadeit&query=%24.public_repos&label=Public+Repos&color=8b5cf6&style=for-the-badge&logo=github&logoColor=white&labelColor=0a0a1a)
![Followers](https://img.shields.io/github/followers/clintmadeit?label=Followers&style=for-the-badge&color=06b6d4&logo=github&logoColor=white&labelColor=0a0a1a&v=2)
![Profile Views](https://komarev.com/ghpvc/?username=clintmadeit&color=ec4899&style=for-the-badge&label=Profile+Views)

<br/>

<!-- Streak stats — demolab.com is on GitHub's allowlist -->
<a href="https://git.io/streak-stats">
<img src="https://streak-stats.demolab.com?user=clintmadeit&theme=tokyonight&hide_border=false&border=1E293B&stroke=1E293B&ring=8B5CF6&fire=EC4899&currStreakLabel=06B6D4&sideLabels=94A3B8&dates=475569&currStreakNum=FFFFFF&sideNums=FFFFFF&background=0A0A1A&card_width=700" alt="GitHub Streak Stats" width="700"/>
</a>

<br/><br/>

<!-- Skill icons grid — hosted on GitHub itself, always works -->
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,nodejs,nestjs,postgres,mongo,docker&theme=dark&perline=8" alt="Core Skills"/>
</a>

<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=redis,supabase,vercel,github,figma,tailwind,vite,expo&theme=dark&perline=8" alt="More Skills"/>
</a>

</div>

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:0"/>
      <stop offset="40%" style="stop-color:#3b82f6;stop-opacity:0.6"/>
      <stop offset="70%" style="stop-color:#8b5cf6;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q450,5 900,20" stroke="url(#waveGrad5)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q450,5 900,20;M0,20 Q450,35 900,20;M0,20 Q450,5 900,20"
      dur="5s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## 🎵 Beyond the Code

<div align="center">

<!-- Animated sound wave banner -->
<svg width="750" height="90" viewBox="0 0 750 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="soundBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a"/>
      <stop offset="100%" style="stop-color:#12122e"/>
    </linearGradient>
    <linearGradient id="barGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#ec4899"/>
      <stop offset="50%" style="stop-color:#8b5cf6"/>
      <stop offset="100%" style="stop-color:#06b6d4"/>
    </linearGradient>
  </defs>
  <rect width="750" height="90" fill="url(#soundBg)" rx="12"/>
  <!-- Animated equalizer bars — 24 bars -->
  <g transform="translate(185, 75)">
    <rect x="0"   width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.2;1,0.9;1,0.4;1,0.7;1,0.2" dur="1.1s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="10"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.7;1,0.3;1,1.0;1,0.5;1,0.7" dur="0.9s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="20"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.4;1,0.8;1,0.2;1,0.9;1,0.4" dur="1.3s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="30"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,1.0;1,0.4;1,0.8;1,0.3;1,1.0" dur="0.8s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="40"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.3;1,0.9;1,0.5;1,0.8;1,0.3" dur="1.4s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="50"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.8;1,0.2;1,0.7;1,0.4;1,0.8" dur="1.0s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="60"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.5;1,1.0;1,0.3;1,0.7;1,0.5" dur="1.2s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="70"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.9;1,0.5;1,0.8;1,0.2;1,0.9" dur="0.75s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="80"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.2;1,0.8;1,0.5;1,1.0;1,0.2" dur="1.5s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="90"  width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.6;1,0.3;1,0.9;1,0.4;1,0.6" dur="1.1s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="100" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.9;1,0.6;1,0.2;1,0.8;1,0.9" dur="0.85s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="110" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.3;1,1.0;1,0.6;1,0.3;1,0.3" dur="1.35s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="120" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,1.0;1,0.3;1,0.7;1,0.5;1,1.0" dur="0.95s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="130" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.5;1,0.9;1,0.4;1,0.8;1,0.5" dur="1.2s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="140" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.8;1,0.4;1,1.0;1,0.3;1,0.8" dur="1.0s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="150" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.2;1,0.7;1,0.5;1,0.9;1,0.2" dur="1.45s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="160" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.7;1,0.2;1,0.8;1,0.4;1,0.7" dur="0.88s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="170" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.4;1,0.9;1,0.3;1,0.7;1,0.4" dur="1.25s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="180" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,1.0;1,0.5;1,0.9;1,0.2;1,1.0" dur="0.78s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="190" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.3;1,0.8;1,0.4;1,1.0;1,0.3" dur="1.3s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="200" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.6;1,0.2;1,0.9;1,0.5;1,0.6" dur="1.05s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="210" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.9;1,0.7;1,0.3;1,0.8;1,0.9" dur="0.92s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="220" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.4;1,1.0;1,0.6;1,0.3;1,0.4" dur="1.18s" repeatCount="indefinite" additive="sum"/></rect>
    <rect x="230" width="6" fill="url(#barGrad)" rx="3" transform-origin="3 0" transform="scale(1,-1) translate(0,0)"><animateTransform attributeName="transform" type="scale" values="1,0.7;1,0.4;1,0.8;1,0.6;1,0.7" dur="1.0s" repeatCount="indefinite" additive="sum"/></rect>
  </g>
  <!-- Label -->
  <text x="375" y="22" text-anchor="middle" font-family="monospace" font-size="11" fill="#64748b" letter-spacing="4">LIVE SOUND · STUDIO · FOH ENGINEERING</text>
</svg>

</div>

<br/>

I'm also a **live sound engineer** and **UI/UX designer**. Mixing a concert and designing a product interface share the same DNA — you're shaping how people *feel* something, not just what they see or hear.

> *"The best systems — whether software or sound — are invisible. You only notice them when something goes wrong."*

<br/>

<!-- ═══════════════ ANIMATED WAVE DIVIDER ═══════════════ -->
<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad6" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#8b5cf6;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#ec4899;stop-opacity:0.5"/>
      <stop offset="60%" style="stop-color:#8b5cf6;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 Q225,32 450,20 Q675,8 900,20" stroke="url(#waveGrad6)" stroke-width="1.5" fill="none">
    <animate attributeName="d"
      values="M0,20 Q225,32 450,20 Q675,8 900,20;M0,20 Q225,8 450,20 Q675,32 900,20;M0,20 Q225,32 450,20 Q675,8 900,20"
      dur="5.5s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a0a1a?style=for-the-badge&logo=linkedin&logoColor=3b82f6&labelColor=0a0a1a)](https://www.linkedin.com/in/johnclinton-luseno/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0a0a1a?style=for-the-badge&logo=vercel&logoColor=8b5cf6&labelColor=0a0a1a)](https://clintmadeit.com)
[![Email](https://img.shields.io/badge/Email-0a0a1a?style=for-the-badge&logo=gmail&logoColor=ec4899&labelColor=0a0a1a)](mailto:clintonbrirdley@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0a0a1a?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0a1a)](https://github.com/clintmadeit)

</div>

<br/>

<!-- ═══════════════ ANIMATED FOOTER ═══════════════ -->
<div align="center">

<svg width="750" height="60" viewBox="0 0 750 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a"/>
      <stop offset="100%" style="stop-color:#12122e"/>
    </linearGradient>
    <linearGradient id="footerLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#06b6d4;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#8b5cf6;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#ec4899;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ec4899;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="750" height="60" fill="url(#footerBg)" rx="10"/>
  <rect x="100" y="8" width="550" height="1" fill="url(#footerLine)" opacity="0.6">
    <animate attributeName="width" values="550;500;550" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x" values="100;125;100" dur="4s" repeatCount="indefinite"/>
  </rect>
  <text x="375" y="35" text-anchor="middle" font-family="monospace" font-size="12" fill="#94a3b8">
    Built with ❤️ from Kenya · Powered by caffeine and 808s
  </text>
  <rect x="100" y="50" width="550" height="1" fill="url(#footerLine)" opacity="0.4">
    <animate attributeName="width" values="550;580;550" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x" values="100;85;100" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>
