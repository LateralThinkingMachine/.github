# Lateral Thinking Machines · GitHub profile

This repository publishes the landing page for [LateralThinkingMachine](https://github.com/LateralThinkingMachine).

GitHub displays [`profile/README.md`](profile/README.md) on the organization's public Overview tab. The repository must remain public, with the profile on the default branch.

## Editing the page

- Update [`profile/README.md`](profile/README.md) for copy, layout, and links.
- Keep images in [`profile/assets/`](profile/assets/). The current profile uses compact monochrome logo variants. The original banner, Enny artwork, and earlier product overview assets are retained in the repository.
- Use absolute asset URLs so images work both in the repository and on the organization page. Update those URLs if the default branch or asset paths change.
- Link only to public resources. Keep product descriptions consistent with their actual availability; the current page presents work in progress.
- Check the rendered organization page and its images after publishing, including at a narrow viewport.

See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) for the publishing convention.

## Profile presentation

The profile pairs a compact, theme-aware monochrome logo with native Markdown headings, paragraphs, and a six-topic index. The logo variants are copied from the public website's `ltm-logo-monochrome.svg` and `ltm-logo-light.svg`; the `<picture>` element selects the appropriate contrast for GitHub's theme. Keep the displayed size at 155 × 58 pixels to preserve the lockup's proportions.

The index links to the website's technical overview sections. Website, technical overview, development roadmap, and public developer repository links give visitors direct next steps. The profile describes AtoposDB as in development and distinguishes the database, the planned Enny companion and mascot, and the Lateral Thinking Machines organization.

The earlier `products-light.svg` and `products-dark.svg` layouts and the supplied full-resolution banner remain available as retained assets. The current profile does not embed their product descriptions; edit its selectable Markdown copy in `profile/README.md`. Verify the rendered page, asset contrast, and public destinations after publication.

## Icon attribution

`atoposdb.svg` and `enny.svg` use Lucide's [database](https://github.com/lucide-icons/lucide/blob/586bf5cf9bcf4129a63c0ce574602b23ca24f324/icons/database.svg) and [orbit](https://github.com/lucide-icons/lucide/blob/586bf5cf9bcf4129a63c0ce574602b23ca24f324/icons/orbit.svg) geometry, respectively. The product overview embeds that same geometry directly. Stroke colors are explicit for light and dark backgrounds; the standalone source icons are retained for reuse.

The upstream [ISC and Feather-derived MIT license notices](profile/assets/LUCIDE-LICENSE.txt) are included with the assets.
