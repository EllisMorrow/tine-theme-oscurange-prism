# Local check summary

- Theme: Oscurange · Prism 0.1.1
- Manifest SHA-256: `146947ed030e65c4cc7f455244f341308e2a3ebac32ba5073283d42601e6089f`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 10.32:1, title 10.32:1, link 5.06:1, tag 5.06:1, code 9.42:1, mark 9.81:1, chosen 9.79:1.
  - Dark: body 15.74:1, title 15.74:1, link 11.55:1, tag 11.55:1, code 14.32:1, mark 12.79:1, chosen 12.49:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
