# 🌐 Aditya Kumar Gupta — Personal Portfolio

> **Frontend Developer & B.Tech CSE Student**
> Live Portfolio: [adkumar2651.github.io/Portfolio](https://adkumar2651.github.io/Portfolio/)

---

## 👨‍💻 About

Hi, I'm **Aditya Kumar Gupta** — a passionate Frontend Developer currently pursuing **B.Tech in Computer Science Engineering**. I build modern, responsive websites using HTML, CSS, JavaScript, and AI-powered tools, with a strong focus on clean UI/UX design.

---

## ✨ Features

- ⚡ **Typing animation** in hero section — rotates through roles
- 🎨 **Dark blueish theme** with cyan/purple gradient accents
- 🌀 **Animated spinning photo ring** in hero
- 📜 **Scroll reveal animations** on all sections
- 📊 **Animated skill progress bars**
- 📱 **Fully responsive** — mobile, tablet, desktop
- 🍔 **Hamburger menu** for mobile
- 📬 **Demo contact form** with success message simulation
- 🐙 **GitHub & Vercel** integration section

---

## 🗂️ Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, animated role, photo, CTA buttons, stats |
| **About** | Bio, future goal, skill cards |
| **Skills** | 6 skills with animated progress bars |
| **Projects** | 5 project cards with live & GitHub links |
| **GitHub** | Profile link, repos, Vercel deployments |
| **Contact** | Info cards + demo contact form |
| **Footer** | Name, socials, copyright |

---

## 🚀 Projects

| Project | Description | Live |
|---------|-------------|------|
| **Wander** | AI-powered travel planning website | [🔗](https://adkumar2651.github.io/wander/) |
| **JS Calculator** | Dark-themed DARKNEO calculator | [🔗](https://adkumar2651.github.io/JS-CALCULATOR/) |
| **Neon Highway** | Browser racing game on Vercel | [🔗](https://neon-highway-x.vercel.app/) |
| **Aditya Tech Info** | Tech gadgets & laptops info site | [🔗](https://adkumar2651.github.io/aditya-tech-info/) |
| **Dharohar** | Travel destination explorer on Framer | [🔗](https://dharohar.framer.website/) |

---

## 🛠️ Tech Stack

```
HTML5        CSS3         JavaScript
Tailwind CSS  AI Tools     Responsive Design
```

**Built with:**
- Pure HTML, CSS, JavaScript — no frameworks
- [Google Fonts](https://fonts.google.com/) — Syne + DM Sans
- [Font Awesome 6](https://fontawesome.com/) — icons
- CSS custom properties, animations, IntersectionObserver API

---

## 📁 File Structure

```
portfolio/
│
├── index.html        ← Complete single-file portfolio
└── README.md         ← This file
```

---

## ⚙️ Setup & Usage

### Run Locally

```bash
# Just open the file in your browser
open index.html

# Or use Live Server in VS Code
```

### Deploy on GitHub Pages

```bash
# 1. Create a repo named: Portfolio
# 2. Upload index.html
# 3. Go to Settings → Pages → Deploy from main branch
# 4. Your site will be live at:
#    https://<your-username>.github.io/Portfolio/
```

---

## 📬 Contact Form — EmailJS Setup

The contact form is currently in **Demo Mode** (simulates success, no email sent).

To make it **fully functional**:

1. Go to [emailjs.com](https://emailjs.com) → create a free account
2. Add Gmail as an Email Service → copy **SERVICE\_ID**
3. Create an Email Template with these variables:
   ```
   {{from_name}}   ← sender's name
   {{from_email}}  ← sender's email
   {{message}}     ← message content
   ```
4. Go to Account → API Keys → copy **PUBLIC\_KEY**
5. Copy your **TEMPLATE\_ID**
6. In `index.html`, find the JS section and replace:

```js
emailjs.init('YOUR_PUBLIC_KEY');
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', params)
```

---

## 🔗 Links

| Platform | Link |
|----------|------|
| 🌐 Portfolio | [adkumar2651.github.io/Portfolio](https://adkumar2651.github.io/Portfolio/) |
| 🐙 GitHub | [github.com/adkumar2651](https://github.com/adkumar2651) |
| 🚀 Vercel | [vercel.com/adkumar2651s-projects](https://vercel.com/adkumar2651s-projects) |
| 💼 LinkedIn | [linkedin.com/in/aditya-kumar-708446395](https://www.linkedin.com/in/aditya-kumar-708446395) |
| 📸 Instagram | [@adkumar2651](https://www.instagram.com/adkumar2651) |
| 📧 Email | tplinkgpay556@gmail.com |
| 📞 Phone | +91 82879 07596 |

---

## 📄 License

This project is open source. Feel free to use it as inspiration for your own portfolio.

---

<div align="center">
  <strong>© 2026 Aditya Kumar Gupta</strong><br/>
  Built with ❤️ & passion
</div>
