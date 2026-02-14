# Silver Detection Machine Learning Project

## Overview
This dataset was created to support research and educational applications in machine learning–based mineral classification, specifically the detection of silver-bearing minerals from photographic images. It consists of **3,869 silver images** and **16,695 non-silver images**, for a total of **20,564 training images**.   All images were obtained from the Mindat database, a resource specializing in mineralogical information, and are used solely for educational purposes [1].

## Dataset
Images were collected from the Mindat.org database and organized into:
- silver/
- non_silver/
- 
The silver class includes native silver and related silver-bearing minerals identified using keywords such as *silver, native silver, argentum, argentite, chlorargyrite, proustite, pyrargyrite, stephanite, polybasite, pearceite, miargyrite, and freibergite*.

The non-silver class is composed of approximately 70% hard negative images and 30% easy negative images to improve model robustness; hard negatives include visually similar minerals such as *galena, pyrite, hematite, graphite, stibnite, sphalerite, chalcopyrite, and molybdenite*, which help reduce false positives during classification.

Metadata was stored in CSV and JSON formats.

## Methods
- Data preprocessing using Python
- Model training using CNN / Machine Learning classifiers
- Train/Validation/Test split: 70% / 15% / 15%

## Tools Used
- Python
- Scikit-learn
- Google Colab
- GitHub for version control

## Author
Brent Knopp  
University of Idaho – Data Science Program
