# Oʻahu STEW Organization Map Data Package

This repository contains a Leaflet web map and supporting GeoJSON layers for Oʻahu organizations from the Stewardship Mapping Project (STEW).

## Contents

- `index.html`
  - Standalone interactive map for viewing and filtering organizations.

- `data/`
  - `org_data.geojson`: combined GeoJSON layer containing all organizations.
  - Individual organization GeoJSON files: one file per organization.

## Data Processing Note

The GeoJSON layers in this package were created by joining Stewardship Mapping Project survey data with the corresponding GIS layer, then exporting:

- one all-organizations layer (`org_data.geojson`), and
- one layer per organization (individual `.geojson` files).

## How to Use

1. Open `index.html` in a web browser.
2. Use the organization checklist in the left panel to toggle layers on/off.
3. Click map polygons to view organization details.

## Data Citation

USDA Forest Service, Northern Research Station. (2021). *The Stewardship Mapping Project: 2021 Oʻahu Data Download* [Dataset]. https://research.fs.usda.gov/products/dataandtools/stewardship-mapping-project-2021-oahu-data-download

## Notes

- This repository is intended as a general-use handoff package for collaborators.
- Citation should be retained in downstream uses of these data.
