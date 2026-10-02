# xrayxl.com

The website for [XRayXL](https://github.com/XRayXL/XRayXL-AddIn) - a flight
recorder for the code running inside Excel.

`index.html` is the front page: hand-written HTML with inline CSS, no build
step and no dependencies, and one small script that closes the menu. Fonts come
from Google Fonts; nothing else is fetched. Open the file in a browser and you
see exactly what is served.

`docs/` is XRayXL's user documentation: the same pages its releases carry,
built from the Markdown in [XRayXL-AddIn](https://github.com/XRayXL/XRayXL-AddIn).
Change them there, not here.

| File | What it is |
|---|---|
| `index.html` | The front page |
| `docs/` | The user docs as web pages, with their images |
| `LICENSE`, `THIRD-PARTY-NOTICES.txt` | The licences the docs link to |
| `CNAME` | The custom domain GitHub Pages serves |
| `.nojekyll` | Serves the files as they are, without running Jekyll over them |

Published by GitHub Pages at [xrayxl.com](https://xrayxl.com/).
