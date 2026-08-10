# 100 Day Frontend Development Challenge

A day-by-day roadmap from HTML/CSS basics to full interactive apps. Pairs nicely with your Python challenge — same discipline, different muscle.

## How to use this

- Spend 30–90 minutes per day. Some days are small builds, some are concept days, some are "polish and refactor" days.
- Push each project to a GitHub repo (one repo, one folder per day, or one repo per project — your call).
- Don't skip the "polish" days. That's where you actually get good.
- Miss a day? Don't restart the count. Just keep going.

---

## Phase 1: HTML & CSS Foundations (Days 1–20)

| Day | Task |
|---|---|
| 1 | **Login page** — email/password fields, labels, a submit button. Just structure and basic styling, no JS yet. |
| 2 | Sign-up page (name, email, password, confirm password) |
| 3 | Style Day 1's login page properly — spacing, colors, a card layout |
| 4 | Simple personal profile/bio page (single page, no CSS framework) |
| 5 | Pricing page with 3 pricing cards side by side |
| 6 | Restaurant menu page (sections, categories, prices) |
| 7 | Recipe page (ingredients list + steps) |
| 8 | 404 error page |
| 9 | Learn Flexbox — rebuild Day 5's pricing cards using Flexbox properly |
| 10 | Learn CSS Grid — build a photo gallery grid (static images/placeholders) |
| 11 | Responsive navbar (hamburger menu on mobile, using pure CSS/media queries) |
| 12 | Footer component with columns (links, social icons, copyright) |
| 13 | Blog post layout (title, hero image, body text, sidebar) |
| 14 | Product card component (image, title, price, "Add to Cart" button) |
| 15 | Testimonials section (3 review cards) |
| 16 | FAQ page layout (just static, accordion behavior comes later) |
| 17 | Landing page hero section (headline, subtext, CTA button, image) |
| 18 | Full landing page — combine hero + pricing + testimonials + footer into one page |
| 19 | CSS animations — hover effects, transitions on buttons and cards |
| 20 | **Review day** — pick your weakest layout from Days 1–19 and rebuild it from scratch |

## Phase 2: JavaScript Fundamentals for the DOM (Days 21–40)

| Day | Task |
|---|---|
| 21 | JS basics refresher — variables, functions, DOM selection (`querySelector`) |
| 22 | Make Day 1's login page functional — validate fields, show error messages |
| 23 | Character counter (textarea that shows remaining characters) |
| 24 | Show/hide password toggle on a login form |
| 25 | Light/dark mode toggle (persist choice with `localStorage`) |
| 26 | To-do list — add items |
| 27 | To-do list — delete and mark items complete |
| 28 | To-do list — persist list with `localStorage` |
| 29 | Simple calculator (buttons + display) |
| 30 | Digital clock (updates every second) |
| 31 | Countdown timer to a specific date |
| 32 | Accordion component (click to expand/collapse) — apply to Day 16's FAQ page |
| 33 | Image slider/carousel (manual next/prev buttons) |
| 34 | Auto-playing carousel with pause-on-hover |
| 35 | Modal/popup window (open, close, click-outside-to-close) |
| 36 | Tabs component (switch content without reloading) |
| 37 | Form validation library — build reusable validation for email, password strength, required fields |
| 38 | Star rating widget (click to rate) |
| 39 | Drag-and-drop list reordering |
| 40 | **Review day** — refactor your to-do list (Days 26–28) with everything you've learned since |

## Phase 3: APIs, Async & Real Data (Days 41–60)

| Day | Task |
|---|---|
| 41 | `fetch()` basics — display a joke from a free joke API |
| 42 | Weather app (search city, show current weather) using a free weather API |
| 43 | Random quote generator with a "new quote" button |
| 44 | GitHub profile viewer (enter username, show avatar/bio/repos) |
| 45 | Movie search app (search title, show poster + details) |
| 46 | Country info app (search country, show flag/capital/population) |
| 47 | Currency converter using a live exchange rate API |
| 48 | Recipe search app (search ingredient, show matching recipes) |
| 49 | Loading spinners and skeleton screens — add to Days 42–48 |
| 50 | Error handling — add proper error states (no results, API down, no internet) across your API projects |
| 51 | Pagination — build a paginated list from a large public dataset (e.g. `jsonplaceholder`) |
| 52 | Infinite scroll version of Day 51 |
| 53 | Search-as-you-type with debounce |
| 54 | Filter and sort UI for a product list |
| 55 | Shopping cart — add/remove items, calculate total |
| 56 | Shopping cart — persist cart with `localStorage` |
| 57 | Multi-step form (progress bar, next/back between steps) |
| 58 | File upload with image preview |
| 59 | Simple chat UI (static, just the interface — messages, input, send button) |
| 60 | **Review day** — pick your favorite API project and make it fully responsive + polished |

## Phase 4: A Real Framework — React (Days 61–80)

| Day | Task |
|---|---|
| 61 | Set up React (Vite), understand components, JSX, props |
| 62 | Rebuild Day 1's login page as a React component |
| 63 | `useState` — rebuild the Day 26–28 to-do list in React |
| 64 | `useEffect` — rebuild the Day 42 weather app in React |
| 65 | Props drilling practice — parent/child component communication |
| 66 | Conditional rendering — loading/error/success states as components |
| 67 | Lists and keys — render a product grid from an array of objects |
| 68 | Controlled forms in React — rebuild Day 57's multi-step form |
| 69 | React Router — set up multi-page navigation (Home, About, Contact) |
| 70 | Nested routes and route params (e.g. `/product/:id`) |
| 71 | Context API — build a theme (light/dark) or auth context |
| 72 | Custom hooks — extract a `useFetch` hook from your API projects |
| 73 | Rebuild the Day 55 shopping cart in React using Context |
| 74 | Component library basics — build reusable Button, Input, and Card components |
| 75 | Form handling library (e.g. React Hook Form) — rebuild a form with it |
| 76 | Animations in React (e.g. Framer Motion) — animate a page transition |
| 77 | Connect to a real backend/database (e.g. Firebase or Supabase) — simple notes app |
| 78 | Authentication — add real sign-up/login using Firebase/Supabase auth |
| 79 | Deploy a React app (Vercel or Netlify) |
| 80 | **Review day** — refactor your biggest React project for cleaner component structure |

## Phase 5: Capstone Projects & Polish (Days 81–100)

| Day | Task |
|---|---|
| 81–85 | **Capstone 1**: Full e-commerce-style app — product listing, cart, checkout flow, auth (combine everything from Phases 3–4) |
| 86–90 | **Capstone 2**: Dashboard app — charts (e.g. Chart.js/Recharts), data tables, filters, dark mode |
| 91–93 | **Capstone 3**: Social feed clone — posts, likes, comments (static or real backend) |
| 94 | Accessibility pass — audit all 3 capstones with Lighthouse, fix contrast/alt-text/keyboard nav issues |
| 95 | Performance pass — audit load times, optimize images, lazy-load components |
| 96 | Mobile responsiveness pass — test all 3 capstones at 375px, 768px, 1024px+ |
| 97 | Write README files for your 3 capstone repos (screenshots, tech stack, how to run) |
| 98 | Build a portfolio site showcasing everything (or update an existing one) |
| 99 | Deploy everything, fix any last bugs |
| 100 | **Reflect** — write up what you learned, what you'd do differently, and pick your next challenge (TypeScript? Mobile with React Native? A CSS framework deep-dive?) |

---

## Notes on tools

- **Editor**: VS Code
- **Days 1–60**: plain HTML/CSS/JS — no framework needed, no build tools needed
- **Days 61+**: Vite + React is the lightest path in
- **Free APIs to keep bookmarked**: OpenWeatherMap, JokeAPI, REST Countries, OMDb (movies), JSONPlaceholder, ExchangeRate-API

## Optional: swap in mobile

If partway through you want to pivot into mobile, React Native reuses almost everything from Phase 4 (components, state, hooks) — you could swap Days 81–100 for a mobile capstone (e.g. rebuild Capstone 1 as a React Native app) instead of starting a separate 100-day track.