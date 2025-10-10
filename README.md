# Overview
The diversity of plant species in a garden ecosystem reflects the complex ecological interactions that are essential for maintaining environmental balance. Traditional classification methods, primarily based on convolutional neural networks (CNNs), often struggle to capture fine-grained features, limiting their effectiveness in biodiversity monitoring. Considering these limitations, this study integrates Vision Transformers (ViTs) with K-means clustering for comprehensive plant species classification. ViTs are employed for deep feature extraction, capturing complex spatial dependencies across diverse ecological zones, while K-means clustering groups species into coherent clusters.

## About Code Files
**1:** **Augmentation_data_generation_using_GAN.py:** Use this file to generate the Holistic Garden images using GANs. </br>
**2:** **Augmentation_data_generation_using_GAN_v2.py:**  Use this code file to generate more diverse images of each class using GANs. </br>
**3:** **k_mean_clustering.py** This file contains all the code that we used for K-means clustering and also includes the code for selecting the optimal value of K for K-means clustering using the Elbow method.</br>
**4:** **Labeling-folders.py** This code includes how to assign labeling to each class image and organize them in separate folders.</br>
**5:** **Proposed_VisionNet.py** This file contains the code of the proposed ViT model (End-to-end code including Data Loading, Pre-processing, Model Training and Model Testing).</br>

## Contributing
Contributions to this implementation are highly appreciated. Whether it's suggesting improvements, reporting bugs, or proposing new features, feel free to open an issue or submit a pull request.

## Citation
The paper is currently under review. 
