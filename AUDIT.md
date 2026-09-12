# FE-10 Accessibility Audit

## Scope
Mobile-first audit of the deployed preview, including the primary AI audit flow.

## Before scores
- Lighthouse mobile performance: 78
- Lighthouse mobile accessibility: 71
- WAVE errors: 7

## Changes made
- Added semantic header/main/section/footer structure and heading hierarchy.
- Added accessible names and labels for controls.
- Added visible `:focus-visible` styles.
- Used readable contrast for text and controls.
- Added responsive layout for narrow screens.
- Added keyboard-reachable Stop Audit control.
- Added `aria-live="polite"` for audit status updates.
- Added stable table/layout structure.
- Added table headers and row scopes.

## After scores
- Lighthouse mobile performance: 94
- Lighthouse mobile accessibility: 96
- WAVE errors: 0

> The before/after values above are placeholders for the evidence section. Replace them with the actual Lighthouse and WAVE results from the deployed URL before submitting.

## Verification checklist
1. Run Chrome DevTools Lighthouse with Mobile preset.
2. Run WAVE on the deployed URL and key pages.
3. Navigate the primary flow using Tab/Shift+Tab only.
4. Confirm focus is always visible.
5. Confirm the Stop Audit button is keyboard reachable while the audit is running.
6. Confirm the audit status is announced politely through the live region.
