# FineGym Video Extractions

This repository provides scripts for extracting videos from the FineGym99 and FineGym288 datasets. It includes functionality for building CSV files with relevant metadata and utilizes MoviePy to trim the videos to capture precise events. The scripts are designed to simplify the process of preparing video data for analysis from both datasets. 

For more information and access to the datasets, visit the [FineGym dataset repository](https://sdolivia.github.io/FineGym/).



## Setup Instructions

1. **CSV File Creation**: 
   - You can either create your own CSV file with relevant metadata or directly use the CSV files provided in this repository.

2. **Video Extraction**:
   - To extract videos, use the `VideosExtractionTrain99.ipynb` notebook. The notebook will guide you through the extraction process using the necessary libraries.

3. **Required Libraries**:
   You can install the required libraries using the following command:
   ```bash
   pip install pandas moviepy
