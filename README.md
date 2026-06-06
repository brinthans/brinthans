
/
Claude finished the response
help me redesign github profile readme

2:50 AM

Reading the frontend design skill
Reading the frontend design skill
Let me check your existing CV data and your current GitHub profile to understand your style before designing.


Relevant chats
Relevant chats
Good — I have full context on your previous README. Now let me design a significantly upgraded version that showcases your projects (Rememberly & Zee Books) from the FE CV and gives it a much more distinctive look.

Now let me look at your FE CV projects closely and design the README:


Created a file, read a file
Created a file, read a file
Here's your redesigned README. The big changes from the previous version:

What's new:

Projects section — Rememberly and Zee Books are now front and center, with the actual technical details from your FE CV (timezone math, multi-tenant routing, AI extraction flow, etc.). This is the biggest upgrade — recruiters and devs who land on your profile now see real work, not just a badge wall.
Better About Me — includes direct references to the projects so it ties together
Expanded tech stack — added Expo, React Query, PostgreSQL as separate badges to reflect your actual stack
Cleaner stat layout — streak + top langs side by side, general stats below
What stayed the same (intentionally):

No career history or education (per your preference)
Badge-driven tech stack
GitHub stats cards
One thing to double-check: make sure your GitHub username is brinthan in the stats card URLs — if it's different, just update it throughout. Want to tweak anything?


Readme
Document · MD 


More simple and professional



Claude is AI and can make mistakes. Please double-check responses.


raw
Readme · MD
<!-- Header -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=Hey%2C+I'm+Brinthan+%F0%9F%91%8B;Senior+Frontend+Engineer;React+%26+React+Native+Dev;Building+things+people+use" alt="Typing SVG" />
</div>
<div align="center">
  <a href="https://linkedin.com/in/brinthan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://brinthan.dev"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="mailto:brinthan7@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=brinthan&label=Profile+views&color=58A6FF&style=for-the-badge" />
</div>
<br />
---
 
## 🧑‍💻 About Me
 
- 🏢 **Senior Software Engineer** at [Virtusa](https://www.virtusa.com) — building a React Native telco app used by millions
- 🌍 Based in **Colombo, Sri Lanka**
- ⚡ 6+ years across **web & mobile** — React, React Native, TypeScript
- 🛠️ Love clean architecture, good performance, and making teams ship better
- 🚀 Currently building [Rememberly](https://github.com/brinthan/rememberly) & [Zee Books](https://github.com/brinthan/zee-books) on the side
- 💬 Ask me about **React Native**, **Supabase**, or **frontend performance**
---
 
## 🚀 Personal Projects
 
### 📅 Rememberly — Cross-Platform Birthday Reminder App
> React Native · Expo SDK 54 · TypeScript · Expo Router · Zustand · Reanimated 4 · EAS Build
 
A birthday reminder app for iOS, Android, and web — built with a single codebase via Expo.
 
- 🌐 **Timezone-aware notifications** — reminders fire at midnight in the *contact's* timezone using `Intl.DateTimeFormat` offset math
- 🎨 **Theming system** — light/dark modes + 4 colour palettes via a single `useTheme()` hook; Zustand persistence gate prevents flash on startup
- 🔗 **Deep-linked notifications** — tapping a reminder routes directly to the right birthday screen via typed Expo Router links
- ⚡ Built on **React 19**, React Compiler, New Architecture, and Reanimated 4 worklets for confetti & haptics
---
 
### 🗂️ Zee Books — Multi-Tenant Document & Invoicing SaaS
> React 18 · TypeScript · Vite · Zustand · Tailwind CSS v4 · shadcn/ui · Supabase · pdf-lib · Netlify
 
A SaaS tool for businesses to manage documents and invoices with AI-powered data extraction.
 
- 🏢 **Multi-tenant routing** — each business gets its own `/:slug/*` space with a full permissions layer (`canAdd/canView/canEdit/isOwner`)
- 🤖 **AI extraction flow** — upload receipt → Supabase Storage → Postgres trigger → Edge Function calls Claude Vision → result reflected live
- 🎨 **Per-tenant theming** — 6 colour themes per client via CSS variables, no build required
- 📄 **Client-side PDF editor** — split & merge invoices with no server round-trips; invoice generator with live preview, line items, discounts, and save-as-template
---
 
## 🛠️ Tech Stack
 
### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
 
### Frontend & Mobile
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
 
### State & APIs
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
 
### Cloud & Tools
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
 
### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
 
---
 
## 📊 GitHub Stats
 
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=brinthan&theme=github-dark-blue&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=brinthan&layout=compact&theme=github_dark&hide_border=true&langs_count=6" height="165" />
</div>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=brinthan&show_icons=true&theme=github_dark&hide_border=true&count_private=true&hide_rank=false" height="165" />
</div>
---
 
<div align="center">
  <i>"The best code is the code your teammates can maintain."</i>
</div>
