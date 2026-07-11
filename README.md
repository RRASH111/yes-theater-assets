# Yes Theatre — media assets

Static media (PDF booklets, photos, and video) for the **Yes Theatre portfolio gallery**.
Kept in a separate public repo so it can be served for free over the
[jsDelivr](https://www.jsdelivr.com/) CDN and keep the site repo light.

Files are organised by program: `theatre/`, `drama-education/`, `storytelling/`,
`drama-therapy/`. They are produced from the original source material by
`scripts/prep.py` in the site repo (PDFs losslessly cleaned or rasterised, HEIC→JPG,
MOV→MP4, images optimised to WebP).

**CDN base:** `https://cdn.jsdelivr.net/gh/RRASH111/yes-theater-assets@v1/`

To publish updated media, re-run the prep script, commit here, and push a new tag
(`v2`, …), then point `NEXT_PUBLIC_ASSETS_BASE_URL` at the new tag.
