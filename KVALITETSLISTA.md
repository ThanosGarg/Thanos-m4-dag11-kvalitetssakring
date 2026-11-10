# Quality checklist (day 11)

Work through the list from top to bottom. Check off each item after verifying it.

## HTML

- [x] Validates at validator.w3.org without errors
- [x] `lang="sv"` is set on `<html>`
- [x] Exactly one `<h1>` per page
- [x] The heading hierarchy does not skip levels (h1, h2, h3)
- [x] Semantic elements are used (header, nav, main, section, article, footer)
- [x] No duplicate `id` values
- [x] All links lead somewhere (test them)

## Accessibility

- [x] All images have alt text describing the image
- [x] All form fields have an associated `label`
- [x] All buttons are `<button>` elements (not `<div>` elements)
- [x] All text meets a contrast ratio of 4.5:1
- [x] You can use the entire page with only the keyboard
- [x] Focus is always visible

## CSS

- [x] `box-sizing: border-box` is set
- [x] Colors and spacing come from variables
- [x] No unused or misspelled classes
- [x] Files are split up and named logically

## Responsiveness

- [x] No horizontal scrolling at 360 px
- [x] Works at 360, 768, and 1280 px
- [x] Images and form fields adapt to the available width

## Git and publishing

- [x] One commit per change, with clear messages
- [x] Everything has been pushed
- [x] The live site shows the latest version
