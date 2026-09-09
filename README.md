# SKONGA AI — Website

Landing page for **SKONGA AI**, a student assistant built in Tanzania.

Live (GitHub Pages): https://shabanihamidu19-cell.github.io/skonga-web/

## Structure

```
index.html                 # site + SEO / Open Graph / JSON-LD
assets/icon.png            # favicon
assets/og-image.png        # social preview image
downloads/skonga-ai.apk    # Android APK
```

## SEO

`index.html` already includes:

- `<title>`, `description`, `keywords`, `robots`, `canonical`
- Open Graph (`og:title`, `og:description`, `og:image`, `og:url`, `og:type`)
- Twitter card
- Schema.org `SoftwareApplication` JSON-LD
- `lang="sw"` and `og:locale` `sw_TZ`

## Run locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## GitHub Pages

Settings → Pages → Deploy from branch `main` / root.
