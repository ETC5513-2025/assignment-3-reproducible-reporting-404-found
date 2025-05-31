# ETC5513 Assignment 3 – Reproducible Reporting

## 🔍 Topic  
**Water Insecurity:** Mapping household water insecurity in the U.S. using R and `tidycensus`.

## 👥 Group Members  
- Xinran Yang  
- Parth Tendulkar  
- Bagas Ari Wibawanto  

## 📊 Data Source  
The dataset was sourced from [TidyTuesday](https://github.com/rfordatascience/tidytuesday) and uses U.S. Census variables via the `tidycensus` R package.

## 📁 Project Structure

- `report.qmd` – Quarto report (renders to PDF)
- `slide.qmd` – Quarto slides (renders to PDF or HTML slides)
- `style/` – Contains `title.tex` and `preamble.tex` for PDF styling and `style.css` for html styling.
- `renv/` – Project-specific package library (do not modify)
- `renv.lock` – Lockfile listing exact package versions
- `report.pdf` - Assignment Report
- `slide.html` - Presentation
- `images` - Visualisations
- `README.md` - This file

## 🛠️ Reproducibility Setup

This project uses [`renv`](https://rstudio.github.io/renv/) to manage packages.

To reproduce the environment:

1. Open either `report.qmd` or `slide.qmd` (or the `.Rproj` file) in RStudio.  
2. Wait for `renv` to activate automatically (you’ll see a message in the Console).
3. Then run the following command in the Console:

```r
renv::restore()
