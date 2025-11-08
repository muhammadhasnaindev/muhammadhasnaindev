Awesome—here’s a **professional, copy-paste-ready GitHub Profile README** that:

* Highlights **MERN + WordPress/PHP**
* Shows your **AWS certification badge** (Credly image)
* States **2+ years experience**
* Features your three flagship apps with **live links + screenshot previews**
* Uses your **new contact email**: `hasnainsumra00@gmail.com`
* Adds **LinkedIn** and **GitHub stats**

> Note: GitHub READMEs don’t allow `<script>` tags, so I used the Credly **badge image** (works perfectly).

---

````markdown
<h1 align="center">👋 Hi, I'm Muhammad Hasnain</h1>

<p align="center">
  Full Stack Developer — <b>MERN</b> • <b>WordPress/PHP</b> • <b>AWS (Cloud Practitioner)</b><br/>
  <b>2+ years</b> building production web apps, real-time systems & e-commerce.
</p>

<p align="center">
  <a href="https://www.credly.com/badges/c869ce4c-acca-447b-a738-8cfef3f776b5" title="AWS Certified Cloud Practitioner">
    <img src="https://images.credly.com/size/340x340/images/0c05648b-2247-4e6b-8cfa-be5bfcce7db0/image.png" width="96" alt="AWS Badge"/>
  </a>
</p>

<p align="center">
  <a href="https://clicon.demowebsite.uno">Clicon (E-Commerce)</a> •
  <a href="https://chat.demowebsite.uno">Chat App</a> •
  <a href="https://go.demowebsite.uno">Shortly (URL Shortener)</a>
</p>

---

## 🧭 About
- I design, build and deploy **MERN** apps with **secure APIs**, **real-time features**, and **clean UI**.
- Comfortable with **AWS EC2 + Nginx + PM2 + MongoDB**, custom domains, and **SSL**.
- Also deliver **WordPress / PHP / Laravel** solutions when a CMS is the right fit.

**Contact:** `hasnainsumra00@gmail.com`  
**LinkedIn:** https://www.linkedin.com/in/muhammadhasnaindev

---

## 🛠️ Tech Stack

**Frontend:** React 18, Vite, Redux Toolkit, React Router, Tailwind CSS, MUI, i18next, Zustand  
**Backend:** Node.js, Express, MongoDB (Mongoose), JWT, Multer, Nodemailer, Socket.IO  
**DevOps/Cloud:** AWS (EC2, S3, RDS, IAM), Nginx, PM2, Docker, GitHub Actions  
**Other:** WordPress (theme/plugin customization), PHP, Laravel, REST APIs, Figma, SEO

---

## ⭐ Featured Projects

### 🛒 Clicon — Full-Stack E-Commerce (MERN)
Storefront + product catalog, cart & checkout, orders, reviews, blog, dashboard, and **Admin with Roles/Permissions**.

**Tech:** React 18, Vite, Redux Toolkit, Tailwind, MUI, React Query, i18next • Node.js, Express, MongoDB (Mongoose), JWT (Http-Only), Nodemailer  
**Live:** https://clicon.demowebsite.uno • **Code:** Private

<details>
<summary><b>Structure, ENV & Local Run</b></summary>

```text
clicon/
├─ client/   # React + Vite
│  ├─ src/
│  ├─ public/
│  └─ .env.example
└─ server/   # Express + MongoDB
   ├─ routes/
   ├─ models/
   ├─ utils/
   └─ .env.example
````

**Backend**

```bash
cd server
cp .env.example .env
npm install
npm run dev
# http://localhost:4000
```

**Frontend**

```bash
cd client
cp .env.example .env
npm install
npm run dev
# http://localhost:5173
```

**client/.env**

```ini
VITE_API_URL=/api
VITE_BACKEND_ORIGIN=http://localhost:4000
```

**server/.env**

```ini
PORT=4000
MONGO_URI=mongodb://localhost:27017/clicon
JWT_SECRET=your-strong-secret
CLIENT_ORIGIN=http://localhost:5173
FRONTEND_ORIGIN=http://localhost:5173
DEMO_MODE=true
```

</details>

**Screenshots (Live)**

> These load from the production app's `/screenshots` (Vite public assets).
> If any image is missing, add it under `client/public/screenshots/` in the app.

| Page        | Preview                                                                        |
| ----------- | ------------------------------------------------------------------------------ |
| Home        | ![](https://clicon.demowebsite.uno/screenshots/01_Homepage.png)                |
| Shop        | ![](https://clicon.demowebsite.uno/screenshots/07_Shop-Page.png)               |
| Product     | ![](https://clicon.demowebsite.uno/screenshots/08_Product-Detail.png)          |
| Track Order | ![](https://clicon.demowebsite.uno/screenshots/09_Track-Order.png)             |
| Wishlist    | ![](https://clicon.demowebsite.uno/screenshots/12_Wishlist.png)                |
| Checkout    | ![](https://clicon.demowebsite.uno/screenshots/14_Checkout.png)                |
| FAQs        | ![](https://clicon.demowebsite.uno/screenshots/21_FAQs.png)                    |
| About       | ![](https://clicon.demowebsite.uno/screenshots/23_About-Us.png)                |
| Blog        | ![](https://clicon.demowebsite.uno/screenshots/25_Blog-List.png)               |
| Dashboard   | ![](https://clicon.demowebsite.uno/screenshots/27_Dasboard.png)                |
| Orders      | ![](https://clicon.demowebsite.uno/screenshots/28_Dashboard_Order-History.png) |

---

### 🔗 Shortly — URL Shortener & Analytics (MERN)

Create branded short links, track clicks, **referrers/UTM**, simple dashboards.

**Tech:** React + Vite • Express • MongoDB • Charts • Auth
**Live:** [https://go.demowebsite.uno](https://go.demowebsite.uno) • **Code:** Private

<details>
<summary><b>Structure, ENV & Local Run</b></summary>

```text
shortly/
├─ client/
│  ├─ public/
│  │  └─ screenshots/
│  └─ src/
└─ server/
   └─ src/
```

**Backend**

```bash
cd server
cp .env.example .env
npm install
npm run dev
# http://localhost:5000
```

**Frontend**

```bash
cd client
cp .env.example .env
npm install
npm run dev
# http://localhost:5173
```

**client/.env**

```ini
VITE_API_BASE=http://localhost:5000
```

</details>

**Screenshots (Live)**

| Page              | Preview                                                                    |
| ----------------- | -------------------------------------------------------------------------- |
| Dashboard (Light) | ![](https://go.demowebsite.uno/screenshots/Analytics-Screenshot.png)       |
| Create Link       | ![](https://go.demowebsite.uno/screenshots/create-link-Screenshot.png)     |
| Create Account    | ![](https://go.demowebsite.uno/screenshots/Create-account-Screenshot.png)  |
| Edit Link         | ![](https://go.demowebsite.uno/screenshots/editlink-Screenshot.png)        |
| Home (Dark)       | ![](https://go.demowebsite.uno/screenshots/home-blackscreenScreenshot.png) |
| Home (Light)      | ![](https://go.demowebsite.uno/screenshots/home-Screenshot.png)            |
| Login             | ![](https://go.demowebsite.uno/screenshots/Login-Screenshot.png)           |
| Recent Clicks     | ![](https://go.demowebsite.uno/screenshots/Recent-Clicks-Screenshot.png)   |

---

### 💬 WhatsApp-style Chat — Real-Time (MERN + Socket.IO + WebRTC)

Email signup & verification, 1-1 and **Groups** with presence, media/file share (large), emoji/reply/copy, **voice notes**, and **audio/video calls**.

**Tech:** React 18, Vite, MUI, Tailwind, Zustand, Socket.IO client • Node.js, Express, Mongoose, JWT, Multer, Nodemailer, Socket.IO
**Live:** [https://chat.demowebsite.uno](https://chat.demowebsite.uno) • **Code:** Private

<details>
<summary><b>Structure, ENV & Local Run</b></summary>

```text
chat/
├─ client/
│  ├─ public/
│  │  └─ screenshots/
│  └─ src/
└─ server/
   └─ src/
```

**Server**

```bash
cd server
cp .env.example .env
npm install
npm run dev
# http://localhost:5000 (or your PORT)
```

**server/.env (example)**

```ini
PORT=5000
MONGO_URI=mongodb://localhost:27017/whatsapp
JWT_SECRET=replace-with-strong-secret
CORS_ORIGIN=http://localhost:5173
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your@gmail.com
SMTP_PASS=app-password
FROM_EMAIL="Chat App <your@gmail.com>"
```

**Client**

```bash
cd client
cp .env.example .env
npm install
npm run dev
# http://localhost:5173
```

**client/.env**

```ini
VITE_API_URL=http://localhost:5000
```

</details>

**Screenshots (Live)**

| Page / State      | Preview                                                                      |
| ----------------- | ---------------------------------------------------------------------------- |
| Home              | ![](https://chat.demowebsite.uno/screenshots/home-Screenshot.png)            |
| Chat              | ![](https://chat.demowebsite.uno/screenshots/chat-Screenshot.png)            |
| Email Verify      | ![](https://chat.demowebsite.uno/screenshots/email-verify-Screenshot.png)    |
| Group Create      | ![](https://chat.demowebsite.uno/screenshots/group-create-Screenshot.png)    |
| Group (list/room) | ![](https://chat.demowebsite.uno/screenshots/group-Screenshot.png)           |
| Profile Settings  | ![](https://chat.demowebsite.uno/screenshots/profile-setting-Screenshot.png) |
| Sign In           | ![](https://chat.demowebsite.uno/screenshots/signin-Screenshot.png)          |
| Sign Up           | ![](https://chat.demowebsite.uno/screenshots/signup-Screenshot.png)          |
| Call              | ![](https://chat.demowebsite.uno/screenshots/call-Screenshot-2.png)          |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=muhammadhasnaindev&show_icons=true&theme=react" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadhasnaindev&layout=compact&theme=react" height="160" />
</p>
```

---

