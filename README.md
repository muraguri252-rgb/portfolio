# Samuel Muraguri — Personal Portfolio

A responsive personal portfolio built with plain HTML, CSS, and JavaScript. It has no build step or package dependencies.

## Run in VS Code

1. Open this folder in VS Code.
2. Open `index.html` in a browser. For live reload, install the **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.

The site also works by opening `index.html` directly in a modern browser.

## Personalize before publishing

- **Profile image:** Replace `assets/profile-placeholder.png` with your own PNG image and update its `alt` text in `index.html`.
- **Email:** Replace `your.email@example.com` in `index.html` and `scripts/main.js` with your real email. The contact form uses the visitor’s configured email app; it does not send or store messages on a server.
- **Social links:** Replace `your-username` in the GitHub and LinkedIn links in `index.html`.
- **Projects:** Add real project cards, screenshots, descriptions, and repository URLs in the Projects section of `index.html`. The current empty state is intentional because no project details were provided.
- **Skills:** Adjust the skills, qualitative labels, and progress-bar `--level` values in `index.html` to reflect your current self-assessment.
- **CV:** The hero includes a downloadable text CV at `assets/samuel-muraguri-cv.txt`, written only from the details provided. Update it with your contact details and any verified experience, projects, or achievements before sharing it with employers.
- **Search preview:** Update the description, page title, and Open Graph details in the `<head>` of `index.html` when you customize the site.

## Project structure

```text
assets/
  favicon.svg
  profile-placeholder.png
scripts/
  main.js
styles/
  style.css
index.html
README.md
```
