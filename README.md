# Silver Detection Machine Learning Project

## Overview
This dataset was created to support research and educational applications in machine learning–based mineral classification, specifically the detection of silver-bearing minerals from photographic images. It consists of **3,869 silver images** and **16,695 non-silver images**, for a total of **20,564 images**. This repository is organized into three folders: Datat, Metadata, and Code. The Datat folder contains all mineral images in JPEG format, the Metadata folder stores descriptive information for each image, and the Code folder includes the Python scripts used to collect and process the dataset. All images were obtained from the Mindat database, a resource specializing in mineralogical information, and are used solely for educational purposes [1].

## Data
Images were collected from the Mindat.org database and organized into two binary categories for classification: **silver** and **non_silver** images. The *silver* folder contains 3,869 JPEG images, while the *non_silver* folder contains 16,695 JPEG images. All image data are stored on Google OneDrive, and the data folder provides a direct link to the drive. A copy of the metadata is also stored in this folder in both CSV and JSON formats.

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
The metadada folder stores 
<p align="left">
  <img width="558" height="332" alt="image" src="https://github.com/user-attachments/assets/483ef54e-44f1-4de3-835e-01d7238e9cf5" />
</p>

## Code
- Python
- Scikit-learn
- Google Colab
- GitHub for version control

## Reference
[1] Hudson Institute of Mineralogy, “Mindat.org – The Mineral Database.” [Online]. Available: https://www.mindat.org. Accessed: Feb. 14, 2026.

## Author
Brent Knopp<br>
Computer Science, Data Science Program<br>
University of Idaho<br>
Coeur d'Alene, Idaho<br>
Email: knop8939@vandals.uidaho.edu
