# Silver Detection Machine Learning Project

## Overview
This dataset was created to support research and educational applications in machine learning–based mineral classification, specifically the detection of silver-bearing minerals from photographic images. It consists of **3,869 silver images** and **16,695 non-silver images**, for a total of **20,564 images**. This repository is organized into three folders: Datat, Metadata, and Code. The Datat folder contains all mineral images in JPEG format, the Metadata folder stores descriptive information for each image, and the Code folder includes the Python scripts used to collect and process the dataset. All images were obtained from the Mindat database, a resource specializing in mineralogical information, and are used solely for educational purposes [1]. The folder structure is shown bellow.<br><br>

<img width="282" height="231" alt="image" src="https://github.com/user-attachments/assets/c2c94922-4b66-45d3-a374-4b0d28bb5c63" />


## Data
Images were collected from the Mindat.org database and organized into two binary categories for classification: **silver** and **non_silver** images. The *silver* folder contains 3,869 JPEG images, while the *non_silver* folder contains 16,695 JPEG images. All image data are stored on Google OneDrive, and the data folder provides a direct link to the drive from the README.md file. A copy of the metadata is also stored in this folder in both CSV and JSON formats.

<img width="481" height="255" alt="image" src="https://github.com/user-attachments/assets/0e2778fe-6d5c-46ea-9119-2329030b76b2" /> <br>



The silver class includes native silver and related silver-bearing minerals identified with the following keywords. A image distribution is not currently listed:

- *Silver*
- *Native silver*
- *Argentum*
- *Argentite*
- *Chlorargyrite*
- *Chalcopyrite*
- *Proustite*
- *Pyrargyrite*
- *Stephanite*
- *Polybasite*
- *Pearceite*
- *Miargyrite*
- *Freibergite*

The non-silver class is composed of approximately 70% hard negative images and 30% easy negative images to improve model robustness. The images are identified using the following keywords:

- *Galena*
- *Pyrite*
- *Hematite*
- *Graphite*
- *Stibnite*
- *Chalcopyrite*
- *Molybdenite*

Each image class has metadata stored in both CSV and JSON formats. The files are identical in content and follow the same labeling scheme. Each image has an associated set of metadata fields, as shown below.
  
## Metadata
All image classes have metadata stored in both CSV and JSON formats. The files are identical in content and follow the same labeling scheme. Each image has an associated set of metadata fields, as shown below.

The metadada folder stores 
<p align="left">
  <img width="566" height="295" alt="image" src="https://github.com/user-attachments/assets/28f7c591-84c3-4af7-a736-714f61754659" />
</p>

## Code
This project uses two Jupyter Notebooks to implement the data collection and validation workflow for the silver detection dataset.

1. image_download_workflow.ipynb

This notebook performs automated data acquisition. It reads the Mindat image URL list, filters minerals into silver and non-silver classes, and programmatically downloads available JPEG images. The script includes error handling, logging, and class balancing logic (including hard and easy negatives) to construct the final dataset.

2. dataset_validation_metadata.ipynb

This notebook validates the downloaded dataset and generates structured metadata. It checks file integrity, extracts image properties (dimensions, size, format), assigns class labels, and exports metadata into CSV and JSON formats. These files are used to link each image to its corresponding data record for machine learning workflows.

## Reference
[1] Hudson Institute of Mineralogy, “Mindat.org – The Mineral Database.” [Online]. Available: https://www.mindat.org. Accessed: Feb. 14, 2026.

## Author
Brent Knopp<br>
Computer Science, Data Science Program<br>
University of Idaho<br>
Coeur d'Alene, Idaho<br>
Email: knop8939@vandals.uidaho.edu
