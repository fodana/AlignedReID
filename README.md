
Person Re-Identification (ReID) using AlignedReID Algorithm
This project focuses on re-implementing and updating the AlignedReID algorithm, a state-of-the-art method for person re-identification (ReID) in multi-camera environments. Our implementation, performed in Google Colab, aims to reproduce the original results of the AlignedReID paper and address challenges related to system memory usage.

Overview
Person re-identification (ReID) is a crucial task in mass surveillance, enabling the tracking of individuals across multiple camera feeds. The AlignedReID approach, which combines global and local features, provides a robust solution for matching identities across varying conditions, such as different camera angles, lighting, and occlusions.

Features
AlignedReID Implementation: Re-implemented using updated libraries and compatible with Google Colab.
Datasets: Tested on the Market1501 and CUHK03 datasets.
Memory Optimization: Leveraged CuPy to optimize RAM usage during dataset evaluation, enabling smooth operation in resource-limited environments.
Datasets
Market1501: Consists of 32,668 images from six cameras, with 1,501 identities.
CUHK03: Contains 14,097 images from six cameras at a Chinese university, with 1,467 identities.
Installation and Usage
To run the code:

Open the Colab Notebook (replace with actual link).
Connect to a GPU runtime.
Run all cells to execute the algorithm. The process takes approximately 5-10 minutes.
Results
Market1501: Achieved 72.28% mean accuracy precision (mAP), 87.05% rank-1 accuracy (cmc1).
CUHK03: Performance was lower due to partial data transformation; a script to combine datasets was in progress but not completed.
Limitations
Time Constraints: Limited to half a semester, impacting the depth of implementation.
Dataset Availability: The Duke dataset was unavailable due to privacy issues.
Compatibility Challenges: Updated TensorFlow code to PyTorch, but some features (e.g., batch normalization) required modifications.
Conclusion
This project successfully re-implemented the AlignedReID algorithm, overcoming various technical challenges. The work showcases the potential applications of ReID in security and public safety, while also highlighting areas for future improvement, such as better dataset integration and full implementation of alternative algorithms.

