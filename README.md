# Lateral Thinking Machines · GitHub profile

This repository publishes the landing page for [LateralThinkingMachine](https://github.com/LateralThinkingMachine).

GitHub displays [`profile/README.md`](profile/README.md) on the organization's public Overview tab. The repository must remain public, with the profile on the default branch.

## Editing the page

- Update [`profile/README.md`](profile/README.md) for copy, layout, and links.
- Keep images in [`profile/assets/`](profile/assets/). The banner and retained Enny artwork are the supplied original PNG files. The product overview uses the simple database and orbit outline icons from the supplied reference screenshot.
- Use absolute asset URLs so images work both in the repository and on the organization page. Update those URLs if the default branch or asset paths change.
- Link only to public resources. Keep product descriptions consistent with their actual availability; the current page presents work in progress.
- Check the rendered organization page and its images after publishing, including at a narrow viewport.

See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) for the publishing convention.

## Borderless product overview

GitHub adds borders to README tables and removes custom inline CSS. The two-column product section is therefore rendered by `products-light.svg` and `products-dark.svg`, selected with `<picture>`. These are self-contained vector layouts, including the icons and text; no screenshots or raster icon scaling are used.

The SVG root deliberately has no `viewBox`: percentage positions center each column while the text and 32-pixel square icons retain their size as the image width changes. An internal media query wraps descriptions into shorter lines below 560 pixels. Preserve the README image's `width="100%"` and `height="224"` attributes and both SVGs' height when editing this layout. The icons retain Lucide's square 24×24 coordinate system and scale uniformly.

Edit product copy in both SVG variants and keep the complete README image alt text in sync. Visible SVG labels are image content, rather than selectable README text; the alt text supplies both names, roles, and descriptions to assistive technology. Verify the rendered page at desktop and narrow widths after changes.

## Icon attribution

`atoposdb.svg` and `enny.svg` use Lucide's [database](https://github.com/lucide-icons/lucide/blob/586bf5cf9bcf4129a63c0ce574602b23ca24f324/icons/database.svg) and [orbit](https://github.com/lucide-icons/lucide/blob/586bf5cf9bcf4129a63c0ce574602b23ca24f324/icons/orbit.svg) geometry, respectively. The product overview embeds that same geometry directly. Stroke colors are explicit for light and dark backgrounds; the standalone source icons are retained for reuse.

The upstream [ISC and Feather-derived MIT license notices](profile/assets/LUCIDE-LICENSE.txt) are included with the assets.
