🛰️ Sentinel-2 Imagery Analysis for Land Cover and Vegetation Monitoring in Bali
A comprehensive Google Earth Engine (GEE) script for analyzing Sentinel-2 satellite imagery over Bali, Indonesia (January–July 2025). This tool provides advanced remote sensing capabilities for land cover classification, vegetation monitoring, and environmental assessment using state-of-the-art spectral indices and machine learning algorithms.
🌟 Key Features

Multi-Spectral Index Analysis: NDVI, SAVI, and NDWI calculations for comprehensive vegetation and water body assessment
Advanced Cloud Masking: Automated cloud filtering for improved image quality
Land Use/Land Cover Classification: Random Forest machine learning algorithm for accurate LULC mapping
Accuracy Assessment: Statistical validation of classification results
Data Visualization: Interactive composite image displays and thematic maps
Export Capabilities: Direct export to Google Drive for further analysis

🔬 Spectral Indices
NDVI (Normalized Difference Vegetation Index)

Purpose: Vegetation health and density assessment
Formula: (NIR - Red) / (NIR + Red)
Applications: Crop monitoring, deforestation detection, vegetation stress analysis

SAVI (Soil-Adjusted Vegetation Index)

Purpose: Vegetation analysis with soil background correction
Formula: ((NIR - Red) / (NIR + Red + L)) × (1 + L), where L = 0.5
Applications: Sparse vegetation areas, agricultural monitoring

NDWI (Normalized Difference Water Index)

Purpose: Water body detection and moisture content assessment
Formula: (Green - NIR) / (Green + NIR)
Applications: Water mapping, flood monitoring, irrigation assessment

🎯 Study Area
Location: Bali, Indonesia
Temporal Coverage: January – July 2025
Satellite Platform: Sentinel-2 (10-20m spatial resolution)
Coverage Area: Entire Bali province including coastal and mountainous regions
📋 Requirements

Google Earth Engine account with access permissions
Basic understanding of remote sensing principles
JavaScript knowledge for GEE code modification
Google Drive account for data export

🚀 Installation & Usage
Setup

Access the Google Earth Engine Code Editor
Copy and paste the script into the editor
Ensure you have the necessary GEE permissions for Bali region
Verify Google Drive integration for export functionality
