<div align="center">

# Hi, I'm Bima Anzalta 👋

**Full-stack Developer** · Building web apps with modern Nuxt & Vue stack

[![Portfolio](https://img.shields.io/badge/Portfolio-anzalta.cloud-7c5cff?style=flat-square&logo=globe)](https://anzalta.cloud)
[![GitHub followers](https://img.shields.io/github/followers/bimaanzalta?style=flat-square&color=7c5cff)](https://github.com/bimaanzalta)

</div>

---

<details>
<summary><strong>Tech Stack</strong></summary>

| Category | Technologies |
|----------|-------------|
| **Framework** | Nuxt 4/3, Vue 3 (Composition API) |
| **Styling** | Tailwind CSS, Glassmorphism, Neon UI |
| **Database** | MySQL, Drizzle ORM, Prisma |
| **Auth** | JWT (jose), bcryptjs, HTTP-only cookies |
| **AI / Integrations** | OpenRouter (Claude / Gemini), WhatsApp Baileys, MyAnimeList API, Live2D Cubism |
| **Deployment** | PM2, Nginx, Node.js |

</details>

---

## Projects

### 🌐 [anzalta](https://github.com/bimaanzalta/anzalta)
Personal portfolio website with **anime/web3 aesthetic** — dark backgrounds, neon accents, glassmorphism UI, and a built-in blog & admin CMS.

`Nuxt 4` `Vue 3` `TailwindCSS` `Drizzle ORM` `SQLite` `@nuxt/content`

<details>
<summary>Read more</summary>

- Full portfolio showcase with project cards, tech stack, and live links
- Markdown-based blog with draft/publish toggle and syntax highlighting
- Hidden admin CMS for managing projects, blog posts, and contact messages
- Scroll-reveal animations via `v-motion`, page transitions, glassmorphism cards
- Design: `#0f0f14` background · `#7c5cff` primary · `#00d1ff` secondary · `#ff4fd8` highlight

</details>

---

### 🌿 [eco-ngo-bot](https://github.com/bimaanzalta/eco-ngo-bot)
WhatsApp AI donation manager for environmental NGOs. Donors simply chat on WhatsApp — the AI bot guides the entire donation process automatically with receipt verification and admin dashboard.

`Nuxt 3` `WhatsApp Baileys` `OpenRouter AI` `MySQL` `Prisma` `RBAC`

<details>
<summary>Read more</summary>

- Multi-account WhatsApp bot management — each bot assignable to a specific campaign
- AI-powered conversation via OpenRouter (Claude / Gemini / Llama) — guides donors step by step
- Donors send transfer receipt photo → stored to database → admin verify/reject via dashboard
- Automatic WhatsApp notification to donor after verification
- Three-role RBAC: Super Admin, Admin, Verifikator
- Multi-campaign support with real-time statistics

</details>

---

### 💅 [aura-beauty](https://github.com/bimaanzalta/aura-beauty)
Full-stack beauty management system for salons, nail/lash studios, and spas — POS, booking calendar, inventory, staff management, and sales reports.

`Nuxt 3` `Vue 3` `Pinia` `MySQL` `TailwindCSS` `Xendit Payment`

<details>
<summary>Read more</summary>

- **POS / Kasir** — service & product transactions, discounts, cash/transfer/QRIS payment
- **Booking** — daily calendar, anti double-booking, appointment status
- **Inventory** — stock auto-decremented on transaction, physical stock opname
- **Staff** — CRUD with role management (owner / admin / staff)
- **Reports** — daily summary, top services/products, date filter
- Three roles: Owner (full access), Admin, Staff

</details>

---

### 🎮 [levelup](https://github.com/bimaanzalta/levelup)
Learning Management System for gaming & esports with a retrofuturism dark neon aesthetic — courses, video lessons, quiz, progress tracking, and certificate generation.

`Nuxt 4` `Prisma` `MySQL` `TailwindCSS` `JWT`

<details>
<summary>Read more</summary>

- Course browsing with category filter and search
- Video player with sidebar navigation and lesson completion marking
- Progress tracking — % completion per course, continue learning
- Multiple choice quiz with score and pass/fail result
- Certificate generation after course completion + quiz passed
- Admin CMS — CRUD for courses, modules, lessons, quizzes, categories, instructors
- Design: retrofuturism dark neon (`#7C3AED` purple · `#06B6D4` cyan · `#0B0F1A` background)

</details>

---

### 🎌 [my-anime-media](https://github.com/bimaanzalta/my-anime-media)
Indonesian anime & manga media platform — articles, reviews, forum discussions, and MyAnimeList API integration with rich text editor and light/dark mode.

`Nuxt 4` `Drizzle ORM` `MySQL` `TipTap` `MAL OAuth 2.0` `VueUse`

<details>
<summary>Read more</summary>

- Articles & reviews with rich text editor (TipTap v3), categories, and anime tagging
- Forum — threaded discussions with nested comments and category support
- Anime search and detail via MyAnimeList API (OAuth 2.0 PKCE)
- Role system: user / moderator / admin with admin panel
- Persistent light/dark mode toggle via VueUse + localStorage
- Responsive layout with mobile hamburger nav

</details>

---

### 🎭 [proseka-ai](https://github.com/bimaanzalta/proseka-ai)
Web-based Live2D viewer for Project SEKAI characters with real-time Japanese lip sync, AI chat powered by OpenRouter, and VITS voice synthesis via ProsekaTTS.

`Nuxt 3` `PixiJS` `Live2D Cubism 4` `OpenRouter AI` `ProsekaTTS` `kuromoji`

<details>
<summary>Read more</summary>

- Live2D Cubism 4 model rendering via `pixi-live2d-display`
- AI chat with character-specific personalities (Google Gemini Flash via OpenRouter)
- High-quality VITS voice synthesis with 20 Project SEKAI character voices (ProsekaTTS)
- Frame-accurate lip sync — phoneme timeline built from kuromoji, mouth parameters driven every frame
- Web Speech API fallback with `onboundary` recalibration for offline use
- Idle animations, expression buttons (smile, sad, angry, surprise, shy), adjustable speech rate
- Admin panel — manage characters, models, songs, and view chat history

</details>

---

<div align="center">

*Building expressive, motion-first web experiences*

</div>
