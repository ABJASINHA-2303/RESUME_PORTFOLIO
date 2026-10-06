Abja Sinha — Portfolio

A single-page developer portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. Dark, terminal-inspired design with a subtle animated neural-network visual, a typewriter hero effect, and scroll-reveal animations.

**Live site:** https://abjasinha-2303.github.io/PORTFOLIO_ABJA_SINHA/

> The link above works once GitHub Pages is enabled (see [Deploying](#-deploying-to-github-pages)).

---

✨ Features

- **Single-file architecture** — markup, styles, and script all live in `index.html`; nothing to install.
- **Animated hero section** with a typewriter effect cycling through role titles and a pulsing SVG neural-network illustration, a nod to the AI specialization and CNN project.
- **Scroll-reveal animations** via `IntersectionObserver`, with a `prefers-reduced-motion` fallback.
- **Fully responsive** — grid layouts collapse cleanly on tablet and mobile.
- **Accessible by default** — semantic HTML, visible focus states, reduced-motion support.

📄 Sections

| Section | What it covers |
| --- | --- |
| **Hero** | Name, rotating role titles, short intro, call-to-action buttons, animated neural-network graphic |
| **About** | Background summary, current focus, and what I'm looking for next |
| **Experience** | Java Full Stack Development Intern at JSpiders |
| **Projects** | Restaurant Management System (Spring Boot + JWT), AVision CNN self-driving simulation, ESP32 IoT environment monitor |
| **Skills** | Pill tags grouped by Languages, Backend, Frontend, Databases, AI/ML, and Tools & QA |
| **Education** | B.Tech in Computer Science Engineering (AI Specialization) and 12th (CBSE) |
| **Contact** | Email, phone, LinkedIn, and GitHub |

🛠 Tech Stack

| Layer | Technology |
| --- | --- |
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS3 (custom properties, CSS Grid, Flexbox) |
| Typography | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts |
| Interactivity | Vanilla JavaScript (typewriter effect, SVG animation, scroll-reveal) |
| Hosting | Static — GitHub Pages, Netlify, or Vercel |

📂 Project Structure

```
PORTFOLIO_ABJA_SINHA/
├── index.html   # Entire site: markup, <style>, and <script>
└── README.md
```

🚀 Running Locally

No build tools or package installs required.

```bash
git clone https://github.com/ABJASINHA-2303/PORTFOLIO_ABJA_SINHA.git
cd PORTFOLIO_ABJA_SINHA
```

Then either open `index.html` directly in a browser, or serve it locally:

```bash
python -m http.server 8000
# visit http://localhost:8000
```

🌐 Deploying to GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two, the site is live at  
   `https://abjasinha-2303.github.io/PORTFOLIO_ABJA_SINHA/`

Netlify and Vercel also work: import the repo, leave the build command empty, and set the publish directory to the repo root.

✏️ Customizing

- **Text and content:** edit the matching section in `index.html`.
- **Colors and fonts:** change the CSS custom properties at the top of the `<style>` block.
- **Typewriter roles:** update the roles array in the `<script>` block.
- **Contact links:** update the `href` values in the `.contact-links` block.

📬 Contact

- **Email:** [abjaaaa.1903@gmail.com](mailto:abjaaaa.1903@gmail.com)
- **Phone:** +91 93406 81759
- **LinkedIn:** [linkedin.com/in/abjasinha23](https://linkedin.com/in/abjasinha23)
- **GitHub:** [github.com/ABJASINHA-2303](https://github.com/ABJASINHA-2303)

---

Built with intent, not a template.
