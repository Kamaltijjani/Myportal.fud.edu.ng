# FUD Portal — Student Prototype

An independent educational UI project inspired by Federal University Dutse. **This is not the official university portal.** Existing university branding, statistics, contact details, news, testimonials and academic claims have not been independently verified. Dashboard records are fictional demonstration content.

## Run locally

Run `python -m http.server 8000` in this folder and open `http://localhost:8000`. No build step is required. External fonts, icons, images and animation scripts need internet access.

## Demo features

- Responsive navigation and a theme toggle, with storage fallback.
- Calendar with previous/next month navigation.
- Testimonial rotation and animated counters.
- A demo dashboard opened with an optional display name; no password is collected.
- Clear feedback for placeholder actions and the unconnected newsletter form.

## Published repairs and validation

The demo dashboard, missing animation-library fallback, calendar navigation, theme toggle, logout and newsletter feedback passed local simulated DOM interaction checks. Broken references to missing manifest/service-worker files were removed. These checks do not constitute full visual, accessibility or production testing.

## Limitations

There is no backend, real authentication, registration, payments, results system or newsletter delivery. No installable PWA support is configured. Do not use this prototype to collect real credentials or student records. Production use requires verified institutional content, authorization, backend services and appropriate access controls.
