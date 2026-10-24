# Ayesha — Personal Developer Portfolio

A responsive, static portfolio built with HTML5, CSS3, and vanilla JavaScript. No build step or framework is required.

## Files

- `index.html` — page content, SEO metadata, project case studies, experience, contact links
- `assets/css/style.css` — responsive dark navy + cyan design system
- `assets/js/main.js` — accessible mobile navigation, reveal effects, active section links, current year
- `assets/images/profile-placeholder.svg` — replaceable portrait placeholder
- `assets/images/favicon.svg` — browser icon

## Before publishing

1. Replace the placeholder portrait with your own professional photo. For best performance, use a compressed WebP or AVIF image.
2. Update your actual LinkedIn profile URL in `index.html` (search for `https://www.linkedin.com/`).
3. Review all experience details and ensure dates and responsibilities are accurate.
4. The project cards are case-study templates. Replace descriptions with work you actually did and are allowed to show. Do not publish confidential employer/client details.
5. If you have public project URLs or GitHub repositories, add them only when they are real and safe to share.
6. The contact button currently opens the visitor's email app using `mailto:`. It does not store or send form submissions through a server.
7. Update the canonical URL and sitemap if you add a custom domain. A canonical URL is intentionally omitted because the final domain is not yet known.
8. Keep `og:image` in the metadata pointed to a suitable share image after replacing the placeholder.

## Preview locally

Open `index.html` in a modern browser. For a local server, run one of these from this folder:

### Python
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

### VS Code
Install/use Live Server and choose **Open with Live Server**.

## Deploy to Vercel

1. Create a Git repository and push this folder.
2. Import the repository in Vercel.
3. Choose **Other** as the framework preset if asked.
4. Leave build command and output directory empty/default for a plain static site, or set the root directory to this project folder if it is nested.
5. Deploy. No environment variables are required.

## Deploy to GitHub Pages

1. Push the folder to a GitHub repository.
2. In repository **Settings → Pages**, select the branch and root folder.
3. Save and wait for the deployment URL.
4. Test mobile navigation, email link, section anchors, images, and social preview.

## Accessibility and motion

- Keyboard skip link and visible focus styles are included.
- Mobile navigation exposes `aria-expanded` and can be closed with Escape.
- Reveal animations respect `prefers-reduced-motion`.
- The site remains readable without JavaScript; only interactive navigation/reveal behavior depends on it.

## Contact details

The contact email currently uses `brightcodeinc@gmail.com` as a professional contact address. Change it if you want a separate personal email.
