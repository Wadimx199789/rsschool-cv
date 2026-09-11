# Martinkevich Vadim

_Frontend engineer_

## Contacts

- **Email:** [martinkewichwadim@gmail.com](mailto:martinkewichwadim@gmail.com)
- **Phone:** [+375 (33) 635-38-01](tel:+375336353801)
- **Telegram:** [@volandmironovich](https://t.me/volandmironovich)
- **LinkedIn:** [wadim-martinkevich](https://www.linkedin.com/in/wadim-martinkevich-05899919b/)
- **GitHub:** [Wadimx199789](https://github.com/Wadimx199789)
- **Location:** Minsk, Belarus

---

## Professional Summary

Product-focused Frontend engineer with 4+ years of commercial experience building modern, high-performance web applications on Vue 3 and TypeScript, with production experience in React.

I have strong expertise in adaptive, semantic, and accessible markup, and I've worked extensively on complex UI implementations — including building client-side logic similar to ChatGPT interfaces, where handling dynamic content rendering, streaming data, and user interaction patterns is critical.

I’m experienced in developing both individual features and full products, collaborating in agile teams or leading parts of a project from scratch.

I’m passionate about clean code, modular architecture, smooth UX.

---

## Technical Skills

- 🛠 **Core Stack:** Vue 3, TypeScript, Tailwind CSS, Vite, Pinia, Vuex
- 🏗 **Architecture:** Feature-Sliced Design (FSD), component-driven development, BEM
- ⚛️ **React Stack:** React, Next.js, Redux, Redux Toolkit (RTK), MobX
- 🔄 **Data Fetching:** TanStack Query (React Query), RTK Query, Axios, WebSocket
- 📐 **UI Expertise:** Advanced layout (semantic HTML, accessibility, responsiveness), streaming content rendering, real-time UI interactions, ChatGPT-like client UIs
- 📊 **Analytics & Experimentation:** A/B testing, feature flags (GrowthBook, Amplitude)
- 💳 **Payment Integrations:** Stripe, Paddle, PayPal, Apple Pay
- 💻 **Languages & Styling:** JavaScript, TypeScript, SCSS/SASS, LESS
- 🖥 **Backend:** Node.js, Next.js API routes, REST
- 🗄 **Databases & BaaS:** PostgreSQL, MySQL, MongoDB, Firebase
- ⚙️ **Build & CI:** Vite, Webpack, Gulp, Git, GitHub, GitLab, CI/CD
- 🔌 **API Tooling:** Postman, Swagger
- 🎨 **Design Handoff:** Figma, Zeplin
- 🧩 **Also worked with:** Svelte, Svelte stores

---

## Professional Experience

### Software Engineer · PrimeTech Apps

_Apr 2026 — Present · Minsk, Belarus_

Building [ChatbotGo](https://app.chatbotgo.ai/), an AI assistant web application, as part of the team behind Chatbox.

- Develop the product front end in React and TypeScript, structuring the codebase with Feature-Sliced Design (FSD) so features stay isolated and reusable as the app grows.
- Implement the conversational interface — streaming assistant responses, markdown and code rendering, conversation history and model switching.
- Design the client-side data layer with Redux Toolkit and TanStack Query, keeping request state, caching and error handling predictable across the app.
- Build subscription and payment flows, connecting checkout to the product's paywall and access levels.
- Instrument features with analytics and feature flags, shipping changes behind A/B tests rather than releasing them blind.

### Instructor · STEP IT Academy

_Aug 2022 — Present · Minsk, Belarus · Part-time_

Teaching web development alongside commercial work.

- Teach web development courses covering JavaScript, React and Node.js, guiding students through the technologies behind modern web applications.
- Create structured, up-to-date curricula, assignments and worked examples that connect theory to practical skills.
- Run hands-on projects where students build real web applications and apply development, testing and deployment practices.
- Assess progress through practical assignments, code reviews and exams, giving feedback students can act on.
- Mentor students one-on-one, helping them unblock and work through problems in their own projects.

### Frontend Developer · AIBY

_May 2022 — Apr 2026 · Minsk, Belarus_

AI product company. Worked across consumer AI products — [Chatbox](https://app.chatbox.ai/), [ChatOn](https://chaton.ai/) and [OnSkin](https://onskin.com/).

- Key front-end developer on Chatbox: led the web application from initial concept, built the MVP from scratch and designed its core architecture around Feature-Sliced Design, which kept the codebase maintainable as the product grew into new features.
- Built the chat interface itself — streaming assistant responses rendered token by token, live markdown and code-block formatting, message history and recovery from dropped connections.
- Led the front-end integration of Amplitude and GrowthBook — SDK implementation, event tracking and a reusable framework for A/B tests and feature flags that the product team ran experiments on.
- Integrated payment gateways — Stripe, PayPal, Paddle and Apple Pay — covering checkout flows, transaction states and error handling.
- Developed and maintained the company's public-facing websites and built high-conversion payment landing pages for marketing campaigns.
- Optimised application performance and implemented SEO practices, cutting page load times and improving Core Web Vitals.
- Maintained code quality across the team through regular code reviews and shared development standards.
- Collaborated in a cross-functional team of product managers, designers, back-end developers and QA engineers to deliver on the product roadmap.

### Full Stack Engineer · Nova English Startup

_Apr 2024 — Jan 2025 · Remote (USA) · Part-time_

EdTech startup building an online English-learning platform. Owned features end-to-end, from UI to the API layer behind it.

- Developed the product interface in React and Next.js with TypeScript, building reusable components for lessons, exercises and student progress views.
- Implemented server-side rendering and API routes in Next.js, covering data fetching, caching and authenticated user sessions.
- Designed client-side state and data flow with Redux Toolkit and TanStack Query, keeping learning sessions responsive on slow connections.
- Built real-time interactive parts of the learning flow, handling streaming responses and optimistic UI updates.
- Shipped features directly with the founder in a small distributed team, taking tasks from idea to production release.

### Frontend Developer · Design lab

_Feb 2022 — Sep 2022 · Minsk, Belarus_

Web studio projects: landing pages, corporate and promo sites delivered from design mock-ups to production.

- Built responsive, pixel-perfect layouts from Figma and PSD mock-ups with semantic HTML5, SCSS and vanilla JavaScript, following the BEM methodology.
- Adapted layouts across mobile, tablet and desktop breakpoints and resolved the cross-browser rendering issues that came with them, most often in Safari and Edge.
- Developed interactive UI components — sliders, modals, tabs, accordions, scroll-driven animations and forms with client-side validation.
- Integrated layouts with CMS templates and connected forms to backend endpoints, handling loading, success and error states.
- Optimised page load through image compression, lazy loading and asset bundling with Gulp and Webpack.
- Worked in Git flow with feature branches and code review, iterating on designer and client feedback under studio deadlines.

---

## Code Example

Binary search over a sorted array — O(log n) lookup.

```ts
export function binarySearch(items: number[], target: number): number {
  let low = 0;
  let high = items.length - 1;

  while (low <= high) {
    const mid = low + Math.floor((high - low) / 2);
    const value = items[mid];

    if (value === target) return mid;

    if (value < target) {
      low = mid + 1;
    } else {
      high = mid - 1;
    }
  }

  return -1;
}
```

---

## Education

### Bachelor's Degree · Belarusian State University of Informatics and Radioelectronics (BSUIR)

_2015 — 2020 · Faculty of Radioengineering and Electronics · Minsk, Belarus_

---

## Additional Information

**Languages:** Russian (Native), English (B1 — Intermediate)
