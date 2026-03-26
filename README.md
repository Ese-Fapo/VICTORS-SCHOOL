# ROCKSTAR Study Abroad Website

A polished multi-page marketing website for an international education agency, built to present services clearly, improve trust with prospective students, and support conversion through strong calls-to-action.

**Live site:** `https://rockstarstudyabroad.com/`

## Why this project stands out

This project is more than a static website. It demonstrates how I approach front-end work with a product mindset:

- build clean, user-focused interfaces
- improve performance without adding unnecessary complexity
- strengthen accessibility and SEO fundamentals
- prepare projects for real-world hosting and deployment
- turn a business website into a more credible, conversion-friendly experience

For recruiters and hiring managers, this repo shows practical front-end skills applied to a real business use case.

## Project overview

ROCKSTAR Study Abroad helps students explore global education opportunities, compare destinations, and connect with the agency for admissions and visa support.

The website includes:

- a landing page with service highlights and testimonials
- dedicated pages for about, programs, destinations, events, FAQs, and contact
- WhatsApp and contact-driven conversion paths
- responsive layouts for desktop and mobile users
- deployment-ready static hosting support

## Highlights

### User experience

- Clear navigation across all core pages
- Strong call-to-action flow from homepage to contact/application
- Social proof via testimonials and experience metrics
- Contact options tailored for quick enquiry, including WhatsApp

### Performance work

- Lazy loading for off-screen images
- Deferred local scripts for faster initial rendering
- Preload and fetch priority hints for key hero imagery
- Reduced unnecessary third-party loading on first paint
- `content-visibility` optimizations for below-the-fold content

### Accessibility and semantics

- Skip link for keyboard users
- Semantic landmark structure with `<main>`
- Improved button labeling and navigational accessibility
- Better alt text for important imagery

### SEO and deployment readiness

- Improved page metadata and social sharing tags
- Canonical URL support
- Lowercase route consistency for Linux hosting compatibility
- Ready for static deployment on Hostinger or similar platforms

## Tech stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Swiper.js** for testimonials carousel
- **Elfsight** widget integration
- **Hostinger / Apache-style static hosting**

## What I improved technically

This repository includes several practical front-end optimization changes:

- centralized image lazy-loading behavior in `main.js`
- conditional Swiper loading with `IntersectionObserver`
- deferred script loading on the homepage
- preconnect and DNS-prefetch hints for third-party resources
- cleanup of invalid or duplicate markup
- stronger external link security with `rel="noopener noreferrer"`
- improved metadata for search and sharing previews

These are the kinds of details that matter in production projects because they improve maintainability, page speed, and the overall user experience.

## Project structure

- `index.html` — homepage
- `about/about-us.html` — about page
- `programs/programs.html` — study programs overview
- `destination/destination.html` — destination information
- `events/events.html` — events page
- `faq/faq.html` — frequently asked questions
- `contact/contact.html` — contact page with WhatsApp enquiry links
- `style.css` — shared global styling
- `index.css` — homepage-specific styling
- `main.js` — shared interaction and optimization logic
- `index.js` — homepage-specific JavaScript behavior

## Running locally

Because this is a static site, no build step is required.

### Quick preview

Open `index.html` directly in your browser.

### Better local testing

Serve the project with any static server and visit:

- `http://localhost:<port>/index.html`

## Deployment

This project is prepared for static hosting.

### Hostinger Git deployment

1. Push the repository to GitHub.
2. In Hostinger hPanel, open **Git**.
3. Connect your repository.
4. Deploy the `main` branch to `public_html`.

### Hosting notes

- `index.html` is the entry point
- lowercase file paths are used to avoid case-sensitivity issues
- `.htaccess` support is included for Apache-compatible environments

For full hosting details, see `HOSTINGER_DEPLOYMENT.md`.

## Lighthouse and quality notes

Recent measured scores captured in this project history:

| Date | Environment | Performance | Best Practices | SEO |
|------|-------------|------------:|---------------:|----:|
| 2026-03-12 | Local/Preview | 93 | 77 | 82 |

> These values reflect a previous optimization pass recorded in the repository notes.

## Business context

The site content positions the brand around:

- 18+ years of experience
- 5,000+ students guided
- 350+ partner institutions

That makes this a useful example of translating business trust signals into a structured web experience.

## Recruiter notes

If you're reviewing this repository as part of a hiring process, this project demonstrates:

- strong fundamentals in HTML, CSS, and JavaScript
- practical website optimization work
- accessibility and SEO awareness
- ability to improve an existing codebase, not just build from scratch
- attention to deployment constraints and real-world hosting details

## Customise this before sharing widely

To make this README even stronger for your public GitHub profile, replace the placeholders below with your real details:

- **Your name:** `[Add your name here]`
- **Portfolio:** `[Add your portfolio link]`
- **LinkedIn:** `[Add your LinkedIn link]`
- **Email:** `[Add your professional email]`

Suggested footer:

`Built and maintained by [Your Name]. Open to front-end, web design, and junior developer opportunities.`
