# Project Title: Development of an integrated framework for SCADA-based condition monitoring and fault detection of wind turbines, incorporating image analysis and trend monitoring techniques.
This repository contains the official implementation and source code for the research project.

## 📌 Paper Abstract
Accurate power prediction is essential for assessing wind turbine performance under real-world operating conditions and for supporting condition monitoring and maintenance planning using SCADA data. Most existing approaches rely directly on raw SCADA signals, which may limit their ability to capture complex spatiotemporal dependencies among operational variables. To address this limitation, this paper proposes a novel SCADA-driven power prediction framework that transforms selected SCADA variables into multi-channel grayscale images and leverages an optimized LeNet-5–LSTM hybrid neural network for active and reactive power prediction. First, the SCADA dataset is analyzed to identify the most influential variables affecting power output. Six key variables are then selected, segmented, and encoded as 2D grayscale images, enabling the model to learn richer feature representations compared to conventional raw SCADA data-based methods. The proposed network combines convolutional layers for spatial feature extraction from SCADA data-based grayscale images with LSTM layers to capture temporal dependencies. Model training incorporates a customized loss function that integrates both data-driven supervision and physics-based constraints. The model is trained using 70% of the image-based dataset, with five independent runs to ensure robustness and reproducibility, while the remaining 30% is used for testing. The proposed approach is validated using SCADA data from three real-world cases: (i) a 2 MW Siemens wind turbine in Poland, (ii) a Vestas V52 wind turbine in Ireland, and (iii) the La Haute Borne wind farm in France, consisting of four wind turbines. The results demonstrate that the SCADA-based image representation enables the proposed LeNet-5–LSTM model to effectively learn discriminative feature patterns and achieve accurate active and reactive power predictions across different turbine types and operating conditions.

## 📊 Datasets Used
The following datasets were utilized for training and validation in this study:

* **[Dataset]**: [Vestas V52 Wind Turbine].  
    🔗 **Link:** [[Insert URL here](http://doi.org/10.17632/tm988rs48k.1)]
    🔗 **Link:** [[Insert URL here](http://doi.org/10.17632/tm988rs48k.2)]

