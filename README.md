# FUD Portal — Student Prototype

An independent educational UI project inspired by Federal University Dutse. This repository is not an official university service. Existing university branding, statistics, contact details, news, testimonials and academic claims have not been verified in this review.

## Run locally

Run `python -m http.server 8000` in this folder and open `http://localhost:8000`. No build step is required. External fonts, icons, images and animation scripts need internet access.

## Current limitations

The current HTML has no backend or real authentication. Its simulated login accepts arbitrary credentials and logs them to the browser console: **do not enter real usernames or passwords**. Newsletter and placeholder actions are demonstrations, not connected services. The HTML references a manifest and service worker that are not present in this repository.

## Repair status

Local repairs were tested for a credential-free demo dashboard, missing animation-library fallback, calendar navigation, theme storage, honest newsletter feedback and removal of missing PWA references. Publication of those HTML changes is pending approval because the page retains unverified university content. These fixes are not yet in the published HTML.

Before using this project beyond a local demonstration, replace or verify the institutional content and implement an authorized backend with appropriate access controls.
