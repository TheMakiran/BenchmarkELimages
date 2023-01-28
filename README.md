# Benchmark dataset for semantic segmentation
This site hosts a benchmark dataset for multi-class semantic segmentation of electroluminescence (EL) imagess of silicon wafer-based solar cells. The dataset consists of EL images of solar cells originating from three (3) private and two (2) public sources. The three private sources include: 1) The CSIR Energy Centre, a PV module test lab in South Africa where the research and development was conducted ; 2) CFV Labs, a PV module test lab in the United States; and 3) ARTsolar, a PV module manufacturer in South Africa. The public dataset includes images selected from the larger datasets previously publishded by CWRU SDLE Research Center and ZAE Bayern. 

# Links
CSIR Energy Centre PV Module Quality and Reliability Lab video (https://www.youtube.com/watch?v=OGP2u6_1-cg)

CFV Labs website                                               (https://www.cfvlabs.com)

ARTsolar website                                               (https://artsolar.net/)

CWRU SDLE Research Center dataset                              (https://osf.io/4qrtv/)

ZAE Bayern dataset                                             (https://github.com/zae-bayern/elpv-dataset)

# Sample images
There are twenty-four (24) classes labelled in the original dataset: twelve (12) intrinsic features of wafer-based solar cells and twelve (12) extrinsic defects. The 'ListOfClassesAndColorCodes.csv' in the 'dataset_20211104' directory lists the 24 classes along with the unique RGB codes used to label the ground truth masks. The benchmark dataset contains a roughly equal number of images from multi-crystalline and mono-crystalline cells. The subsequent datasets include additional images, additional classes, and corrections to earlier versions of the same images. The corresponding 'ListOfClassesAndColorCodes.csv' are also included in each of database directories.   

Some examples of the EL images and corresponding ground truth masks are shown below. 

![image](https://user-images.githubusercontent.com/26845062/165531501-1606bdbb-8155-4d84-9568-bd7df862a7d4.png)

# Citations

Please, cite the following publications when publishing work based on these datasets.

For the 20211104 dataset, cite the following:
@article{pratt2021defect,
  title={Defect detection and quantification in electroluminescence images of solar PV modules using U-net semantic segmentation},
  author={Pratt, Lawrence and Govender, Devashen and Klein, Richard},
  journal={Renewable Energy},
  volume={178},
  pages={1211--1222},
  year={2021},
  publisher={Elsevier}
}

For the 20221008 dataset, cite the following:
@article{pratt2023benchmark,
  title={A benchmark dataset for defect detection and classification in electroluminescence images of PV modules using semantic segmentation},
  author={Pratt, Lawrence and Mattheus, Jana and Klein, Richard},
  journal={Systems and Soft Computing},
  pages={200048},
  year={2023},
  publisher={Elsevier}
}
