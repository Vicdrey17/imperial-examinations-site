# Phase 4 Testing Report

Date: 2026-11-15

## Content and assets

- All seven approved Part 1–7 Markdown files were copied into `content/` and SHA-256 compared against the canonical files in `History_Package/`. All seven matched exactly.
- All nine verified historical images loaded in the browser. The package also retains the supporting Kangxi source PDF.
- Every copied asset was SHA-256 compared against the original asset. All ten copied asset files (nine images plus the supporting PDF) matched byte-for-byte.
- The original Kangxi scans are used as foreground evidence and lightbox targets. They are not cropped, filtered, or modified.
- The Evidence 03 publication-date qualification, Evidence 04 approximately 1% qualification, and Evidence 05 damaged-scan qualification appear in the rendered Evidence Trail.

## Functional checks

- Desktop Explore menu: opened and navigated to Part 4.
- Mobile navigation: opened and navigated to Part 5.
- Evidence card: Evidence 01 expanded and displayed its complete source, interpretation, connection, and limitation.
- AI Audit comparison: Claim 1 expanded and displayed its complete audit.
- Historical document lightbox: PDF page 320 opened with its caption and keyboard-focusable close control.
- Active navigation indicator: showed Part 5 while that section was active.
- Browser console: no warnings or errors.

## Accessibility and responsive checks

- Semantic landmarks, heading hierarchy, image alternative text, labelled navigation, skip link, visible keyboard focus styles, and accessible expanded/collapsed states are present.
- At a 390 × 844 mobile viewport, the mobile navigation exposed Home, all seven parts, and References; the section link closed the menu after navigation.
- Reduced-motion styles disable transitions and smooth scrolling for visitors who request it.

## Local preview

Run `node server.js` in this directory and open `http://127.0.0.1:8765`.

No deployment or publication was performed.
