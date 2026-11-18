# Jarvis Edu Portal

An ambitious, free-first online learning platform for academics, JEE, NEET, UPSC, coding, AI, programming, and foreign languages.

## What's here

This repository currently contains a responsive, static website prototype:

- `index.html` — landing page, course catalog, learning paths, AI tutor preview, and footer.
- `styles.css` — responsive visual design for desktop and mobile.
- `app.js` — course filtering/search, course preview, navigation, and a sample chatbot.

## Run locally

No build tools are required. Open `index.html` in a browser, or serve this directory with any static web server, for example:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Important: prototype limitations

The course cards are sample catalog data; they do not contain full lessons or enrollment. The chatbot uses a small set of built-in example responses and is **not connected to a live AI model**. Authentication, saved progress, quizzes, admin tools, and student records are not implemented. Never put AI provider secrets in browser JavaScript. A production AI tutor should use a secure server-side API, sourced course materials, privacy controls, and appropriate safeguards. Add a database and authentication backend before storing learner data.

All course listings in this prototype are marked free. Hosting, AI inference, and content creation can still have operating costs; a sustainable free service needs a funding and usage plan.

## Publish

The site can be hosted as static content using GitHub Pages: in the repository settings, enable Pages and select the `main` branch and `/ (root)` as the source. GitHub Pages may take a few minutes to publish; its settings page displays the final URL.
