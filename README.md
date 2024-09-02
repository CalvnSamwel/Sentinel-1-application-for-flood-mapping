# Sentinel-1-application-for-flood-mapping

## Introduction
Welcome to the Sentinel-1-application-for-flood-mapping Repository! This repository contains JavaScript code for detecting and analyzing flood inundation using Synthetic Aperture Radar (SAR) data from Sentinel-1. The code is designed to assess flood events by comparing SAR images from before and after a flood incident, applying speckle filtering, and identifying flooded and water body areas.

The repository includes scripts for preprocessing Sentinel-1 SAR data, applying speckle filtering, detecting flooded areas, and visualizing the results using Google Earth Engine (GEE). This code can be used to monitor flood events and their impacts on land surfaces.

## Flood MApping Overview
1. Flood Detection: This project uses Sentinel-1 SAR imagery to detect and analyze flood inundation by comparing images before and after the flood event. The workflow includes:
2. Data Import and Filtering: Retrieve Sentinel-1 images for the specified time periods before and after the flood, filtered by VH polarization and IW mode.
3. Image Processing: Apply median filtering to the image collections, convert images to dB scale, and use speckle filtering to reduce noise.
4. Flood Detection: Use thresholding to identify areas inundated by floods and distinguish them from permanent water bodies.
5. Visualization: Display the results on a map with layers showing before and after images, flood inundation, and water bodies.

## Code Overview
a. Data Import: The script starts by defining the region of interest (ROI) and importing Sentinel-1 SAR data. Images are filtered based on polarization, mode, and orbit pass.
b. Preprocessing: Median filtering is applied to the images from before and after the flood event. Speckle filtering is then performed, and images are converted to dB scale.
c. Flood Detection: Thresholding techniques are used to identify flooded areas and distinguish them from water bodies. Masks are created to highlight these areas.
d. Visualization: The results are visualized using Google Earth Engine, with layers for raw images, filtered images, flood inundation, and water bodies. A legend and map title are added for better interpretation.
e. Export: The final results are exported to Google Drive for further analysis and sharing.

## Getting Started
To use the scripts in this repository, you will need a Google Earth Engine account. Follow these steps to get started:
1. Clone or Download: Clone or download the repository to your local machine.
2. Open Google Earth Engine Code Editor: Navigate to the Google Earth Engine Code Editor.
3. Create a New Script: Create a new script and paste the code from this repository.
4. Modify Variables: Update the table variable to match your input data boundary.
5. Run the Script: Execute the script to process the images, detect floods, and visualize the results.

## Acknowledgments
This script was prepared by Calvin Samwel Swai @ Aquila Eyes Group. Special thanks to the Google Earth Engine team for providing the platform and tools necessary for this analysis.

Happy flood Mapping! 🌊


![image](https://github.com/user-attachments/assets/8bba59c3-0c5a-498d-9a12-394b8a8dc094)
