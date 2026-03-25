# Shijia Tang — Personal Portfolio Website

[![Live Site](https://img.shields.io/badge/Live%20Site-joytang2023.github.io-blue?style=flat-square&logo=github)](https://joytang2023.github.io)
[![HTML](https://img.shields.io/badge/Built%20with-HTML-orange?style=flat-square&logo=html5)](https://github.com/JoyTang2023/JoyTang2023.github.io)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)](https://joytang2023.github.io)

A personal portfolio website for **Shijia (Joy) Tang**, a Data Science & AI master's graduate from Chalmers University of Technology. The site showcases her professional experience, technical skills, projects, and education.

🌐 **Live at:** [https://joytang2023.github.io](https://joytang2023.github.io)

---

## 📋 Contents

- [About](#about)
- [Sections](#sections)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Local Development](#local-development)
- [Use This Template](#-use-this-template-with-claude)
- [Contact](#contact)

---

## About

This is a single-page personal portfolio hosted on GitHub Pages. It is built with plain HTML, CSS, and JavaScript — no frameworks or build tools required. The site is fully responsive and designed to present Shijia's background as a data scientist and AI engineer to potential employers and collaborators.

---

## Sections

The portfolio is organized into the following sections:

| Section | Description |
|---|---|
| **Hero** | Introduction and quick links (LinkedIn, email) |
| **About** | Personal background, interests, and language skills |
| **Skills** | Technical toolbox: programming, ML/AI, and data & analytics |
| **Experience** | Work history including internships at iMatrics, ABB, and others |
| **Projects** | Selected project highlights with tech tags and outcomes |
| **Education** | Degrees from Chalmers University of Technology and NUAA, plus leadership |
| **Contact** | Email, phone, and LinkedIn |

---

## Tech Stack

- **HTML5** — single-page structure
- **CSS3** — custom styling and responsive layout
- **JavaScript** — interactivity and smooth scrolling
- **GitHub Pages** — free static site hosting

---

## Project Structure

```
JoyTang2023.github.io/
├── index.html      # Main (and only) HTML file — all content and styles
└── photo.jpg       # Profile photo
```

---

## Local Development

No build tools or dependencies are required. Choose the path that suits you:

---

### 🖥️ Option A — For Git Users

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JoyTang2023/JoyTang2023.github.io.git
   cd JoyTang2023.github.io
   ```

2. **Open in your browser:**
   ```bash
   open index.html        # macOS
   start index.html       # Windows
   xdg-open index.html    # Linux
   ```
   Or drag `index.html` into any modern browser.

3. **Edit** `index.html` in your text editor of choice and refresh the browser to preview changes.

4. **Deploy** by committing and pushing to `main` — GitHub Pages updates the live site automatically within a minute or two:
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push
   ```

---

### 📁 Option B — For Non-Git Users (No installation needed)

**Step 1 — Download the files**

- Go to [github.com/JoyTang2023/JoyTang2023.github.io](https://github.com/JoyTang2023/JoyTang2023.github.io)
- Click the green **`<> Code`** button → **Download ZIP**
- Unzip the downloaded file anywhere on your computer

**Step 2 — Preview locally**

- Open the unzipped folder
- Double-click `index.html` — it will open directly in your browser
- You're running the site locally, no server needed ✅

**Step 3 — Edit the content**

- Open `index.html` in any text editor:
  - **Windows:** Notepad, [Notepad++](https://notepad-plus-plus.org/), or [VS Code](https://code.visualstudio.com/)
  - **macOS:** TextEdit (use Format → Make Plain Text first), or [VS Code](https://code.visualstudio.com/)
- Find the section you want to change (use **Ctrl+F** / **Cmd+F** to search for text)
- Save the file and refresh your browser to see the result

**Step 4 — Publish to GitHub Pages**

1. Create a free account at [github.com](https://github.com) if you don't have one
2. Click **+** → **New repository**, and name it exactly: `YOUR-USERNAME.github.io`
3. On the next screen, click **uploading an existing file**
4. Drag both `index.html` and your `photo.jpg` into the upload area
5. Click **Commit changes**
6. Your site will be live at `https://YOUR-USERNAME.github.io` within a minute or two 🎉

> **Updating later:** repeat Step 4 — go to your repository, click the file you want to replace, then click the pencil ✏️ icon to edit it directly in the browser, or click **Add file → Upload files** to re-upload a modified version.

---

## 🤖 Use This Template with Claude

Want to adapt this portfolio for yourself? Copy the prompt below, paste it into [Claude](https://claude.ai), and attach the `index.html` file from this repo. Claude will rewrite the entire site with your personal details.

````
I'm attaching index.html from a personal portfolio website I'd like to use as a template.
Please adapt it to become my own portfolio. Here is my information:

**Personal**
- Full name: [Your Name]
- Tagline / role: [e.g. "Full-Stack Engineer", "UX Designer & Researcher"]
- Location: [City, Country]
- Email: [your@email.com]
- Phone: [optional]
- LinkedIn: [linkedin.com/in/your-profile]
- GitHub: [github.com/your-username]
- Profile photo filename: [photo.jpg — I'll replace this file myself]

**About me (2–4 sentences about who you are and what drives you):**
[Write a short personal bio here]

**Hobbies / interests (emoji + label format welcome):**
[e.g. 🎸 Guitar, 🧗 Climbing, ✈️ Travel]

**Languages spoken:**
[e.g. English (Native), Spanish (Fluent), French (Basics)]

**Skills (group by category):**
- Programming: [e.g. Python, TypeScript, Rust]
- Frameworks & tools: [e.g. React, FastAPI, Docker]
- Other: [e.g. Figma, SQL, AWS]

**Work experience (repeat for each role):**
- Company: [Name]
- Role: [Title]
- Dates: [YYYY/MM – YYYY/MM or Present]
- 2–3 bullet points of what you did and impact achieved

**Projects (repeat for each):**
- Title: [Project name]
- Dates: [YYYY/MM – YYYY/MM]
- Description: [1–2 sentences on what it is and why it matters]
- Tech tags: [e.g. React, PostgreSQL, Docker]

**Education (repeat for each):**
- Degree & field: [e.g. B.Sc. Computer Science]
- University: [Name]
- Dates: [YYYY/MM – YYYY/MM]
- Location: [City, Country]
- Relevant courses or highlights (optional)

**Any sections to add, remove, or rename?**
[e.g. "Add a Publications section", "Remove the phone number", "Rename Experience to Work"]

**Color scheme / style preferences (optional):**
[e.g. "Keep it minimal", "Dark mode", "Use blue and white as accent colors"]

Please return the complete, updated index.html ready to drop into my GitHub Pages repo.
````

> **Tip:** The more detail you provide for each field, the better the result. You can leave optional fields blank and Claude will omit them gracefully.

---

## Contact

| | |
|---|---|
| 📧 Email | [sjtang100@gmail.com](mailto:sjtang100@gmail.com) |
| 🔗 LinkedIn | [linkedin.com/in/shijiatang-925a35204](https://www.linkedin.com/in/shijiatang-925a35204) |
| 📍 Location | Gothenburg, Sweden |

---

© 2026 Shijia Tang
