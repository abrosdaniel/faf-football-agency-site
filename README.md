<p align="center">
<a href ="https://f-a-f.ru" target="_blank" title="FAF">
<img src=".github/assets/logo.png" width="150px" alt="FAF"/>
</a>
</p>
<div align="center">

[![Site/Version](https://img.shields.io/badge/f--a--f.ru-v_1.0-2A8F3B)](https://f-a-f.ru)
[![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js)](https://nextjs.org)
[![Directus](https://img.shields.io/badge/Directus-263238?logo=directus)](https://directus.io)
[![N8N](https://img.shields.io/badge/N8N-EA4B71?logo=n8n&logoColor=white)](https://n8n.io)

</div>

## Introduction

FAF Football Agency stands as an innovative, next-generation website designed for the dynamic football industry landscape. This strategic digital solution creates a vital connection between emerging football talent and premier professional pathways. Engineered with advanced web technologies, the platform provides flawless user interactions across every device while upholding exceptional performance benchmarks.

Developed on Next.js foundation with headless CMS capabilities, the website showcases cutting-edge web development methodologies within the sports domain, harmoniously blending sophisticated aesthetics with robust technical architecture.

<img src=".github/assets/home_page.png" width="100%">

# Table of Contents

1. [Features](#features)
2. [Stack](#stack)
3. [Quick Start](#quick-start)
4. [Credits](#credits)

## Features

- ⚽ **Player Database** - Complete football talent profiles and statistics
- 📈 **Industry News** - Current football market updates and agency announcements
- 🏢 **Agency Directory** - Full-scale sports agency information system
- ✍️ **Talent Application** - Digital registration platform for football prospects
- 📲 **Mobile-First Design** - Seamlessly adapted for every screen size
- 🚀 **High-Speed Performance** - Lightning-fast experience powered by Next.js
- 🎯 **Search Engine Ready** - Built for maximum online visibility
- 📊 **Analytics** - Integrated Yandex Metrics for insights

## Stack

- **Frontend:**
  ![Next.js](https://img.shields.io/badge/Next.js-^15.5.9-white?logo=next.js)
  ![TanStack Query](https://img.shields.io/badge/TanStack_Query-^5.83.0-FF4154?logo=tanstack)
  ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-^7.62.0-EC5990?logo=reacthookform&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-^5-3178C6?logo=typescript&logoColor=white)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-^4-06B6D4?logo=tailwindcss&logoColor=white)
  ![PostCSS](https://img.shields.io/badge/PostCSS-^4-DD3A0A?logo=postcss)
  ![Radix UI](https://img.shields.io/badge/Radix_UI-161618?logo=radixui)
  ![shadcn/ui](https://img.shields.io/badge/shadcn/ui-black?logo=shadcnui)
  ![GSAP](https://img.shields.io/badge/GSAP-^3.13.0-0AE448?logo=gsap&logoColor=white)
  ![Lucide](https://img.shields.io/badge/Lucide-^0.525.0-F56565?logo=lucide&logoColor=white)
  ![Yandex Smart Captcha](https://img.shields.io/badge/Yandex_Smart_Captcha-F90000)
  ![Yandex Metrics](https://img.shields.io/badge/Yandex_Metrics-F90000)

- **Backend:**
  ![Directus](https://img.shields.io/badge/Directus-^11.3.2-263238?logo=directus)
  ![N8N](https://img.shields.io/badge/N8N-^1.71.2-EA4B71?logo=n8n&logoColor=white)

- **Tools & Services:**
  ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
  ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
  ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint)
  ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?logo=prettier&logoColor=black)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## Quick Start

❗ **Prerequisites:**

- ✅ Node.js 18+ installed
- ✅ Directus with tables configured
- ✅ N8N with nodes set up

Clone the repository:

```bash
git clone https://github.com/abrosdaniel/faf-football-agency-site.git
cp .env.example .env
```

Install dependencies:

```bash
npm install
```

Create `.env` in the project root:

```env
NEXT_PUBLIC_FRONT_URL=your_project_url
NEXT_PUBLIC_DIRECTUS_URL=your_directus_url
NEXT_PUBLIC_API_URL=your_n8n_url
NEXT_PUBLIC_YANDEX_METRIKA_ID=your_yandex_metrika_id
NEXT_PUBLIC_YANDEX_CAPTCHA_ID=your_yandex_captcha_id
```

Standard Next.js commands:

```bash
npm run dev
npm run build
npm run start
```

## Credits

- **Developer:** [Daniel Abros](https://abros.dev)
- **Design:** [Daria Afanaseva](https://t.me/a_dari)
- **Client:** [FAF Football Agency](https://f-a-f.ru)
