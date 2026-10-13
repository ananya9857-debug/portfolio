# Ananya Verma - Student Developer Portfolio & Resume Site

> **Name:** Ananya Verma  
> **Course:** B.Tech in Computer Science and Engineering (1st Year, 2026 – Present)  
> **College:** JECRC University, Jaipur, Rajasthan  
> **Location:** Jaipur, Rajasthan  
> **Class 12:** MP Board  

---

## 🌟 Overview

A professional, minimal, and modern personal portfolio website built specifically for a first-year Computer Science Engineering student. It includes an integrated, dedicated **Web Resume Site** (`resume.html`) with print-to-PDF support tailored for academic submissions and early internship applications.

---

## 📁 Project Directory Structure

```text
ananya-portfolio/
│
├── index.html                   # Main portfolio website (8 complete sections)
├── resume.html                  # Dedicated, ATS-friendly online resume site
│
├── css/
│   ├── style.css                # Portfolio styles (dark minimal UI, responsive grids)
│   └── resume.css               # Clean resume styles & print stylesheet
│
├── js/
│   └── script.js                # Mobile navigation, scroll spy, animations, form feedback
│
├── assets/
│   └── images/
│       ├── avatar.svg           # Professional SVG profile illustration placeholder
│       └── favicon.svg          # 'AV' monogram developer favicon
│
└── README.md                    # Setup and customization guide
```

---

## 🚀 How to Open the Website

No installation or server setup is required:

1. Navigate to the `ananya-portfolio` folder on your desktop.
2. **Double-click `index.html`** to view your portfolio in Chrome, Edge, Firefox, or Safari.
3. To view your resume directly, **double-click `resume.html`**, or click the **Resume** button in the portfolio navigation bar.

---

## 📄 How to Print or Save Your Resume as a PDF

1. Open `resume.html` in your browser.
2. Click the **"Print / Save as PDF"** button at the top (or press `Ctrl + P`).
3. In the print dialog, select **"Save as PDF"** as the destination.
4. The custom print stylesheet automatically strips away background dark colors, toolbars, and buttons, generating a crisp, clean, black-and-white academic resume ready for recruiters and professors.

---

## 🛠️ How to Customize Placeholders

### 1. Replacing the Profile Photo
1. Place your photo (e.g. `ananya-photo.jpg`) inside the `assets/images/` folder.
2. Open `index.html` in VS Code or Notepad.
3. Search for:
   ```html
   <img src="assets/images/avatar.svg" alt="Ananya Verma - Profile Illustration" ...>
   ```
4. Replace `assets/images/avatar.svg` with your photo's filename:
   ```html
   <img src="assets/images/ananya-photo.jpg" alt="Ananya Verma" ...>
   ```

### 2. Updating GitHub & LinkedIn Links
Search for `https://github.com/ananya-verma` and `https://linkedin.com/in/ananya-verma` in both `index.html` and `resume.html`, and update them with your actual profile URLs.

### 3. Updating Email
Replace `ananya.verma@example.com` with your actual college or personal email address in `index.html`, `resume.html`, and `js/script.js`.

### 4. Adding Certifications & Achievements
The **Achievements** section in `index.html` and `resume.html` is structured with clean placeholder cards. When you complete a course, workshop, or contest, simply add your certificate name, issuing authority, and date inside the designated card.
