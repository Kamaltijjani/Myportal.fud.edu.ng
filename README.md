# FUD Portal — Student Prototype

An independent educational UI project inspired by Federal University Dutse. **This is not the official university portal.** Campus statistics, testimonials, courses and dashboard records are demonstration content.

## Run locally

Run `python -m http.server 8000` in this folder and open `http://localhost:8000`. No build step is required.

## Working demo features

- Responsive navigation and theme toggle (saved locally when browser storage is available).
- A calendar with previous/next month navigation.
- Testimonial rotation and animated counters.
- A demo dashboard opened with an optional display name; no password is collected.

## Limitations

There is no backend, real authentication, registration, payments, results system or newsletter service. Placeholder links state that the feature is not connected. The newsletter does not send or save subscriptions. PWA support is not configured; references to missing manifest/service-worker files have been removed.

Fonts, icons, images and AOS load from external services. If AOS fails, local interactions continue and animated sections remain visible.

Do not use this prototype to collect student credentials or personal records. Production use requires a properly authorized backend, access controls and verified university content.
