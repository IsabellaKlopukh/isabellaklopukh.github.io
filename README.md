# Isabella Klopukh — research website

A responsive academic website for GitHub Pages. Plain HTML and CSS; no build step, dependencies, analytics, or external fonts.

## Publish on GitHub Pages

1. Sign in to **IsabellaKlopukh** on GitHub.
2. Create a public repository named **IsabellaKlopukh.github.io**. If it already exists, inspect and preserve its contents before updating it.
3. Upload the contents of this folder to the repository's `main` branch, with `index.html` at the root (not inside another folder).
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then `main` and `/(root)`, and Save.
5. Once deployment finishes, visit **https://isabellaklopukh.github.io/** and check that the page loads before adding that link to an application.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Update the site

Edit `index.html` for text, publications, and presentations; edit `styles.css` for appearance. Changes committed to the publishing branch are automatically republished.

Keep published papers distinct from manuscripts in preparation, submitted papers, and accepted papers. Add coauthors, dates, venues, and public links only when confirmed. Research topic descriptions do not claim results or publication status.

To add an updated public CV, place a reviewed PDF named `cv.pdf` in this folder and add a link to it in the navigation. Review contact information and document metadata before uploading a CV.

## Preview locally

Run `python3 -m http.server 8765 --bind 127.0.0.1` from this folder, then open http://127.0.0.1:8765/. You can also open `index.html` directly in a browser.
