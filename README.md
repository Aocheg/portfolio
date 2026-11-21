# 💼 Developer Portfolio | Adanu Oche Gabriel

A modern, high-converting, responsive developer portfolio for **Adanu Oche Gabriel** — AI-Native Full-Stack Software Engineer & Registered Nurse (B.N.Sc., RN).

Designed with Tailwind CSS, Lucide Icons, Dark/Light mode theme toggle, print-ready resume page, and deep showcase of featured projects including the **NCD Patient Safety Platform**, **Automated Payroll**, **Go-Reloaded**, and **CareLink**.

---

## 🚀 How to Preview Locally

Run Python's built-in web server:

```bash
cd /home/student/portfolio
python3 -m http.server 3000
```

Open your browser to: **`http://localhost:3000`** (or `http://127.0.0.1:3000`)
- Portfolio: `http://localhost:3000/`
- Resume / CV: `http://localhost:3000/resume.html`

---

## 🌐 How to Deploy to GitHub Pages (100% Free)

You can host this portfolio permanently for free using **GitHub Pages** under your GitHub account (`@Aocheg`).

### Option A: Create a Dedicated Portfolio Repo (`https://aocheg.github.io/portfolio`)

1. Go to GitHub and click **[New Repository](https://github.com/new)**.
2. Name the repository: **`portfolio`** (set to **Public**). Do NOT initialize with README.
3. In your terminal, initialize and push from this folder:
   ```bash
   cd /home/student/portfolio
   git init
   git add .
   git commit -m "feat: initial launch of developer portfolio and resume"
   git branch -M main
   git remote add origin https://github.com/Aocheg/portfolio.git
   git push -u origin main
   ```
4. On GitHub, go to **Settings** > **Pages** (in the left sidebar).
5. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
6. In ~60 seconds, your portfolio will be live at:
   👉 **`https://aocheg.github.io/portfolio/`**

---

### Option B: Root User Page (`https://aocheg.github.io`)

If you want the cleanest possible URL (`https://aocheg.github.io`):
1. Create a repository on GitHub named exactly: **`Aocheg.github.io`**
2. Push this folder to that repository:
   ```bash
   cd /home/student/portfolio
   git init
   git add .
   git commit -m "feat: initial launch of developer portfolio"
   git branch -M main
   git remote add origin https://github.com/Aocheg/Aocheg.github.io.git
   git push -u origin main
   ```
3. Your portfolio is immediately live at:
   👉 **`https://aocheg.github.io`**

---

## 📄 Included Files

- `index.html`: The main single-page portfolio with Hero, Metrics, Clinical Advantage, Filterable Projects, Skills Matrix, and Contact section.
- `resume.html`: A clean, printable, ATS-friendly resume and CV. Clicking "Print or Save as PDF" renders a clean 1-2 page document.
- `README.md`: Deployment and setup instructions.
