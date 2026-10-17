<div align="center">

<img src="assets/hero.svg" width="100%" alt="Aditya Sarse — Full Stack Developer × Designer at heart" />

<br/>

<a href="https://www.linkedin.com/in/adityasarse"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:adityasarse362@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Pune-India-0f172a?style=for-the-badge&logo=googlemaps&logoColor=white" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

<div align="center">
<img src="assets/terminal.svg" width="100%" alt="Terminal intro" />
</div>

<img src="assets/divider.svg" width="100%" alt="" />

## 🚀 Selected Work

<img src="assets/projects.svg" width="100%" alt="StoreRatings, APIShield, Élanor" />

### 01 · StoreRatings

<img src="assets/storeratings.jpg" width="100%" alt="StoreRatings landing page" />

**One platform, three roles, scoped permissions.** Shoppers, store owners and admins each get their own dashboard, and each can only do what their role allows.

[![Code](https://img.shields.io/badge/View%20Code-181717?style=for-the-badge&logo=github)](https://github.com/AdityaSarse)  [![Live](https://img.shields.io/badge/Live%20Demo-ec4899?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/AdityaSarse)

<details>
<summary><b>🔍 How it works</b></summary>

<br/>

```mermaid
flowchart LR
    U([👤 Normal User]) -->|rates stores| API
    O([🏪 Store Owner]) -->|manages OWN store only| API
    A([🛡️ Admin]) -->|users · stores · ratings| API
    API[Express + JWT<br/>service layer] --> DB[(PostgreSQL<br/>via Prisma)]
```

- 🔐 JWT auth, protected routes and ownership-based authorization
- ⭐ Duplicate-rating prevention
- 🧱 Service-layer backend: auth · store · rating · user
- 🛠️ Admin console for platform-wide management
- ☁️ Deployed end to end on Vercel, Render and Neon

`React` `Vite` `Node.js` `Express` `PostgreSQL` `Prisma` `JWT`

</details>

<br/>

### 02 · APIShield

<img src="assets/apishield.jpg" width="100%" alt="APIShield banner" />

**A gateway that verifies, routes and throttles every request.** A production-style API gateway and security layer in front of microservices, with a live dashboard for traffic, logs and health.

[![Code](https://img.shields.io/badge/View%20Code-181717?style=for-the-badge&logo=github)](https://github.com/AdityaSarse)

<details>
<summary><b>🔍 How it works</b></summary>

<br/>

```mermaid
flowchart LR
    C([Client]) --> G{{🛡️ APIShield Gateway}}
    G -->|verify JWT| G
    G <-->|sliding-window<br/>rate limit| R[(Redis)]
    G -->|routed| S1[Service A]
    G -->|routed| S2[Service B]
    G -->|logs · policies| P[(PostgreSQL)]
    P --> D[📊 React Dashboard]
```

- 🚦 Redis sliding-window rate limiting per client / API key
- 🔑 Centralized JWT auth and request routing
- 📈 Live traffic, request logs and health metrics in a React dashboard
- 🐳 One-command Docker Compose deployment
- 🎨 Designed first, with its own `DESIGN.md` and indigo Figma system

`Node.js` `Express` `Redis` `PostgreSQL` `Prisma` `React` `TanStack Query` `Tailwind` `Docker`

</details>

<br/>

### 03 · Élanor

<img src="assets/elanor.jpg" width="100%" alt="Élanor storefront" />

**Luxury fashion e-commerce with real payments.** A MERN storefront that feels premium, with an admin side that makes running the shop easy.

[![Code](https://img.shields.io/badge/View%20Code-181717?style=for-the-badge&logo=github)](https://github.com/AdityaSarse)  [![Live](https://img.shields.io/badge/Live%20Demo-0f2744?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/AdityaSarse)

<details>
<summary><b>🔍 What's inside</b></summary>

<br/>

- 🛍️ Search, filtering, cart and wishlist
- 💳 Razorpay payments and order processing
- 🖼️ ImageKit image delivery and optimization
- 🧑‍💼 Admin dashboard for products, categories, orders and users
- 🔐 JWT auth with role-based access for customers and admins

`MongoDB` `Express` `React` `Node.js` `JWT` `Razorpay` `ImageKit`

</details>

<img src="assets/divider.svg" width="100%" alt="" />

## 🧰 Toolbox

<img src="assets/skills.svg" width="100%" alt="Skills marquee" />

<img src="assets/divider.svg" width="100%" alt="" />

<img src="assets/quote.svg" width="100%" alt="The best interfaces are the ones you don't notice — because everything just works. — my design mantra" />

<img src="assets/divider.svg" width="100%" alt="" />

## 🧭 How I Work

```mermaid
flowchart LR
    A[🔍 Understand<br/>the users] --> B[✏️ Wireframe &<br/>prototype in Figma]
    B --> C[🧱 Build API &<br/>data model]
    C --> D[⚛️ Craft the<br/>interface]
    D --> E[🔒 Secure<br/>& test]
    E --> F[🚢 Dockerize<br/>& deploy]
    F -.->|feedback| A
```

<div align="center">

| 🎨 Design-led | 🔐 Security-minded | 🚢 Ship-ready |
|:--:|:--:|:--:|
| Flows and a design system come before code | Auth, ownership checks and rate limiting from day one | Real deployments and containers, not just localhost |

</div>

<img src="assets/now.svg" width="100%" alt="Now playing: building, exploring, levelling up" />

<br/>

<div align="center">

## 💬 Let's Talk

**Hiring for Full Stack or Java Backend? Or have an idea worth building?**

<a href="mailto:adityasarse362@gmail.com"><img src="https://img.shields.io/badge/adityasarse362@gmail.com-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/adityasarse"><img src="https://img.shields.io/badge/linkedin.com/in/adityasarse-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=AdityaSarse&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaSarse&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa" height="160" />

</div>
