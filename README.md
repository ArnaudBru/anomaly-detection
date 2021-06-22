# anomaly-detection
Master Project - Anomaly Detection in Industrial Imaging

Anomaly detection is a vast research topic used in many sectors of the economy: finance, health, industry. The applications are also diverse, ranging from video surveillance to bank fraud detection and medical diagnosis. Numerous methods have been developed, particularly in the supervised case where the training data is already labelled "normal" or "abnormal". Our study does not fit into this framework because the images we will process have no label, as already specified, we are in the unsupervised framework.
More precisely, we are in the "novelty detection" framework where the aim is to recognise test data that deviate significantly from the normal data seen during training.
There are now a large number of deep learning methods for anomaly detection and localisation that have demonstrated significantly better performance than conventional methods. Generally speaking, we can classify them into two main categories, which are reconstruction-based methods and embedding similarity-based methods.

We have chosen to implement 5 different algorithms in order to compare the results on two datasets: mvtec and gdxray:

