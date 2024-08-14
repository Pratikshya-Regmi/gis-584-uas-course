# GIS/MAE 584 Mapping and Analytics Using UAS

[![pages-build-deployment](https://github.com/ncsu-geoforall-lab/gis-584-uas-course/actions/workflows/pages/pages-build-deployment/badge.svg?branch=gh-pages)](https://github.com/ncsu-geoforall-lab/gis-584-uas-course/actions/workflows/pages/pages-build-deployment)

Course website for GIS/MAE 584 Mapping and Analytics Using UAS

## Requirements

[Quarto: v1.4](https://quarto.org/docs/get-started/)

## Configuration

Install Quarto following the directions at [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)

## Development

To start the development server, run:

```bash
quarto preview
```

### Optimize Images

Convert images to webp format using the following commands:

```bash
mogrify -format webp -quality 80 *.{png,PNG,jpg}
```

## Deployment

The site is deployed to GitHub Pages using the `gh-pages` branch. The site will be automatically deployed when changes are pushed to the `main` branch.

## Authors

Copyright 2024

- Corey T. White, NCSU GeoForAll Lab
- Helena Mitasova, NCSU GeoForAll Lab
- Justyna Jeziorska

Course developed by GeoForAll Lab at The Center for Geospatial Analytics at North Carolina State University

## License and use

The course material is under CC BY-SA 4.0 license.

[https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)
