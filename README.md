# Emirates Airline Customer Service Online Interview Questions

A single-page, display-only web app that shows the online interview questions in order.
Questions 1 and 2 are free; Questions 3–6 and the Language Assessment section unlock
after payment. There are no answer fields — candidates record answers elsewhere.

## Files

- `index.html` — the entire app (HTML, CSS, and JavaScript in one file).
- `header-photo.jpg` — the header banner photo.

## How unlocking works

- The **Support the group** button opens the Stripe payment link.
- The **Show all questions** button reveals the hidden questions
  directly on the page via JavaScript (no redirect, no URL parameter, no backend).

## Deploy with GitHub Pages

1. Create a new GitHub repository and push these files to it.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Your site publishes at `https://<your-username>.github.io/<repo-name>/`.

Because everything is static and self-contained, it works in all modern browsers on
desktop and mobile with no build step.
