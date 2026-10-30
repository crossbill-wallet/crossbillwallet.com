# crossbillwallet.com

The public website for [Crossbill Wallet](https://github.com/crossbill-wallet/crossbill), served by GitHub Pages at https://crossbillwallet.com.

It is one page: `index.html` and `style.css`, with no frameworks, trackers, analytics, external fonts or external scripts. The diagrams are inline SVG in `index.html`; their colors come from `style.css`, so they follow light and dark mode.

## Images

| File | Pixels | Keep under | Use |
| --- | --- | --- | --- |
| `crossbill-icon-320.png` | 320 x 320 | 80 KB | Header (40 px) and hero (160 px), sharp on Retina |
| `favicon-32.png` | 32 x 32 | 5 KB | Browser tab |
| `apple-touch-icon.png` | 180 x 180, no transparency | 30 KB | iPhone home screen |
| `og-image.png` | 1200 x 630 | 300 KB | Link previews (optional) |
| `registry-icon.png` | 256 x 256 | 60 KB | Install step 1 (in place) |

PNG, sRGB, with all metadata stripped (no camera, location or editor details).

Search `index.html` for `IMAGE PLACEHOLDER` to find where each one goes.

## Changes

Open a branch and a pull request. Don't commit to `main` directly.

Facts on the page come from the [crossbill](https://github.com/crossbill-wallet/crossbill) and [crossbill-startos](https://github.com/crossbill-wallet/crossbill-startos) repositories. When those change, check the page against them.

Content is licensed under Apache 2.0, as the wallet is.
