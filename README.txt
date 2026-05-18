# <CassandraArcilla />

## Personal Portfolio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat\&logo=css3\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat\&logo=bootstrap\&logoColor=white)](https://getbootstrap.com/)
[![React](https://img.shields.io/badge/React_18-61DAFB?style=flat\&logo=react\&logoColor=black)](https://react.dev/)
[![EmailJS](https://img.shields.io/badge/EmailJS-FF6B35?style=flat)](https://www.emailjs.com/)

> A multi-page personal portfolio built with vanilla HTML, CSS, and JavaScript — featuring advanced animations, a dark/light theme system, interactive project modals, and a functional contact form.

---

##  Live Pages

| Page     | File                     | Description                                                             |
| -------- | ------------------------ | ----------------------------------------------------------------------- |
| Home     | `home/home.html`         | Hero section with particle background and animated React code card      |
| About    | `about/about.html`       | Profile, skills, education, and professional biography                  |
| Projects | `projects/projects.html` | Project cards with modal gallery, role badges, and contribution details |
| Resume   | `resume/resume.html`     | Timeline-style resume with downloadable PDF                             |
| Contact  | `contact/contact.html`   | EmailJS contact form with FAQ accordion                                 |

---

##  Key Features

###  Animation System

* Particle background with mouse interaction
* Custom animated cursor
* 3D tilt service cards
* Magnetic call-to-action buttons
* Scroll reveal engine
* Typewriter section headers
* Floating badge cycle
* Counter animations
* Ripple click effects
* Animated section accent lines

###  Dark / Light Theme

* Navbar toggle switch
* Theme saved in `localStorage`
* Navbar remains dark in both modes
* Warm light mode (`#fdfaf7`) fully supported
* Fully responsive layout

###  Animated React Code Card (Homepage)

* Typewriter syntax highlighting
* Line numbers + status indicator
* macOS-style window UI
* Glitch + floating animations

###  Project Modal System

* Full-screen blur overlay
* Screenshot gallery with thumbnails
* Role badges and contribution lists
* Live + GitHub links
* ESC / click-outside close support

###  Contact Form

* EmailJS integration
* `mailto:` fallback
* Character counter
* Input glow + progress animations
* Success/error feedback UI

---

##  Project Structure

```
cassandraarcilla-portfolio/
├── assets/
│   ├── shared.css
│   └── shared.js
│
├── home/
├── about/
├── projects/
├── contact/
├── resume/
└── README.md
```

---

##  Getting Started

### Option 1 — Python

```bash
python -m http.server 8000
```

### Option 2 — Node

```bash
npx serve .
```

Then open:

```
http://localhost:8000/home/home.html
```

---

##  EmailJS Setup

1. Create account at [https://www.emailjs.com/](https://www.emailjs.com/)
2. Create service + template
3. Add credentials in `contact/contact.js`:

```js
const EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';
const EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
const EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';
```

### Required template variables:

* `{{from_name}}`
* `{{from_email}}`
* `{{subject}}`
* `{{message}}`

Recipient email:

```
arcillacassandra009@gmail.com
```

---

##  Design System

### Colors

* Maroon: `#7b1422`
* Accent: `#c42040`
* Deep Maroon: `#5c0f1a`
* Dark BG: `#0a0a0b`
* Light BG: `#fdfaf7`

### Fonts

* Playfair Display — headings
* DM Mono — code/labels
* Lato — body text

---

##  Customization Checklist

* [ ] Add EmailJS credentials
* [ ] Replace project images
* [ ] Update GitHub/social links
* [ ] Replace resume PDF
* [ ] Update personal info
* [ ] Add/update projects

---

##  Author

**Cassandra Aubrey R. Arcilla**
Frontend Web Developer · UI/UX Designer
Angeles City, Philippines
mailto:arcillacassandra009@gmail.com

