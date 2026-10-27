# Local check summary

- Theme: One · Prism 0.1.1
- Manifest SHA-256: `a028c49543fef0cd4aa64b9bf9d4bbc66a146c18b9a87e63c5e2d747c67e295f`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 10.86:1, title 10.86:1, link 5.33:1, tag 5.86:1, code 9.77:1, mark 9.22:1, chosen 9.48:1.
  - Dark: body 6.57:1, title 6.57:1, link 5.92:1, tag 4.75:1, code 5.29:1, mark 5.02:1, chosen 5.36:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
