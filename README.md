# Chase Staples — Personal Site

A static personal portfolio site: home page, projects, dashboard, launchpad,
and a sign-in / one-time-code flow.

## Pages

- `index.html` — home / landing page
- `projects.html` — projects listing
- `dashboard.html` — dashboard view
- `launchpad.html` — launchpad view
- `login.html` / `otp.html` — sign-in demo flow

## Note on login / OTP

`login.html` and `otp.html` are a **front-end-only demo**, not a real
authentication system. There is no backend: form submission is handled
entirely in the browser with `sessionStorage`, and the "one-time code" is a
hardcoded demo value (`1234`). This means the flow works fine on static
hosting (GitHub Pages, etc.) as-is, but it does not represent real user
accounts, sessions, or security.

## Hosting

This is a fully static site (plain HTML/CSS/JS, relative paths only) and is
deployed via GitHub Pages.
