# McManus Legacy Group — website

Static multi-page site. Each page is a self-contained HTML file (logo and fonts are inlined); no build step.

Pages: `/` (home), `/about/`, `/services/`, `/clients/`, `/credentials/`, `/careers/`, `/contact/`. Every page carries its own copy of the header, menu and footer, so a change to those must be made in each page's `index.html`. Old one-page links such as `/#careers` forward to the matching page.

## Deploy (Netlify via GitHub)
- Build command: _leave empty_
- Publish directory: `.`

Netlify redeploys automatically on every push to the default branch.

## Contact form
The form posts to FormSubmit, which forwards submissions to the address in the `<form action>` attribute. The first submission after launch triggers a one-time confirmation email to that address — click the link to activate forwarding.
