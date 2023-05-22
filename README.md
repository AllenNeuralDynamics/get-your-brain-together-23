# Get Your Brain Together Hackathon 2023

This repository contains startup code to show <a href="https://insightsoftwareconsortium.github.io/GetYourBrainTogether/HCK02_2023_Allen_Institute_Hybrid/">hackathon</a> participants how to perform basic processing of example data.

## Available Scripts

Processing techniques are available in [Jupyter Notebooks](https://jupyter.org/). You can interact with notebooks in the following ways:
1. View non-interactively in CodeOcean and launch a reproducible run;
2. Launch an interactive Jupyter session in CodeOcean;
3. Download notebooks and run them locally on your PC.

The following notebooks are available:
- `RegisterToCCF`: Demonstrates a reproducible process to read in a downsampled, stitched SmartSPIM image and then run registration to map from SmartSPIM image space to the Common Coordinate Framework (CCF) atlas.

![SmartSPIM image compared with CCF atlas](code/images/smartspim-after-reorient.png)

- `LocalFetchFromS3`: Demonstrates how to fetch stitched SmartSPIM image data from AWS S3 if working outside of the CodeOcean platform.

- `ApplyTransformToPointSet`: Demonstrates how to apply the transform stack result from the `RegisterToCCF` image registration pipeline to point set data.

![SmartSPIM point set annotation](code/images/point-set-annotation.png)

## Tips and Tricks

We will collect useful tips for working with SmartSPIM data and registration pipelines here during the hackathon. If you find a useful hint during your work, let us know to share it here!

## Frequently Asked Questions

Check back soon for answers to common questions.
