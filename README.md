# 🌐 Saptak Chaki — Personal Portfolio Website

Welcome to my **personal developer portfolio website**, built to showcase my projects, skills, and experience as a passionate Computer Science undergrad and aspiring data scientist.

![image](https://github.com/user-attachments/assets/f1ceffca-c5c2-4bc3-93e4-7b9d6e75ae38)


---

## 🚀 Live Preview

🌍 https://portfolio-saptak.vercel.app/(#)
(You can deploy this on GitHub Pages, Vercel, or Netlify)

---

## 🛠️ Technologies Used

| Technology       | Description                              |
|------------------|------------------------------------------|
| **HTML5**        | Core structure of the website            |
| **CSS3**         | Base styling                             |
| **Tailwind CSS** | Utility-first responsive styling         |
| **JavaScript**   | DOM manipulation and interactivity       |
| **Typed.js**     | Typewriter animation on hero section     |
| **EmailJS**      | Send messages directly from contact form |

---

## ✨ Features

- ⚡ Animated hero section using **Typed.js**
- 🌗 Light/Dark mode toggle (optional)
- 💼 Project showcase with hover interactions
- 🧠 Skills section with icon-based layout
- 📫 Contact form powered by **EmailJS** (no backend required!)
- 🎨 Fully responsive layout for mobile, tablet, and desktop
- 🌈 TailwindCSS used for sleek UI and theming

---

## 📂 Folder Structure

```
/portfolio/
├── index.html
├── style.css (optional if you're combining)
├── /images/ (e.g. screenshot.png, favicon)
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Saptakcodes/portfolio.git
cd portfolio
```

### 2. Open `index.html`

You can directly open the file in your browser:

```bash
start index.html
```
Or with VS Code Live Server:
```bash
code .
```

---

## 📩 EmailJS Integration Guide

Already set up with:
- **Service ID**: `service_4x6wm0u`
- **Template ID**: `template_5xyjcc6`
- **Public Key**: `dYKan-1wxeEgYd_ua`

To use your own:
1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Add your Gmail or email service under "Email Services"
3. Create an email template with fields: `{{name}}`, `{{email}}`, `{{title}}`, `{{message}}`
4. Replace the service/template/public key in the JavaScript block in `index.html`

```js
emailjs.init("YOUR_PUBLIC_KEY");

emailjs.sendForm("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", this)
```

---

![image](https://github.com/user-attachments/assets/08a75f41-9632-4c0b-b410-4c97c395025b)

---

## 🧑‍💻 Author

**Saptak Chaki**  
- 🌐 [GitHub](https://github.com/Saptakcodes)  
- 💼 [LinkedIn](https://www.linkedin.com/in/saptak-chaki-31a83228b/)  
- 🐦 [Twitter](https://x.com/ChakiSapta68840)

---

## 🪄 Customization Tips

- ✏️ Modify `strings[]` in `Typed.js` to personalize your intro.
- 🎨 Tweak Tailwind classes to change color palette and layout.
- 🔒 Replace EmailJS credentials with your own for security.
- 📁 Add new sections like Resume, Blog, or Testimonials if needed.

---

## 📄 License

This project is open source and free to use. Attribution appreciated! ❤️
