# Bangla Handwritten Digit Recognition using CNN




### Problem Statement:
Currently, natural language processing (NLP) research is developing rapidly due to the rise of artificial intelligence (AI). One of the key topics of NLP is optical character recognition (OCR). To build an OCR in Bengali language, digit classification provides a convenient starting point. We have accumulated a large dataset (85,000+) of Bengali digits (NumtaDB) which can be used by researchers for benchmarking their algorithm.

In this competition, your goal is to correctly identify digits from NumtaDB. We encourage you to experiment with different algorithms to learn first-hand what works well and make comparison among them.



## Dataset description:
The dataset is a combination of six datasets that were gathered from different sources and at different times. However, each of them was checked rigorously under the same evaluation criterion so that all digits were at least legible to one human being without any prior knowledge. Descriptions of these datasets including collection methodology, image segmentation and extraction and image formats of these datasets are described in https://bengali.ai/datasets.

The sources are labeled from 'a' to 'f'. The training and testing sets have separate subsets depending on the source of the data (training-a, testing-a, etc.). All the datasets have been partitioned into training and testing sets so that handwriting from the same subject/contributor is not present in both. Dataset-f had no corresponding metadata for contributors for which all of it was added to the testing set (testing-f). The metric for the competition is selected to be the Unweighted Average Accuracy (UAA). Starter codes for the competition are available at https://github.com/BengaliAI.

Two augmented datasets (augmented from test images of dataset 'a' and 'c') are appended to the testing set which consists of the following augmentations:

Spatial Transformations: Rotation, Translation, Shear, Height/Width Shift, Channel Shift, Zoom.
Brightness, Contrast, Saturation, Hue shifts, Noise.
Occlusions.
Superimposition (to simulate the effect of text being visible from the other side of a page).
File descriptions
trainining-a.zip - images of training set a

trainining-b.zip - images of training set b

trainining-c.zip - images of training set c

trainining-d.zip - images of training set d

trainining-e.zip - images of training set e

testing-a.zip - images of testing set a

testing-b.zip - images of testing set b

testing-c.zip - images of testing set c

testing-d.zip - images of testing set d

testing-e.zip - images of testing set e

testing-f.zip - images of testing set f

testing-auga.zip - augmented images from testing set a

testing-augc.zip - augmented images from testing set c

trainining-a.csv - label for training set a

trainining-b.csv - label for training set b

trainining-c.csv - label for training set c

trainining-d.csv - label for training set d

trainining-e.csv - label for training set e

sampleSubmission.csv - a sample submission file in the correct format

UPDATE: The testing set consisted some illegible and ambiguous digits. These digits are replaced by legible digits of the same label. The new testing digits along with old legible ones are placed in testing-all-corrected.zip

