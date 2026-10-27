# Socail Network Platform — "Mahber"

> Repo keeps its original (misspelled) name on purpose — see the folder/history, not this README title.

**Mahber** (Amharic: *ማህበር* — "community") is a **static HTML & CSS design prototype** of a social
platform aimed at campus & city life in Addis Ababa: meetups, messages, events, videos and saved posts.

## What it is — and what it honestly is not

- ✅ A fully designed, linkable prototype: 13 pages sharing one design system.
- ❌ No backend, no auth, no database, no build step, no framework.
- ❌ No accounts are ever stored; forms and buttons are visual/labelled as demo.

Everything you can click either navigates between pages or is intentionally labelled as demo-only.

## Pages

| File | Screen |
| --- | --- |
| `index.html` | Landing / honest marketing page (links to every screen) |
| `sign_in.html`, `signup.html`, `forgot_password.html`, `more_info.html` | Auth & onboarding (visual flow, demo-only) |
| `home.html` | Feed: stories rail, composer, sample posts, right sidebar |
| `your_profile.html` / `others_profile.html` | Profile screens with grid galleries |
| `message.html` | Chat list + conversation (stacks on mobile) |
| `saved.html` | Saved items grid |
| `calander.html` | Community calendar — static October 2026 month grid + event list |
| `video.html` / `video_player.html` | Video grid and player page |

## Design system

- `css/design-system.css` — single shared stylesheet.
- Identity: ink navy (`#16223d`) + warm coral (`#f2603c`), honey accent used sparingly.
- Type: system font stack (no remote fonts). Icons: inline SVG. Mobile menu: CSS checkbox hack.
- All imagery is local (`assets/images/`) — no hotlinked photos.

Run it by opening `index.html` in a browser, or deploy the folder as a static site (e.g. Vercel).
