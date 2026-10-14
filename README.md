# Kanika's Professional & Minimalist Portfolio

A modern, responsive, and minimalist personal portfolio crafted for **Kanika** — Computer Engineering Student at **Thiagarajar Polytechnic College** and Project Management Intern at **JK Digital**.

Designed with clean typography, refined contrast, subtle micro-interactions, dark & light theme modes, and an integrated printable resume preview.

---

## 🌟 Key Highlights & Features

- **Minimalist Aesthetic:** Inspired by modern engineering portfolios (clean lines, subtle glow, refined borders, and generous whitespace).
- **Dual Themes:** Seamless Dark and Light theme toggle with local storage persistence and system preference detection.
- **Academic & Industry Showcase:**
  - **About:** Lateral entry background, technical passion, and career philosophy.
  - **Experience:** Project Management Internship at JK Digital with breakdown of responsibilities and skills.
  - **Education:** 2nd-year Computer Engineering at Thiagarajar Polytechnic College & Higher Secondary foundation.
  - **Skills:** Categorized into Project Management, Computer Engineering & Technical, and Interpersonal Leadership with animated progress indicators.
  - **Future Roadmap:** High-ambition trajectory targeting PSG College of Technology and Google.
- **Interactive Resume Modal:** Built-in clean resume sheet with a one-click **Print / Save as PDF** command.
- **One-Click Email Copy:** Automatic copy-to-clipboard button with toast feedback.
- **Fully Responsive:** Tailored layout for mobile phones, tablets, laptops, and ultra-wide screens.
- **Zero Dependencies:** Pure HTML5, modern CSS3, and vanilla JavaScript. Runs instantly in any browser without needing `npm install` or node servers.

---

## 📁 Project Structure

```text
kanika-portfolio/
│
├── index.html        # Main semantic markup with all portfolio sections
├── style.css         # Modern styling, theme tokens, animations & print styles
├── script.js         # Theme toggle, modal handlers, copy buttons & interactions
└── README.md         # Guide & customization instructions
```

---

## 🚀 How to View Locally

### Option 1: Direct Double-Click
Simply double-click [`index.html`](./index.html) in your Windows File Explorer to open it in your browser (Google Chrome, Edge, Brave, etc.).

### Option 2: Live Server (VS Code)
If using Visual Studio Code:
1. Open the folder `D:\kanika portfolio` in VS Code.
2. Install the **Live Server** extension.
3. Click **"Go Live"** in the bottom status bar.

### Option 3: Python HTTP Server (PowerShell)
Run the following command in PowerShell:
```powershell
python -m http.server 3000
```
Then visit `http://localhost:3000` in your web browser.

---

## ✏️ Easy Customizations

To personalize with your exact details, open [`index.html`](./index.html) in your text editor:

1. **Email Address:**
   - Search for `kanika.connect@example.com` and replace it with your personal or college email.
   - Update the `data-email` attributes on the copy buttons as well.

2. **LinkedIn & GitHub Links:**
   - Search for `linkedin.com/in/kanika` and replace the `href` attribute with your LinkedIn profile URL.
   - Search for `github.com/kanika` and replace the `href` attribute with your GitHub URL.

3. **Resume Details:**
   - Modify the contents inside `<div id="resumeModal">` if you want to add specific course projects, grades, or certifications.

---

## 🌐 Free Deployment Options

### 1. GitHub Pages (Recommended)
1. Initialize a git repository and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Kanika portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Branch**, select `main` and `/ (root)`, then click **Save**.
   - Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

### 2. Netlify / Vercel
- Simply drag and drop this folder onto [Netlify Drop](https://app.netlify.com/drop) or import from GitHub on [Vercel](https://vercel.com) for instant SSL-secured deployment.
