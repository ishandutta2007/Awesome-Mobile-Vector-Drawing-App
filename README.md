# Awesome-Mobile-Vector-Drawing-App

## Top Mobile Vector Drawing App Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Touch-Optimized SVG Editing, iPad Illustration & Android Vector Tools*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Vector Drawing Apps**. These tools bring vector illustration to tablets and phones — bezier paths, layers, SVG export — with a spectrum running from polished commercial iPad apps to open-source Android editors that run entirely offline.

**Examples** include Inkpad, FreePaint, VectorTouch, and FidoCadJ (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, touch-optimized vector editing, and offline mobile drawing — especially relevant as **Inkpad** remains the most complete open-source iPad vector app under the MPL 2.0 license [citation:3][citation:9], and **FreePaint** offers native SVG editing on Android via F-Droid [citation:7].

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Adobe Illustrator on iPad** — **The reference professional vector tool for tablets.** Full Illustrator toolset reimagined for touch and Apple Pencil, with Creative Cloud sync and .ai file compatibility. **Subscription required** (Creative Cloud plan). **Best for professional designers** already in Adobe's ecosystem who need desktop-class vector power on an iPad.

- **Vectornator (Linearity Curve)** — **The free Apple-ecosystem vector design tool.** Free plan with paid Pro tiers, Apple Pencil support, auto-trace, and Boolean operations. **Trade-offs**: Apple-only, no Android or Windows version. **Best for iPad users** wanting a polished free vector app with Apple Pencil integration.

- **Concepts** — **The infinite-canvas sketching app.** Vector-based drawing on an infinite canvas with adjustable precision, ideal for ideation and wireframing. **Free tier with paid Pro**. **Best for designers** wanting a flexible ideation space rather than precise illustration.

- **Procreate** — **The iPad painting standard.** Not a vector app, but widely used by mobile artists for illustration and sketching. **One-time purchase**. **Best for painters** wanting the most polished iPad drawing experience, though it is raster-based rather than vector.

## Open-Source GitHub Projects

- **Inkpad** — **The open-source iPad vector illustration app.** **Mozilla Public License 2.0**, available on the App Store [citation:3][citation:9]. **A vector illustration app designed from scratch for the iPad** — supports paths, compound paths, text, images, groups, masks, gradient fills, and unlimited layers [citation:9]. **Designed for performance**: can handle drawings with hundreds to thousands of shapes without lag, with zero-lag selection, scaling, and rotation of hundreds of objects [citation:3][citation:9]. **Full toolset**: bezier pen tool, Boolean operators (Unite, Intersect, Exclude, Subtract Front), arbitrary stroke dash patterns, snap to grid/points/path edges, and layer isolation [citation:9]. **Export to SVG, PDF, PNG, and JPEG**, with direct Dropbox and Files app integration [citation:3][citation:9]. **The honest caveat**: **iPad-only** and the last App Store update was in 2025 — it works on modern iPadOS but is not actively developed [citation:3]. **Best for iPad users** wanting a free, open-source vector illustration app with a proven feature set [citation:9].

- **FreePaint** — **The native Android vector drawing app.** **Open-source, available on F-Droid**, with **Material Design 3** and dynamic colors [citation:7]. **Draw open or closed paths** with customizable fill/stroke colors and stroke sizes, **erase shapes from closed paths or points from open paths**, and **save/load SVG files** [citation:7]. **Selection tool** for marquee-selecting and moving paths, with **pan and pinch-to-zoom** [citation:7]. **Requires Android 7.0+** [citation:7]. **The honest caveat**: **basic feature set** — no layers, no Boolean operations, no text tools, and no gradient fills [citation:7]. **Best for Android users** wanting a simple, offline SVG drawing app without ads or subscriptions.

- **VectorTouch** — **The touch-optimized SVG editor for Android.** **MIT licensed**, bringing the **GodSVG** editing experience to mobile with a touch-friendly interface [citation:14]. **Direct SVG file editing** on Android devices, available on Google Play Store with direct APK downloads from GitHub releases [citation:14]. **The honest caveat**: **still in development and may have bugs** [citation:14]. **Best for Android users** wanting direct SVG markup editing with a mobile-optimized interface.

- **FidoCadJ** — **The easy-to-use 2D vector drawing program with Android support.** **GPL-3.0 licensed**, a free user-friendly vector graphic editor for macOS, Linux, Windows, and Android [citation:1]. **Includes a vast library of electrical symbols and footprints** — useful as a basic schematic capture for presentations or papers [citation:1]. **Drawings can be exported to PDF, EPS, PGF for LaTeX, SVG, PNG, and JPG** [citation:1]. **The honest caveat**: **specialized for electronics diagrams**, not general illustration — the symbol library and workflow are oriented toward schematic capture rather than artistic drawing [citation:1]. **Best for electronics hobbyists and engineers** needing a portable vector tool for circuit diagrams, accepting its domain-specific focus.

### Additional Strong Open-Source Options

- **Capy Canvas** — **The cross-platform painting and illustration app in active development.** Open-source, targeting **Linux, Windows, macOS, iPad, Android, and web** [citation:5]. **GPU-accelerated with wgpu**, aiming for 120+ FPS with brushes thousands of pixels wide [citation:5]. **Multiple workspaces** (Sketch, Paint, Photo) with HDR support, non-destructive effect chains, and advanced selection tools [citation:5]. **The honest caveat**: **in active development** — evaluate stability and mobile feature parity before committing a production workflow [citation:5]. **Best for artists** wanting a modern, GPU-native open-source alternative to Procreate that runs on multiple platforms.

- **Atomic Canvas** — **The Android infinite-canvas note-taking and vector app.** Open-source Flutter app with **pen and draw support**, smart gestures (fingers pan when stylus detected, two-finger tap to undo), and **CRDT-based sync** via Loro for full history playback and versioning . **Simple, clean UI** with color selector, size adjust, history scrubber, and gallery . **The honest caveat**: **note-taking and sketching focus**, not a full vector illustration suite — no Boolean operations or advanced path editing . **Best for Android tablet users** wanting a snappy infinite-canvas app with pen support and history versioning.

**Frameworks for building custom systems**: Combine **Inkpad** for full-featured iPad vector illustration with SVG/PDF export, **FreePaint** for simple Android SVG drawing, **VectorTouch** for direct SVG markup editing on mobile, and **FidoCadJ** for electronics diagramming across platforms — to build a mobile vector drawing stack tailored to your platform (iPad vs Android) and use case (illustration vs schematic vs quick sketching).

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile vector drawing apps differ significantly in platform support, feature depth, and maintenance status. **Inkpad is the most complete open-source iPad vector app** with a full illustration toolset and SVG/PDF export, but **it is iPad-only and not actively developed** [citation:3][citation:9]. **FreePaint is the simplest Android SVG editor** — it saves real SVG files but lacks layers, text, and Boolean operations [citation:7]. **VectorTouch is still in development and may have bugs** [citation:14]. **FidoCadJ is specialized for electronics diagrams**, not general illustration [citation:1]. **Capy Canvas is actively developed but still maturing** — its cross-platform ambitions are promising but mobile stability should be verified [citation:5].
- Self-hosted open-source solutions require proper app installation from F-Droid or GitHub releases (not always the Play Store), and awareness that mobile vector editors are limited by available screen size and touch precision compared to desktop tools.

---

**Made for mobile designers, illustrators, and developers choosing vector drawing tools that match their tablet platform and touch workflow.**
Let's make mobile vector drawing more open, touch-optimized, and offline-capable.
