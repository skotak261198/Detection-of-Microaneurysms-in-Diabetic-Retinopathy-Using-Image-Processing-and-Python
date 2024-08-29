# Detection of Microaneurysms in Diabetic Retinopathy Using Image Processing and Python

## Abstract

Diabetic retinopathy (DR) is a leading cause of blindness among the working-age population worldwide. It is an eye disease that arises due to long-standing untreated diabetes, which can lead to vision impairment if not detected and treated in a timely manner. Early detection of DR, particularly the identification of microaneurysms, is crucial to prevent blindness. Microaneurysms are tiny swellings in the blood vessels of the retina that can rupture and leak blood, marking the onset of diabetic retinopathy.

Our project aims to detect microaneurysms in retinal images to assist in the early diagnosis of diabetic retinopathy using image processing techniques and Python. We have developed an algorithm specifically designed to detect these microaneurysms and have tested it on the DiaretDB1 database, which provides ground truth data for all images.

## Project Overview

The primary goal of this project is to develop an automated method to detect microaneurysms in retinal images, which can aid in the early screening of diabetic retinopathy. By detecting these initial indicators, the progression to more severe stages of diabetic retinopathy can be slowed or even halted, thereby preventing blindness.

## Methodology

The detection of microaneurysms in retinal images involves several image processing steps, each crucial for accurately identifying the tiny aneurysms in the blood vessels of the retina. The steps are as follows:

1. **Image Acquisition**: Obtain high-quality retinal images for analysis.
2. **Green Channel Extraction and CLAHE**: Extract the green channel from the retinal images and apply Contrast Limited Adaptive Histogram Equalization (CLAHE) to enhance contrast.
3. **Sequential Filtering**: Apply a series of image filters to remove noise and enhance features that are relevant to detecting blood vessels and microaneurysms.
4. **Blood Vessel Detection**: Use image processing techniques to detect blood vessels in the retina.
5. **Blood Vessel Extraction**: Extract detected blood vessels from the processed image to isolate potential microaneurysms.
6. **Thresholding**: Apply thresholding techniques to distinguish microaneurysms from other features in the image.
7. **Microaneurysm Detection**: Identify and mark microaneurysms based on the processed image data.

## Dataset

The algorithm has been tested on the publicly available DiaretDB1 database, which provides annotated retinal images with ground truth labels for microaneurysms and other features. This dataset is essential for validating the accuracy and effectiveness of the proposed detection algorithm.
