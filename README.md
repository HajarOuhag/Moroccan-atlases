# Moroccan Atlases
## Precision Agriculture & Crop Intelligence

### Project Overview
Moroccan Atlases explores potential vegetation and moisture stress patterns in the Admine argan ecosystem near Agadir, Morocco, using Sentinel-2 satellite imagery.

### Research Question
Where are potential vegetation and moisture stress patterns appearing in the Admine argan ecosystem, and which areas should be prioritized for field assessment and water-management intervention?

### Data and Methodology
- **Data source:** Copernicus Sentinel-2 Level-2A via Microsoft Planetary Computer STAC.
- **Study period:** January–October 2026.
- **NDVI:** Used as an indicator of vegetation greenness.
- **NDMI:** Used as an indicator related to vegetation moisture.
- Cloud filtering and scene classification masking are applied to reduce cloud and shadow contamination.

### Preliminary Results
The exploratory analysis identified 563 priority pixels out of 4,704 valid pixels (approximately 11.97%), using lower-percentile thresholds for both NDVI and NDMI.

These pixels are candidates for field assessment, not confirmed damaged trees or drought-affected land.

### Limitations and Validation
Satellite indices are indirect indicators and cannot independently confirm tree health or water stress. Results require field validation and may be affected by seasonality, land-cover differences, and residual cloud contamination.

### Intended Use
This project provides preliminary decision support to help prioritize field inspections and environmental monitoring in the Admine argan ecosystem.

### Reproducibility
The accompanying Jupyter notebook documents the exploratory analysis. Data access and execution depend on the availability of the public data services and required Python packages.
 
### Data Sources and Licensing

- **Satellite data:** Copernicus Sentinel-2 Level-2A imagery, accessed through the [Microsoft Planetary Computer STAC API](https://planetarycomputer.microsoft.com/dataset/sentinel-2-l2a).
- **Data access:** The analysis uses publicly accessible satellite data. Please consult the [Copernicus Sentinel data legal notice](https://sentinels.copernicus.eu/documents/d/sentinel/legal_notice) for the applicable terms of use and attribution.
- **Software:** This repository contains the analysis notebook and `requirements.txt` listing the Python packages used.

