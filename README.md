---
output:
  html_document: default
  pdf_document: default
---
# BIA project
**Group8**
 
## Introduction

Welcome! Our project focused to identify the tuberculosis based on chest radiography images.This folder contains the project report, source codes, trained Unet model and a CNN model for Tuberculosis image classification and a command line executable file allow users to use our pre-trained model to classify their chest radiography images. **The language version used for codes is python 3.7**

- **?.h5**: The trained CNN model for classification
-	**seg_3.h5**: The trained Unet model for Lung segmentation in X-ray
-	**BIA_project_report_Group_8**: Project report
-	**self_model.py**: Main source code for Lung segmentation, contains codes and discriptions of image preprocessing, model construction, accuracy evaluation & visaulization
-	**load_model.py**: Codes to load the pretrained Unet model to produce images of the segmented lungs using classification dataset
- 

## Getting Started 

1. Enter python environment 
```text
python3
```

2. Create a 'test' folder under your provided directory to hold the images.
```text
cd your/test/dir
mkdir test
```
3. Input command lines
```text
python3 prediction_probability.py -n your/output/filename -d your/test/dir -o your/output/dir
```

4. Get your prediction result! 
