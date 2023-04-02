# Annotated-Apple-Leaf-Disease-Dataset-for-Mask-RCNN

About:
This dataset contains annotated images of apple leaves with different diseases from the PlantVillage
dataset, which can be used for image segmentation-based research. The Mask RCNN annotation style is 
used. This dataset will aid in accurately locating the damage on the leaves, which is necessary for 
predicting the severity of the disease.

Black Rot, Apple Scab, and Cedar Apple Rust are the three diseases that have been annotated. 
This annotated dataset can be used to find diseases on apple leaves by using image segmentation.

The data was annotated using MakeSense.AI, an open-source image annotation application. 
Annotating the damage on the leaves was done with the Rect tool. Annotation files are saved in.xml 
format with the two diagonally positioned corners of the bounding boxes. Various colors are used 
for various classes when labeling.

A total of 850 images have been annotated. 680 images are kept in the train folder, and 170 images
 are in the valid folder.

The folder structure is as follows:

![image](https://user-images.githubusercontent.com/122490814/229361865-a641b063-dece-4f7d-80e9-863ffc38db7b.png)

If you are using this dataset or found any of this information contributing towards your research, 
please cite: 

1. @InProceedings{10.1007/978-3-031-18872-5_5,
author="Mitra, Alakananda
and Mohanty, Saraju P.
and Kougianos, Elias",
editor="Camarinha-Matos, Luis M.
and Ribeiro, Luis
and Strous, Leon",
title="A Smart Agriculture Framework to Automatically Track the Spread of Plant Diseases Using Mask Region-Based Convolutional Neural Network",
booktitle="Internet of Things. IoT through a Multi-disciplinary Perspective",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="68--85",
isbn="978-3-031-18872-5"
}

2. @InProceedings{10.1007/978-3-031-18872-5_1,
author="Mitra, Alakananda
and Mohanty, Saraju P.
and Kougianos, Elias",
editor="Camarinha-Matos, Luis M.
and Ribeiro, Luis
and Strous, Leon",
title="aGROdet: A Novel Framework for Plant Disease Detection and Leaf Damage Estimation",
booktitle="Internet of Things. IoT through a Multi-disciplinary Perspective",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="3--22",
isbn="978-3-031-18872-5"
}

3. Original PlantVillage Dataset: 
@article{DBLP:journals/corr/HughesS15,
Author = {David P. Hughes and
           Marcel Salath{'{e} } },
Title = {An open access repository of images on plant health to enable the
           development of mobile disease diagnostics through machine
           learning and crowdsourcing},
journal   = {CoRR},
volume    = {abs/1511.08060},
year      = {2015},   
url       = {http://arxiv.org/abs/1511.08060},
archivePrefix = {arXiv},
eprint    = {1511.08060},
timestamp = {Mon, 13 Aug 2018 16:48:21 +0200},
biburl    = {https://dblp.org/rec/bib/journals/corr/HughesS15},
bibsource = {dblp computer science bibliography, https://dblp.org}
}
