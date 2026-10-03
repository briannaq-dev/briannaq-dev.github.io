# briannaq-dev.github.io

My personal portfolio site, live at **[briannaq-dev.github.io](https://briannaq-dev.github.io)**.

It's a small static site with an overview of who I am and what I've worked on:

- **Home** (`index.html`): a short bio and my co-op and internship experience.
- **Projects** (`projects.html`): consulting and data projects, with the problem, my role and key contributions.
- **Contact**: links to GitHub, LinkedIn and email in the header, menu and footer.

## Design
- Built on the [Future Imperfect](https://html5up.net/future-imperfect) template by [HTML5 UP](https://html5up.net) (CC BY 3.0, see `LICENSE-template.txt`), with a green accent color and the content written as experience and project posts.
- Two pages, `index.html` (about and experience) and `projects.html` (consulting, software and data projects), in plain HTML using the template's CSS and JavaScript. No build step.
- Responsive layout with a slide-out menu on small screens.
- `images/headshot.jpg` is my profile photo (cropped, with metadata removed). `images/monogram.svg` is the favicon.

For code and project write-ups, see my [GitHub profile](https://github.com/briannaq-dev).

## Run locally
```
python -m http.server
```
Then open `http://localhost:8000`.

## Deploy
Hosted with GitHub Pages from the `main` branch.
