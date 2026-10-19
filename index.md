---
title: LI YINGFANG — Data Science Portfolio
layout: default
---

# LI YINGFANG — Data Science Portfolio

Hi! I am LI YINGFANG, a master's student at the University of Macau (CISC7204 Data Visualization). I enjoy turning raw data into clear, readable pictures — geospatial maps, statistical charts, and interactive visualizations.

## Technical Skills

- **Languages & tools:** Python, Git/GitHub, Jupyter Notebook
- **Data:** Pandas, NumPy, SciPy
- **Visualization:** Matplotlib, animation, choropleth / Voronoi / dot-density maps
- **Currently learning:** interactive mapping, dashboard design, NLP applications

## Project Showcase

### Geospatial Data Visualization with Python

**Research question:** How can Python be used to explore and communicate patterns in geospatial data — flight tracks, city point clouds, and administrative boundaries?

![US state choropleth](images/choropleth.png)
*US state outline map rendered with Matplotlib, used as the base layer for regional analysis.*

![Flight track animation](images/track_animation.gif)
*Animated flight tracks: a sample of recorded positions shown over time, exported as a GIF.*

**Findings:** The project builds a reproducible pipeline (Pandas → SciPy Voronoi → Matplotlib) that renders point-density maps, choropleths, Voronoi tessellations, and track animations from flight and city data. It also exposed a classic data-quality trap: case-sensitive filtering silently returned zero matches on an all-lowercase city-name column, fixed by normalizing case before filtering.

- **Project repository:** [github.com/lyf200262-um/data-science-project](https://github.com/lyf200262-um/data-science-project)
- **Status:** Completed (ongoing refinements planned — interactive filtering and dashboard-style layers)

## Improvements & Next Steps

Reviewing the portfolio with a classmate highlighted that the site could better explain *why* each visualization matters and how to reproduce it. Improvements applied:

- Added a proper Jekyll page title (front matter) so the site reads as a personal portfolio, not a bare repository page.
- Added this "Improvements & Next Steps" section to make the reflection and roadmap explicit on the site itself.

Planned next steps:

1. Make the visualizations interactive (e.g., Plotly/Bokeh) instead of static images.
2. Add 1–2 more completed projects from different domains (NLP, statistics) to show breadth.
3. Apply a custom Jekyll theme and CSS for a more polished look.
4. Add a short video walkthrough of the analysis.

## Contact

- GitHub: [lyf200262-um](https://github.com/lyf200262-um)
