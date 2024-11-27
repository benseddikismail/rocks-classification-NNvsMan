# Rocks Classi
This study explores the intersection of neural networks and human cognition in classifying rocks by integrating deep learning techniques with psychological models of categorization. Its primary objective is to bridge the gap between machine learning and human cognition by employing deep learning representations of complex natural stimuli, such as rock images, as inputs for formal psychological classification models.

The research aims to achieve three key goals: derive psychological feature representations for natural stimuli using convolutional neural networks (CNNs), leverage these representations to predict human categorization behavior, and compare the performance of machine-generated models with human classification patterns.

Building on the approach outlined in [this paper](https://escholarship.org/content/qt3vj7j48f/qt3vj7j48f_noSplash_75f3343520483f0b92b5c4bcedccf2cc.pdf?t=sginq6), the study trains CNNs to predict Multidimensional Scaling (MDS) coordinates for rock images, representing psychological feature spaces derived from human similarity judgments. These CNN-derived features are then used within a formal psychological framework, the Generalized Context Model (GCM), to forecast human categorization behavior for rock types. Additionally, the study assesses the capacity of various dimensionality reduction techniques (e.g., PCA, t-SNE, MDS, LLE) and CNNs to capture meaningful feature spaces relevant for classification tasks. Human categorization data from a separate experiment, involving a new set of rock images, is compared to GCM predictions informed by CNN-derived features.

Discrepancies between human and machine classification reveal areas where CNNs fall short in capturing unique features that humans rely on, such as the porous texture characteristic of pumice. Despite these limitations, the study demonstrates that CNNs can effectively learn psychological feature spaces (MDS coordinates) from naturalistic stimuli like rock images, eliminating the need for extensive human similarity judgments. By integrating CNN-derived features with the GCM, this research bridges machine learning and cognitive science, offering a robust method for predicting human categorization behavior.

The analysis also delves into how different dimensionality reduction methods capture meaningful data structures, shedding light on feature interpretability and advancing our understanding of the relationship between machine-derived and human-perceived feature spaces.

## Data and Feature Representation
- ***Dataset:*** The dataset consists of 360 images of rocks from 30 categories (igneous, metamorphic, and sedimentary rocks). Each rock image has associated 8-dimensional coordinates derived from Multidimensional Scaling (MDS), which reflects psychological similarity judgments made by humans.
- ***MDS Dimensions:*** These dimensions include features like lightness/darkness, grain size, roughness/smoothness, chromaticity, hue, and shape-related components.



