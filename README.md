# SWE-363 Portfolio — Assignment 4 | Abdulrahman Alomar

![Status: Complete](https://img.shields.io/badge/Status-Complete-22c55e)
![Assignment: 4](https://img.shields.io/badge/Assignment-4-3b82f6)

## Project Description

This project is the **final, production-ready iteration** of an interactive portfolio website for SWE-363. Building on Assignments 1, 2, and 3, it delivers a complete, polished web application featuring **external API integration**, **complex filtering and sorting logic**, **visitor state management**, **performance optimizations**, **comprehensive documentation**, and a **professional video presentation** — all implemented with vanilla HTML, CSS, and JavaScript.

## Deployment Link
```bash
https://alomar04.github.io/202263820-abdualrhmanalomar-assignment4/
```
### Key Features

- **GitHub API** — Fetches and displays public repositories dynamically with language indicators, stars, and forks
- **Quotes API** — Shows random inspirational quotes from DummyJSON with graceful fallback
- **Weather API** — Displays current weather information for Dhahran via Open-Meteo (no API key required)
- **Project Filtering & Sorting** — Filter by category and skill level, sort by date or name
- **Visitor State Management** — Simulated login/logout with `localStorage`, greeting banner, and session timer
- **Dark / Light Theme** — Persisted theme toggle using CSS custom properties and `localStorage`
- **Advanced Form Validation** — Subject field, character counter, minimum length checks, real-time feedback
- **Security** — XSS prevention via `escapeHTML()`, input sanitization, safe external links
- **Performance** — Lazy-loaded API data, deferred scripts, efficient DOM rendering, clean CSS architecture
- **Responsive Design** — Mobile-first layout with breakpoints at 980px and 640px

## File Structure

```text
202263820-abdualrhmanalomar-assignment4/
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── images/
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
├── presentation/
│   ├── slides.pdf
│   └── demo-video.mp4
└── .gitignore
```

## Setup Instructions

### Option 1: Clone and Open

1. Clone the repository:
   ```bash
   git clone https://github.com/Alomar04/202263820-abdualrhmanalomar-assignment4.git
   ```
2. Open the project directory:
   ```bash
   cd 202263820-abdualrhmanalomar-assignment4
   ```
3. Open `index.html` in any modern web browser:
   ```bash
   open index.html
   ```

### Option 2: Live Deployment

Visit the live site: [GitHub Pages link] _(add your deployment URL here)_

### Requirements

- No build tools, package managers, or external setup steps are required
- This is a static frontend project — just open `index.html` in a browser
- Recommended browsers: Chrome, Edge, Firefox, Safari (latest versions)
- Internet connection required for API features (GitHub repos, quotes, weather)

## How to Use

1. **Navigate** — Click the tab buttons (About, Projects, GitHub, Contact) to switch sections
2. **Theme** — Use the theme toggle button to switch between light and dark mode
3. **Set Name** — Click "Set Name" in the header to enter your visitor name and see a personalized greeting
4. **Browse Quotes** — Click "New Quote" on the About page to fetch a new inspirational quote
5. **Filter Projects** — Use the dropdowns on the Projects page to filter by category/level and sort by date/name
6. **View GitHub Repos** — Open the GitHub tab to see live repository data pulled from the GitHub API
7. **Contact Form** — Fill out the form with real-time validation feedback and character counter

## Technical Highlights

| Feature | Implementation |
|---------|---------------|
| API Integration | 3 external APIs (GitHub, DummyJSON, Open-Meteo) with `fetch` + `async/await` |
| Error Handling | Graceful fallbacks for every API (retry buttons, fallback data, friendly messages) |
| State Management | `localStorage` for theme, visitor name; `sessionStorage` for timer |
| Security | `escapeHTML()` for XSS prevention, input sanitization, `rel="noopener noreferrer"` |
| Responsive | CSS Grid + Flexbox with breakpoints at 980px (tablet) and 640px (mobile) |
| Theming | CSS custom properties for instant dark/light switching |
| Accessibility | ARIA attributes (`role`, `aria-label`, `aria-selected`, `aria-controls`, `aria-live`) |
| Performance | Lazy-loaded GitHub data, deferred script, font preconnect hints |

## Browser Compatibility

Works across current versions of Chrome, Edge, Firefox, and Safari. Uses standard HTML5, CSS3, and ES6+ JavaScript features.

## AI Usage Summary

GitHub Copilot, Claude, and ChatGPT were used as development assistants for code generation, debugging, code review, and documentation support. All AI-generated output was reviewed, understood, and modified to match the assignment requirements. Full details are in [docs/ai-usage-report.md](docs/ai-usage-report.md).

## Presentation

The presentation includes:
- **Slide deck** (`presentation/slides.pdf`) — 10 professional slides with screenshots and visual aids
- **Demo video** (`presentation/demo-video.mp4`) — 5 minute recorded presentation 

## License

This project was created for SWE-363 at KFUPM. © 2026 Abdulrahman Alomar.
