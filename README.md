# DLeo Portfolio

A lightweight, mobile-friendly portfolio for DLeo projects and gaming interests. The site uses standalone HTML pages with no build step or third-party JavaScript dependencies.

## Preview locally

1. Open `index.html` in a browser, or use your editor's HTML preview.
2. Test the mobile navigation, light/dark theme toggle, section links, and the optional game trackers.
3. Save a tracker note, reload the page, and confirm it restores in the same browser.

## Publish with GitHub Pages

1. Open the repository on GitHub and select **Settings**.
2. Open **Pages** under **Code and automation**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. Wait for GitHub Pages to finish publishing; the Pages section will show the site URL.

If Pages is already enabled, commits to the configured branch/folder can update the published site automatically. A repository's public source URL is not itself the live website URL.

## Features

- Responsive layout and mobile navigation
- Light/dark theme toggle
- Keyboard focus styling and skip-to-content link
- Homepage, project directory, Bug Detective notes, and dedicated roadmap
- Project overview, responsible-use notes, and game links
- Optional game trackers stored locally in the current browser

## Privacy and limitations

The optional game tracker stores notes in the browser's local storage. The notes are not uploaded by this static page, but they may be unavailable in another browser or device and can be cleared by browser settings. Avoid saving sensitive information.

DLeo Bug Detective is described as an evolving project, not a complete security audit or a guarantee that a website is safe. Only assess websites you own or have permission to test.

## Manual verification baseline

Maintainer-reported browser checks passed on 2026-10-19:

- Keyboard-only navigation, visible focus, and keyboard activation
- Mobile menu Escape behavior and focus return
- Light/dark theme consistency and persistence across pages
- Readability of text, links, controls, and status messages in both themes
- Navigation, theme, and tracker save/clear checks in a second browser
- Direct loading and reloading of each HTML page
- Responsive layout, tracker validation, clear/reset controls, and graceful handling when browser storage is unavailable

These are manual test results, not an automated test suite. Repeat the relevant checks after changes. A successful GitHub source update does not by itself confirm that GitHub Pages has finished publishing the change; verify the live site separately.

## Project structure

- `index.html` — the portfolio homepage
- `projects.html` — the project directory
- `bug-detective.html` — Bug Detective scope, limitations, and development notes
- `roadmap.html` — development priorities and project planning
- `README.md` — this guide
