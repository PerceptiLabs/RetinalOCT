<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Retinal optical coherence tomography (OCT) classification

This dataset<sup>1</sup> contains images of retinal optical coherence tomography, a technique used to capture high-resolution cross sections of retinas that can be used to detect different diseases.

The data can be used to build and train an ML model that can detect ocular diseases.

# Structure

This repo contains the following structure:

- **data**: contains the images directories.
- **dataset.csv**: CSV file with all required data.

<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in **dataset.csv** that is used as the main example.

| **labels**  | **images** |
| CNV | data/train/CNV/CNV-451136-177.jpeg |
| CNV | data/train/CNV/CNV-6652117-103.jpeg |
| CNV | data/train/CNV/CNV-445726-65.jpeg  |
| CNV | data/train/CNV/CNV-6215140-132.jpeg |


The labels on CSV are:

- **CNV**: choroidal noevascularization
- **DME**: Diabetic macular edema
- **DRUSEN**: Multiple drusen present in early AMD
- **NORMAL**: Normal retina

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/paultimothymooney/kermany2018

