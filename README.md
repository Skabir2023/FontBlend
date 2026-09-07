# FontBlend — Free Font Pairings & Typography Tools

**FontBlend** is a free, browser-based typography toolkit at [fontblend.com](https://fontblend.com). It helps designers, developers, and content teams pick fonts, build font pairings, check color contrast, generate type scales, and export production-ready CSS — all without an account, without uploads, and without AI guessing what looks good.

> **FontBlend is a 100% static website.** Every tool runs entirely in your browser. Nothing you type, paste, or upload ever leaves your device. This repository exists to document the project and point you to the live tools — it intentionally contains no source code.

**Website:** [https://fontblend.com](https://fontblend.com)
**Contact:** [hello@fontblend.com](mailto:hello@fontblend.com)
**Report an issue or suggest a font:** [Open an issue on GitHub](https://github.com/Skabir2023/FontBlend/issues)

---

## Why FontBlend?

Most font tools fall into one of two camps: galleries that show static screenshots, or generators that produce random combinations and call it a day. FontBlend takes a third path — a **deterministic, designer-authored toolkit**:

- **Curated, not generated.** Every font pairing in the library was chosen by a designer and evaluated for readability, weight balance, and real-layout use. Nothing is auto-generated.
- **Live previews.** Fonts are loaded and rendered in your browser, so what you see is what ships.
- **Contrast scores built in.** Pairings and palettes come with WCAG 2.2 AA/AAA contrast data, not vibes.
- **Production-ready export.** Copy-ready CSS, Tailwind config, SCSS variables, JSON design tokens, and Markdown — one click, no signup.
- **Private by design.** No accounts, no analytics on your work, no server-side storage. Favorites and brand kits live in your browser's local storage under the `fontblend:v1:*` namespace and never leave your device.

## Start Here

| Page | What you'll find |
| --- | --- |
| [Font Pairings](https://fontblend.com/font-pairings/) | 50 curated font pairings with designer notes, contrast scores, and CSS export |
| [Font Catalog](https://fontblend.com/fonts/) | 38 open-source fonts (OFL / Apache licensed) with live previews, weights, and pairing suggestions |
| [Typography Playground](https://fontblend.com/playground/) | Test any font combination on a real layout before you commit |
| [Color Palettes](https://fontblend.com/colors/) | 14 curated color palettes, each with WCAG contrast data |
| [CSS Gradients](https://fontblend.com/gradients/) | 12 OKLCH-interpolated gradients — no muddy midpoints |
| [All Tools](https://fontblend.com/tools/) | The full toolkit index |

## Font Pairing Tools

- **[Font Pairing Generator](https://fontblend.com/font-pairing-generator/)** — Walks every heading and body font in the catalog, scores each pair across six weighted factors, and returns the top six. Fully deterministic: no machine learning, no embedding models, no API calls.
- **[Pairing Compare](https://fontblend.com/compare/)** — Put two pairings side by side and compare contrast, x-height balance, and mood.
- **[Font Matrix](https://fontblend.com/font-matrix/)** — Scan the whole catalog at a glance to find fonts that pair well together.

## Type Scale & Rhythm Tools

- **[Type Scale Calculator](https://fontblend.com/type-scale/)** — Static modular scales with a choice of ratio, previewed on real text.
- **[Fluid Typography Generator](https://fontblend.com/fluid-type/)** — Fluid `clamp()`-based type scales, step by step, with copy-ready CSS.
- **[Line Height Calculator](https://fontblend.com/line-height/)** — Compute accessible line heights from font size and x-height.
- **[Letter Spacing Tool](https://fontblend.com/letter-spacing/)** — Track and kern headings with live optical feedback.
- **[Spacing Scale Generator](https://fontblend.com/spacing-scale/)** — Build a consistent spacing system for margins and padding.
- **[Type Hierarchy Preview](https://fontblend.com/type-hierarchy/)** — See how display, heading, and body sizes work together on one page.
- **[Vertical Rhythm Calculator](https://fontblend.com/vertical-rhythm/)** — Baseline grids and rhythm-safe spacing for editorial layouts.
- **[Responsive Type Preview](https://fontblend.com/responsive-type/)** — Check how your type holds up from mobile to desktop widths.
- **[Readability Preview](https://fontblend.com/readability-preview/)** — Measure reading comfort: measure, line length, and paragraph density.
- **[Widows & Orphans Checker](https://fontblend.com/widows-orphans-checker/)** — Catch typographic orphans before your readers do.

## Color & Contrast Tools

- **[WCAG Contrast Checker](https://fontblend.com/contrast-checker/)** — AA and AAA pass/fail for normal and large text, with accessible variant suggestions.
- **[Contrast on Images](https://fontblend.com/contrast-on-image/)** — Test text contrast directly over photos and gradients.
- **[Color Palette Generator](https://fontblend.com/colors/)** — 14 curated palettes with contrast data for every pairing of foreground and background.
- **[Color Palette from Image Extractor](https://fontblend.com/color-extractor/)** — Pull a working palette out of any image, in your browser.
- **[CSS Gradient Generator](https://fontblend.com/gradients/)** — OKLCH-interpolated gradients with copy-ready CSS.

## Font Inspection & Testing Tools

- **[Variable Font Tester](https://fontblend.com/variable-fonts/)** — Play with weight, width, and optical size axes on every variable font in the catalog.
- **[OpenType Feature Tester](https://fontblend.com/opentype-tester/)** — Toggle ligatures, small caps, alternates, and tabular figures live.
- **[Font Inspector](https://fontblend.com/font-inspector/)** — Inspect metadata, axes, and features of catalog fonts.
- **[Font Weight Tester](https://fontblend.com/weight-tester/)** — Compare weights side by side to pick the right optical balance.
- **[Font Fallback Previewer](https://fontblend.com/font-fallback-previewer/)** — See what renders when your webfont fails to load.
- **[Font Coverage Checker](https://fontblend.com/font-coverage/)** — Check which languages and glyphs a font actually covers.
- **[Font Size Converter](https://fontblend.com/font-size-converter/)** — Convert between px, pt, em, rem, and physical units.
- **[Text Measure Tool](https://fontblend.com/measure/)** — Find the optimal line length (in ch units) for any font size.

## Brand & Export Tools

- **[Brand Kit Builder](https://fontblend.com/brand-kit/)** — Combine fonts, palette, and type scale into one exportable design system.
- **[Export Everything](https://fontblend.com/export-everything/)** — CSS, SCSS, Tailwind, JSON design tokens, and Markdown from any tool.
- **[Design Token Diff](https://fontblend.com/token-diff/)** — Compare two design-token files and see exactly what changed.
- **[Shareable Brand Board](https://fontblend.com/brand-board/)** — Package fonts, colors, and type styles into a link you can share.
- **[Brand Extractor](https://fontblend.com/brand-extractor/)** — Extract fonts and colors from any website via a bookmarklet — server-free.
- **[Font Embed Generator](https://fontblend.com/font-embed/)** — Generate `<link>` and `@font-face` snippets for Google Fonts.
- **[Typographic Poster Maker](https://fontblend.com/typographic-poster/)** — Design a print-ready typographic poster in the browser.
- **[Font Stack Generator](https://fontblend.com/font-stack/)** — Build resilient system-font fallback stacks.

## Learning & Discovery

- **[Typography Glossary](https://fontblend.com/typography/glossary/)** — 25 plain-English definitions, from apex to x-height, each linked to the tool where the term matters.
- **[Best Fonts For…](https://fontblend.com/best-fonts-for/)** — Curated picks by use case: SaaS, blogs, portfolios, resumes, e-commerce, and more.
- **[Best Fonts for Websites](https://fontblend.com/best-fonts-for-websites/)** — Web-safe picks organized by project type.
- **[Fonts for Logos](https://fontblend.com/fonts-for-logos/)** — Wordmark-friendly fonts that stay readable at small sizes.
- **[Script & Handwriting Fonts](https://fontblend.com/script-and-handwriting-fonts/)** — When (and when not) to use script faces.
- **[Font Categories Guide](https://fontblend.com/font-categories-guide/)** — Sans, serif, slab, display: what each category is actually for.
- **[Font Alternatives](https://fontblend.com/font-alternatives/)** — Free, open-source substitutes for commercial fonts like Helvetica, Gotham, and Futura — with live side-by-side previews.
- **[Typography Books](https://fontblend.com/typography-books/)** — A short, opinionated reading list.
- **[External Typography Tools](https://fontblend.com/typography-tools/)** — An honest directory of tools we don't build, evaluated for pricing and privacy.
- **[Blog](https://fontblend.com/blog/)** — Practical typography articles: pairing rules, fluid type tutorials, WCAG 2.2 changes, and more.

## Just for Fun & Utility

- **[Kerning Game](https://fontblend.com/kerning-game/)** — Train your eye by fixing real kerning pairs.
- **[Typography Checker](https://fontblend.com/typography-checker/)** — Paste text and get a typographic health report.
- **[Text Spacing Checker](https://fontblend.com/text-spacing-checker/)** — Verify your spacing meets WCAG 2.2 text-spacing requirements.
- **[Favorites & Scrapbook](https://fontblend.com/favorites/)** — Save fonts, pairings, and palettes locally. No account needed — data stays in your browser.

## What FontBlend Is Not

- **Not an AI generator.** Pairing scores come from transparent, weighted heuristics written by designers — you can reason about every recommendation.
- **Not a font marketplace.** FontBlend links to each font's original source and license; it never redistributes font binaries.
- **Not a SaaS.** There is nothing to sign up for, and there are no tiers. Every tool is free and complete.
- **Not a data collector.** No analytics on your work, no accounts, no server-side storage. Local storage only.

## Privacy & Licensing

- **Privacy:** FontBlend has no accounts, no server-side storage, and no tracking of the fonts or colors you work with. Details in the [Privacy Policy](https://fontblend.com/privacy/).
- **Fonts:** Every font in the catalog keeps its original [SIL Open Font License](https://openfontlicense.org/) or Apache license. See the [Terms of Use](https://fontblend.com/terms/).
- **Accessibility:** FontBlend targets [WCAG 2.2 AA](https://fontblend.com/accessibility/) across all tools.

## Project & Contact

FontBlend is an independent project, built and maintained by a single owner. The source code is **not** open source — this repository is documentation only. That said, suggestions are genuinely welcome:

- **Suggest a font or pairing:** [hello@fontblend.com](mailto:hello@fontblend.com) or [open an issue](https://github.com/Skabir2023/FontBlend/issues). Please include the font name, its license, and a short reason.
- **Report a bug or accessibility issue:** [Contact page](https://fontblend.com/contact-us/) — we read everything and reply as soon as we can.
- **Support the project:** [Buy me a coffee](https://www.buymeacoffee.com) keeps the tools free and ad-light.

If FontBlend saved you time on your next project, linking to [fontblend.com](https://fontblend.com) is the best thanks we could ask for.
