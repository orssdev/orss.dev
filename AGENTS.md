## Design principles

Design and build mobile-first: base (unprefixed) Tailwind classes target small screens, and larger viewports are layered on with `sm:`/`md:`/`lg:` breakpoints — never the other way around. Every new section or component must be usable and legible at a ~375px width (touch targets, spacing, font sizes) before any desktop-only enhancement is added. Desktop should still feel intentional, not just a stretched mobile layout — use the larger breakpoints to add multi-column layouts, larger type, and wider spacing where it improves the experience.

## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)
