# HCI Fisheye Heuristics Webpage

An interactive Human Computer Interaction webpage that presents Jakob Nielsen's 10 usability heuristics through a polished fisheye dock interface.

The project was created from the HCI group work brief, which asked for accurate heuristic content, improved overlay text, real icons, better visual design, smooth fisheye interactions, click support, responsiveness, and keyboard accessibility.

## Live Files

- `index.html` - main webpage entry point for GitHub Pages or browser preview.
- `hci_fisheye_heuristics.html` - same webpage kept under the original project filename.

## What It Includes

- All 10 Nielsen usability heuristics, labeled `UH#1` through `UH#10`.
- Accurate definitions and short learning takeaways for each heuristic.
- A fisheye-style icon dock with hover and focus magnification.
- Neighbor item scaling for a smoother dock effect.
- Click selection so an item can stay open after hover.
- Real Font Awesome icons instead of emojis.
- A readable detail overlay panel with the selected heuristic, definition, and practical notes.
- Responsive layout for desktop, tablet, and mobile screens.
- Keyboard support with `Tab`, arrow keys, `Home`, `End`, `Enter`, and `Space`.
- Accessible labels, focus states, and live updates for the selected content.
- Reduced-motion support for users who prefer less animation.

## HCI Roles Covered

### Content and Heuristics Specialist

- Verified the 10 heuristics against Nielsen's standard usability heuristic set.
- Rewrote overlay content so each item is concise but useful for learning.
- Kept labels short enough to fit visually in the dock and detail panel.

### Visual and UI Designer

- Replaced emoji placeholders with Font Awesome icons.
- Added a clean visual system with color accents, shadows, borders, and readable spacing.
- Designed the detail overlay so the selected heuristic is easy to scan.
- Added smooth hover, focus, and active states.

### Interaction and Frontend Developer

- Added click support in addition to hover behavior.
- Added keyboard navigation and visible focus states.
- Implemented responsive behavior for smaller screens.
- Integrated content, layout, animation, and accessibility in one standalone HTML file.

## How To Open Locally

Open `index.html` directly in a browser, or serve the folder locally:

```powershell
cd "C:\Users\User\Documents\hci_fisheye_heuristics_repo"
python -m http.server 4173
```

Then visit:

```text
http://127.0.0.1:4173/index.html
```

## Verification

The webpage was checked in the browser at:

```text
http://127.0.0.1:4173/hci_fisheye_heuristics.html
```

Verified behavior:

- All 10 dock items render.
- `UH#10` content is present.
- Clicking `UH#7` updates the detail panel and selected counter.
- No browser console errors were found during the interaction check.

## Technologies

- HTML
- CSS
- JavaScript
- Font Awesome icons
- Google Fonts

## GitHub Repository

Repository:

```text
https://github.com/Costa-git001/hci_fisheye_heuristics.html
```
