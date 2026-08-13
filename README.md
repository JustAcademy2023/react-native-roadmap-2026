# React Native Developer Roadmap 2026 — Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-5EEAD4?style=flat-square)
![No Build Step](https://img.shields.io/badge/Build%20Step-None-FFB454?style=flat-square)

A single page, dependency free landing page for the **React Native Developer Roadmap 2026: Skills, Projects and Career Guide**. Built around a dark, terminal inspired visual language, an animated build log hero, and a git branch style roadmap timeline instead of the usual template look.

**[View the live version →](#)** *(replace with your GitHub Pages URL after publishing)*

## What this is

A conversion focused, scroll worthy landing page that walks a visitor through the seven stage roadmap to becoming a job ready React Native developer, compares React Native against Flutter, Android native and iOS native, and links out to the full course, a free demo, and two companion articles.

## Design notes

- **Look and feel** — deep ink background, warm amber and mint accents, `Space Grotesk` for headings, `Inter` for body copy, and `JetBrains Mono` for terminal and label text. No stock gradients, no generic hero illustration.
- **Signature moment** — a terminal window in the hero types out a fake build log line by line and ends on "Ready to ship." Respects `prefers-reduced-motion`.
- **Roadmap section** — a vertical git branch style timeline with alternating stage cards, styled like terminal commands (`$ stage_01 --js-foundations`) rather than plain numbered circles.
- **Footer** — styled like a `package.json` file, doubling as a link directory for every course and article referenced on the page.
- Fully responsive down to small mobile screens, with a collapsible nav menu, visible keyboard focus states, and scroll reveal animation on cards.

## File structure

```
.
├── index.html      # everything lives in one file — markup, styles, and script
└── README.md
```

No build tools, package manager, or framework required. Open `index.html` directly in a browser, or deploy as is.

## Running locally

```bash
git clone https://github.com/your-username/react-native-roadmap-2026.git
cd react-native-roadmap-2026
open index.html
```

Any static file server works too, for example:

```bash
npx serve .
```

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/root`.
4. Save. Your page will be live at `https://your-username.github.io/react-native-roadmap-2026/`.

## Links referenced on the page

| Section | Destination |
|---|---|
| Hero and footer | React Native training course |
| Header and CTA banner | Free course demo |
| Tracks section | Flutter, Android native, and iOS native courses |
| Roadmap stage one | JavaScript training course |
| Resources section and footer | Roadmap article and the Flutter vs React Native vs Android vs iOS comparison article |

## License

Free to use, adapt, and restyle for your own project.
