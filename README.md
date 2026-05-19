# sholler-lab-website

HTML and CSS code for the Sholler Lab website (<https://sites.psu.edu/shollerlab>) at the Penn State College of Medicine.

## Structure

- **HTML pages**: Modular, CMS-friendly fragments (`header.html`, `home.html`, `research.html`, `people.html`, `education.html`, `publications.html`, `inspiration.html`, `contact.html`, `footer.html`)
- **Styling**: Centralized `global-css.css` with page-level overrides

## Reusable intake templates

The `lab-info/` directory holds structured content for the site. `lab-info.xlsx` is the primary source of truth — edit it to update content, then export each sheet as a CSV to the same directory. The individual CSV files are derived from the spreadsheet and some intentionally include only a few rows as structural examples for cloning this layout to other labs.
