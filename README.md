# Benchmark dataset for semantic segmentation
This site hosts a benchmark dataset for multi-class semantic segmentation of electroluminescence (EL) imagess of silicon wafer-based solar cells. The original dataset was created on 2021-11-04 and used in a paper submission. [reference] The dataset consists of 593 EL images of solar cells originating from three (3) private and two (2) public sources. The three private sources include: 1) The CSIR Energy Centre, a PV module test lab in South Africa where the research and development was conducted ; 2) CFV Labs, a PV module test lab in the United States; and 3) ARTsolar, a PV module manufacturer in South Africa. The public dataset includes images selected from the larger datasets previously publishded by CWRU SDLE Research Center and ZAE Bayern. 

Links:
CSIR Energy Centre PV Module Quality and Reliability Lab video (https://www.youtube.com/watch?v=OGP2u6_1-cg)
CFV Labs website                                               (https://www.cfvlabs.com)
ARTsolar website                                               (https://artsolar.net/)
CWRU SDLE Research Center dataset                              (https://osf.io/4qrtv/)
ZAE Bayern dataset                                             (https://github.com/zae-bayern/elpv-dataset)


There are twenty-four (24) classes labelled in the original dataset: twelve (12) intrinsic features of wafer-based solar cells and twelve (12) extrinsic defects. The 'ListOfClassesAndColorCodes.csv' lists the 24 classes along with the unique RGB codes used to label the ground truth masks. The benchmark dataset contains a roughly equal number of images from multi-crystalline and mono-crystalline cells. 

Some examples of the EL images and corresponding ground truyh images are shown below. 

![image](https://user-images.githubusercontent.com/26845062/165531501-1606bdbb-8155-4d84-9568-bd7df862a7d4.png)
