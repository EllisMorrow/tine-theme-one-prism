# Adaptation notes

Based on the official Atom One Light and One Dark syntax theme repositories at fixed revisions d84579027410c576086dfca14d934c4bd74b0438 and 9c96f4454362267ac45322063e193ccf9d2debb1. Color roles are independently mapped to the Tine theme API.

## Sources

- darkPalette: https://github.com/atom/one-dark-syntax/tree/9c96f4454362267ac45322063e193ccf9d2debb1
- lightPalette: https://github.com/atom/one-light-syntax/tree/d84579027410c576086dfca14d934c4bd74b0438
- licenseDark: https://github.com/atom/one-dark-syntax/blob/9c96f4454362267ac45322063e193ccf9d2debb1/LICENSE.md
- licenseLight: https://github.com/atom/one-light-syntax/blob/d84579027410c576086dfca14d934c4bd74b0438/LICENSE.md

## Mapping decisions

- The light mode is based on the official One Light syntax theme and the dark mode on official One Dark; both repositories carry the same MIT notice.
- Tine surface tiers, selected-block backgrounds, borders, guides and marks are semantic adaptations around the upstream neutral canvases.
- Text, links, tags and accent roles are mapped to the One palette; the Tine API does not control fonts, task markers, arbitrary hover rules or all syntax colors.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
