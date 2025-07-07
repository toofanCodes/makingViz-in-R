# Visualizing Growth: Global Economic Data Analysis

This project presents a comprehensive data-driven analysis of global economic growth, population, and prosperity using R and Quarto. The main deliverable is an interactive presentation built with Quarto Reveal.js slides, featuring visualizations of GDP, per-capita GDP, PPP, inflation, and population trends for major world economies.

## Project Structure

```
DataViz_RCode&Datasets/
├── DataVizV2.qmd         # Main Quarto presentation source file
├── DataVizV2.html        # Rendered HTML presentation (output)
├── DataVizV2_files/      # Supporting files for the HTML presentation
├── data/                 # (Optional) Folder for all data files
├── README.md             # Project documentation (this file)
```

## Data Files

The project uses several data files (in CSV and Excel formats) containing:
- Country-level GDP and per-capita GDP data
- Purchasing Power Parity (PPP) statistics
- Population figures and trends
- Inflation rates
- Other macroeconomic indicators for major world economies

These datasets are used to generate the visualizations and analyses in the presentation. You can organize them in a `data/` folder for clarity, or keep them in the project root.

## How to Render the Presentation

1. **Install Quarto:**
   - [Download Quarto](https://quarto.org/docs/get-started/) and follow the installation instructions for your OS.

2. **Install R and Required Packages:**
   - Make sure you have R installed.
   - Install the required R packages:
     ```r
     install.packages(c("tidyverse", "ggplot2", "readxl", "treemap", "patchwork"))
     ```

3. **Render the Quarto file:**
   - In your terminal, run:
     ```sh
     quarto render DataVizV2.qmd
     ```
   - This will generate `DataVizV2.html`, which you can open in your browser.


## Credits

- Data sources: IMF World Economic Outlook, Oct 2023
- Authors: Saran, Aditi, Pooja Patil, Pooja Nalam, Pankhuri

---

For questions or contributions, please open an issue or pull request on GitHub. 