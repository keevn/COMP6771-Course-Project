# COMP6771-Course-Project
COMP6771 Course Project : 

Multi-class surface defect classification on 3D concrete printing structures using deep learning

ABSTRACT

Quality control and monitoring are essential aspects of every fabrication process. 3D concrete printing is an automated construction process that utilizes cement-based materials to create physical objects in a layer-by-layer manner. Layers with inappropriate properties and imbalance between the load and stiffness could bring large deformations or even cause the structure to collapse. Cross-sectional deformation, presence of tearing, or cracking are a few examples of defects that are visible in the fresh or harden state of the printed element. During the fresh state, those defects can be identified and prevented from happening again by closely monitoring the procedure. In this paper a multi-class surface defect classification on 3D concrete printing structures is attempted using convolutional neural networks. Images from the harden state of 3D printed walls were used to generate the image database using the sliding window technique. The dataset is divided into four classes: one with good surface quality and three more with tearing, chemical reaction, or cracking. Due to the small and imbalanced available dataset, data augmentation and oversampling were implemented. Five models are compared in total, including the four pre-trained models AlexNet, VGG-16, ResNet18, and GoogleNet using transfer learning, and a custom convolutional neural network. The confusion matrix is used as the evaluation metric. 

ACKNOWLEDGMENTS

We extend sincere gratitude to Ms. Claudiane Ouellet-Plamondon, Mr. Jean-Francois Caron, Ms. Eva Dokladalova and Mr. Rodrigo Rill Garcia for providing the photos used in the study.