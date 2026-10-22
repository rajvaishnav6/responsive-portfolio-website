# Raj Vaishnav | Full Stack Developer Portfolio

<p align="center">
  <a href="https://responsive-portfolio-website-ashen.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Portfolio-Visit%20Website-8A2BE2?style=for-the-badge" alt="Visit live portfolio" />
  </a>
  <a href="https://github.com/rajvaishnav6/responsive-portfolio-website">
    <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github" alt="View source code on GitHub" />
  </a>
</p>

A personal portfolio website showcasing my background as a **B.Tech Computer Science and Engineering student (2027)**, my full-stack development skills, selected projects, education, certificates, resume, and contact links.

## 🔗 Links

- **Live Portfolio:** [responsive-portfolio-website-ashen.vercel.app](https://responsive-portfolio-website-ashen.vercel.app/)
- **GitHub Repository:** [rajvaishnav6/responsive-portfolio-website](https://github.com/rajvaishnav6/responsive-portfolio-website)
- **GitHub Profile:** [github.com/rajvaishnav6](https://github.com/rajvaishnav6)
- **LinkedIn:** [Raj Vaishnav](https://www.linkedin.com/in/raj-vaishnav-121154210/)

## ✨ Features

- Responsive personal portfolio layout for desktop and mobile screens.
- Introduction and About section highlighting my developer profile.
- Downloadable resume.
- Project showcase with links to live projects and source repositories.
- Education timeline.
- Certificate carousel with credential links.
- Skills and services section with an expandable panel.
- Animated role text, scroll-reveal effects, and interactive project/certificate sliders.
- Contact section with a copy-email button and social links.
- Automatically updated copyright year.

## 🛠️ Technologies Used

### Portfolio

- **HTML5** — page structure and content
- **CSS3** — styling, layout, animations, and responsive design
- **JavaScript** — interactive behaviour
- **Swiper.js** — project and certificate sliders
- **ScrollReveal.js** — scroll-based reveal animations
- **Anime.js** — animated text effects
- **Remix Icon** — interface icons
- **Google Fonts** — Montserrat and Unbounded typography

Swiper.js and ScrollReveal.js are included in the project assets. Anime.js, Remix Icon, and Google Fonts are loaded from external CDNs, so an internet connection is recommended when viewing the site.

## 🚀 Featured Projects

| Project | Description / Technologies | Link |
|---|---|---|
| **Blockchain-Based Voting System** | Voting application using React.js, Tailwind CSS, Node.js, Express.js, PostgreSQL, Solidity, Ethereum, MetaMask, Ethers.js, and JWT. | [Open Project](https://blockchain-voting-system-iota.vercel.app/) |
| **Hospital Management System** | Java application using Swing, AWT, JDBC, and MySQL. | [View GitHub Repository](https://github.com/rajvaishnav6/Hospital_Management_System) |
| **Byte2Bite** | Online food website showcased in the portfolio. | [Open Project](https://byte-2-bite.vercel.app/) |
| **Project Management Platform** | Full-stack project using Next.js, React.js, Tailwind CSS, Node.js, Express.js, and REST APIs; associated with my Full Stack Development internship at Innovation Hacks. | [Open Project](https://innovation-hacks-internship.vercel.app/login) |

## 📁 Project Structure

The website source is inside the `responsive-portfolio-website-raj/` directory in this repository.

```text
responsive-portfolio-website/
├── README.md
└── responsive-portfolio-website-raj/
    ├── index.html
    └── assets/
        ├── CSS/
        │   ├── styles.css
        │   └── swiper-bundle.min.css
        ├── JS/
        │   ├── main.js
        │   ├── scrollreveal.min.js
        │   └── swiper-bundle.min.js
        ├── img/
        └── pdf/
            └── Raj_Vaishnav_Full_Stack_Developer_Resume.pdf
```

## 💻 Run Locally

This is a static website and does not require a Node.js build step.

### Option 1: Clone and run with Python

```bash
git clone https://github.com/rajvaishnav6/responsive-portfolio-website.git
cd responsive-portfolio-website/responsive-portfolio-website-raj
python -m http.server 5500
```

Open **http://localhost:5500** in your browser.

### Option 2: VS Code Live Server

1. Clone or download this repository.
2. Open the `responsive-portfolio-website-raj` folder in VS Code.
3. Open `index.html` and choose **Open with Live Server**.

You can also open `index.html` directly in a browser, though a local server is recommended.

## ✏️ Customization

- **Text, sections, project links, and certificates:** edit `responsive-portfolio-website-raj/index.html`.
- **Colors, typography, layout, and responsive styles:** edit `responsive-portfolio-website-raj/assets/CSS/styles.css`.
- **Interactions and animations:** edit `responsive-portfolio-website-raj/assets/JS/main.js`.
- **Project images and certificate images:** update files in `responsive-portfolio-website-raj/assets/img/` and keep the filenames in `index.html` in sync.
- **Resume:** replace the PDF in `responsive-portfolio-website-raj/assets/pdf/` and update its path in `index.html` if the filename changes.

Keep the relative `assets/...` paths consistent with the current folder structure so images, styles, scripts, and the resume continue to load correctly.

## 📬 Contact

- **Email:** [rajvaishnavraj6@gmail.com](mailto:rajvaishnavraj6@gmail.com)
- **LinkedIn:** [Raj Vaishnav](https://www.linkedin.com/in/raj-vaishnav-121154210/)
- **GitHub:** [rajvaishnav6](https://github.com/rajvaishnav6)

---

**Built and maintained by Raj Vaishnav.** The current website footer also credits Bedimcode; review the original template's terms if you plan to redistribute or reuse its design/source.
