# Hawaii Tourism Data Visualization

A D3.js-based interactive visualization showing Hawaii tourism data before and after the pandemic.

## Features

- **Scene 1**: Total visitor numbers by region across all years
- **Scene 2**: 2019 vs 2020 comparison showing pandemic impact  
- **Scene 3**: 2019 vs 2022 comparison showing recovery progress
- Interactive charts with tooltips and annotations
- Martini Glass narrative structure with scene navigation

## Technologies Used

- D3.js v7
- d3-annotation v2.5.1
- topoJSON v3
- Vanilla JavaScript, HTML, CSS

## Data

The visualization uses `hawaii_tourism_data.csv` which contains monthly visitor arrival data from 2015-2025 for different regions:
- US West
- US East  
- Japan
- Canada
- Europe
- Oceania
- China
- Korea
- Latin America

## Usage

### Local Development
```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
