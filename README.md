# Red King Geospatial

Public website for **Red King Geospatial**, an Arkansas-based GIS consulting and spatial data engineering practice.

## Services represented on the site

- Spatial data engineering and ETL
- Address and location-data cleanup
- E911 / NG911-oriented data quality work
- PostgreSQL / PostGIS
- QGIS workflows and Python automation
- Web mapping and spatial APIs
- Spatial analysis
- GIS consulting and subcontract support

## Site architecture

This is intentionally a zero-dependency static site:

- `index.html` — site content and structure
- `styles.css` — responsive styling
- `favicon.svg` — site icon
- `.nojekyll` — prevents unnecessary Jekyll processing on GitHub Pages

There is no package manager, JavaScript framework, build step, or CI workflow required to publish the site.

## GitHub Pages

In the repository, open **Settings → Pages** and configure:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

The initial project-site URL will be:

`https://code-johnny-code.github.io/red-king-geospatial/`

## Custom domain

The intended production domain is `redkinggeo.com`. Once DNS is ready, add the domain in **Settings → Pages → Custom domain**. GitHub will create or use a `CNAME` file as part of that configuration.

Do not commit API keys, client data, proprietary datasets, credentials, or other secrets to this public repository.
