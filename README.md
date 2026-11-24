# The NuTerra Project

NuTerra connects six pillars for preserving knowledge, advancing technology, developing people, supporting families, and building resilient communities. This repository contains the public GitHub Pages site. It uses static HTML, CSS, and SVG assets.

## Preview

Run `python3 -m http.server 8794 --bind 127.0.0.1 --directory docs` and open `http://127.0.0.1:8794/`. All local links and asset references work with the `/NuTerra/` project prefix.

## GitHub Pages

Use the separate `deusordo/NuTerra` repository. From the repository’s Settings → Pages, choose **Deploy from a branch**, then **main** and **/docs**. The expected address is [https://deusordo.github.io/NuTerra/](https://deusordo.github.io/NuTerra/). The public site has no backend or build dependencies. Verify the homepage, pillar detail links, and both established project destinations after deployment.

The `docs/` folder is the complete publishable site. Keep private records and planning material outside that folder and outside Git.
