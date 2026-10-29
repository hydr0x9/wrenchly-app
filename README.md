# Wrenchly — first working build

Wrenchly is a mobile-first mechanic education app prototype built with plain HTML, CSS and JavaScript. It does not require a framework, paid API, database or account.

## Included
- Mobile-first dark interface
- 8 learning tracks and 13 starter lessons
- Lesson completion and progress tracking
- Knowledge quiz with answer feedback
- Three diagnostic practice cases
- Local progress saved in the browser
- Progressive Web App files for installability and offline caching

## Run it
1. Unzip this folder.
2. Open `index.html` in a browser to test the main app.
3. For install prompts and offline caching, serve it over HTTPS or localhost. Service workers do not run from ordinary `file://` URLs.

## Free hosting options
You can publish the folder using GitHub Pages, Cloudflare Pages or Netlify's free static hosting. HTTPS is required for installability and service workers. Hosting providers' free-tier terms can change.

## Install on a phone
- Android: open the hosted URL in Chrome, then choose “Install app” or “Add to Home screen”.
- iPhone: open the hosted URL in Safari, tap Share, then “Add to Home Screen”.

## Current limitations
- Progress is stored locally on that device/browser. It does not sync between devices.
- This is an educational starter, not a substitute for vehicle-specific service data or hands-on training.
- The included content is a foundation; advanced repair instructions, diagrams, sourced videos, accounts and formal qualification pathways should be added and reviewed before public launch.
- No native App Store / Google Play package is included yet. Store publication may involve developer account fees and additional build work.

## Suggested next milestones
1. Add original diagrams and more detailed lessons.
2. Add search, bookmarks and a glossary.
3. Add vehicle make/model/year selection and a reliable service-information source.
4. Add secure accounts and cloud sync if needed.
5. Package as a native app with Capacitor or React Native if store distribution is required.
