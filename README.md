# McManus Legacy Group — website

Static single-page site. `index.html` is self-contained (3D scene, logo, and fonts are inlined); no build step.

## Deploy (Netlify via GitHub)
- Build command: _leave empty_
- Publish directory: `.`

Netlify redeploys automatically on every push to the default branch.

## Contact form
The form posts to FormSubmit, which forwards submissions to the address in the `<form action>` attribute. The first submission after launch triggers a one-time confirmation email to that address — click the link to activate forwarding.
