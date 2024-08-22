# Person Re-Identification (ReID) using AlignedReID Algorithm
</br >
This group project focuses on re-implementing and updating the AlignedReID algorithm, a state-of-the-art method for person re-identification (ReID) in multi-camera environments. Our implementation, performed in Google Colab, aims to reproduce the original results of the AlignedReID paper and address challenges related to system memory usage.
</br >

## Overview
</br >
Person re-identification (ReID) is a crucial task in mass surveillance, enabling the tracking of individuals across multiple camera feeds. The AlignedReID approach, which combines global and local features, provides a robust solution for matching identities across varying conditions, such as different camera angles, lighting, and occlusions.
</br >
</br >

## Features
- AlignedReID Implementation: Re-implemented using updated libraries and compatible with Google Colab.
- Datasets: Tested on the Market1501 and CUHK03 datasets.
- Memory Optimization: Leveraged CuPy to optimize RAM usage during dataset evaluation, enabling smooth operation in resource-limited environments.
</br >

## Datasets
- Market1501: Consists of 32,668 images from six cameras, with 1,501 identities.
- CUHK03: Contains 14,097 images from six cameras at a Chinese university, with 1,467 identities.

