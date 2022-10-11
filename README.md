# CNN Segmentation Models and Microscopy Image Detection for Sole Neural Cell


Neural cell instance segmentation, which aims at joint detection and segmentation of every neural cell in a microscopic image, is essential to many neuroscience applications. The challenge of this task involves cell adhesion, cell distortion, unclear cell contours, low-contrast cell protrusion structures, and background impurities. Consequently, current instance segmentation methods generally fall short of precision.

Accurate cell counting provides key quantitative feedback and plays key roles in biological research as well as in industrial and biomedical applications. Unfortunately, the commonly used manual counting method is time-intensive, poorly standardized, and non-reproducible. The straightforward approach for determining cell counts is to develop an object detection and segmentation model, which incorporates key determining characteristic combinations of morphological features such as cell size, color value, and cell spacing. Object detection and segmentation have been an import research focus in the computer vision field and many popular algorithms have been proposed in recent years such as Fast R-CNN, YOLO, and U-Net. While biological image analysis has entered the era of artificial intelligence with the utilization of approaches such as computer vision methods and deep convolutional networks because segmenting small objects is a notoriously difficult problem.

Neurological disorders, including neurodegenerative diseases such as Alzheimer’s and brain tumors, are a leading cause of death and disability across the globe. However, it is hard to quantify how well these deadly disorders respond to treatment. One accepted method is to review neuronal cells via light microscopy, which is both accessible and non-invasive. Unfortunately, segmenting individual neuronal cells in microscopic images can be challenging and time-intensive. Accurate instance segmentation of these cells — with the help of computer vision — could lead to new and effective drug discoveries to treat the millions of people with these disorders.

Study of nervous systems via the connectome, the map of connectivities of all neurons in that system, is a challenging problem in neuroscience. Towards this goal, neurobiologists are acquiring large electron microscopy datasets. However, the shear volume of these datasets renders manual analysis infeasible. Hence, automated image analysis methods are required for reconstructing the connectome from these very large image collections. Segmentation of neurons in these images, an essential step of the reconstruction pipeline, is challenging because of noise, anisotropic shapes and brightness, and the presence of confounding structures.

Current solutions have limited accuracy for neuronal cells in particular. In internal studies to develop cell instance segmentation models, the neuroblastoma cell line SH-SY5Y consistently exhibits the lowest precision scores out of eight different cancer cell types tested. This could be because neuronal cells have a very unique, irregular and concave morphology associated with them, making them challenging to segment with commonly used mask heads. In this project I was able to train and test deep learning models using contrast microscopy images. The model has achieved accuracy of 94% with 6% loss percentage. The performance of this model can be enhanced by using UNET, Canet, Pytorch, Wand, Keras , TFPredict models similar to other participants.The model is used to detect distinct objects in biological neural cell images. The model successfully depicts delineate cells in neural images.



#     


For further data and to review the code you can see the head of the project's page on the below link :

https://github.com/Alireza-Rahimi-3000/CNN-Segmentation-Models-and-Microscopy-Image-Detection-for-Sole-Neural-Cell
