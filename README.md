# Moemen Mohamed — Portfolio

Personal portfolio website for **Moemen Mohamed**, a Computer Science student focused on **Cybersecurity** and **Network Engineering**.

**Live site:** [https://moemenshendia0-tech.github.io/portfolio/](https://moemenshendia0-tech.github.io/portfolio/)

## Features

- Responsive layout (mobile & desktop)
- Light / dark theme with saved preference
- Sections: Home, About, Skills, Experience, Projects, Certificates, Contact
- Contact form via [FormSubmit](https://formsubmit.co/)
- Downloadable CV
- Certificate gallery with modal preview

## Tech Stack

- HTML5
- CSS3 (custom properties, flex/grid)
- Vanilla JavaScript (no build step)
- [Google Fonts — Outfit](https://fonts.google.com/specimen/Outfit)

## Project Structure

```
portofolio/
├── index.html          # Main page
├── styles.css          # Styles & themes
├── script.js           # Theme, nav, animations, certificates
├── assets/
│   ├── CV.pdf          # Resume (Download CV button)
│   ├── images/         # Profile & project images
│   └── README.txt      # Asset notes
└── README.md
```

## Local Development

No install required. Open the project in a browser:

1. Clone the repository.
2. Open `index.html` in your browser, or use a local server, for example:

   ```bash
   npx serve .
   ```

## Deploy on GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** to deploy from the `main` branch (root `/`).
4. Ensure the repository or Pages path matches your live URL (e.g. `portfolio`).

Update the FormSubmit redirect in `index.html` if your Pages URL changes:

```html
<input type="hidden" name="_next" value="https://moemenshendia0-tech.github.io/portfolio/">
```

## Customize

| What | Where |
|------|--------|
| Profile photo | `assets/images/moe.jpeg` (paths in `index.html`) |
| CV file | `assets/CV.pdf` |
| Certificates | `.certificate-card` links in `index.html` |
| Projects & copy | `index.html` |
| Colors & theme | CSS variables in `styles.css` (`:root`) |

## Contact

- **Email:** [moemen.mohamed.it@gmail.com](mailto:moemen.mohamed.it@gmail.com)
- **LinkedIn:** [linkedin.com/in/moemen-shendia](https://www.linkedin.com/in/moemen-shendia)
- **GitHub:** [github.com/moemenshendia0-tech](https://github.com/moemenshendia0-tech)

## License

© Moemen Mohamed. All rights reserved.
