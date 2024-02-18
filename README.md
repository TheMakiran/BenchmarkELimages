# Benchmark datasets for defect detection in EL images of solar cells using semantic segmentation
This site hosts benchmark datasets for multi-class semantic segmentation of electroluminescence (EL) imagess of silicon wafer-based solar cells. The dataset consists of EL images of solar cells originating from three (3) private and two (2) public sources. The three private sources include: 1) The CSIR Energy Centre, a PV module test lab in South Africa where the research and development was conducted ; 2) CFV Labs, a PV module test lab in the United States; and 3) ARTsolar, a PV module manufacturer in South Africa. The public dataset includes images selected from the larger datasets previously publishded by CWRU SDLE Research Center and ZAE Bayern. Please, cite the papers listed below when using these datasets in your own work. 

# Links
CSIR Energy Centre PV Module Quality and Reliability Lab video (https://www.youtube.com/watch?v=OGP2u6_1-cg)

CFV Labs website                                               (https://www.cfvlabs.com)

ARTsolar website                                               (https://artsolar.net/)

CWRU SDLE Research Center dataset                              (https://osf.io/4qrtv/)

ZAE Bayern dataset                                             (https://github.com/zae-bayern/elpv-dataset)

# Sample images
The 'dataset_20211104' folder contains a labelled dataset with twenty-four (24) classes: twelve (12) intrinsic features of wafer-based solar cells and twelve (12) extrinsic defects. The datasets contain a roughly equal number of images from multi-crystalline and mono-crystalline cells. The subsequent datasets include additional images, additional classes, and corrections to earlier versions of the same images.  The 'ListOfClassesAndColorCodes.csv' included in each database directory lists the 24 classes along with the unique RGB index used to label the ground truth masks. 

Some examples of the EL images and corresponding ground truth masks are shown below. 

![image](https://user-images.githubusercontent.com/26845062/165531501-1606bdbb-8155-4d84-9568-bd7df862a7d4.png)

# Folder structure
Each dataset folder has subfolders for EL images (train, val, test), ground truth masks (train, val, test), and the full-color (RGB) masks that were manually annotated using GIMP. The train subfolders include the original images/masks and augmented images/masks that were generated by flipping, rotating, and mirroring the originals. The ground truth masks contain an index from 0 to c-1 for each pixel, where c is the number of classes in the dataset. The index corresponds to the RGB color assigned to the class in the GIMP image. '0' is assigned to the background class colored black in the RGB images.  The color to index mapping for all classes is detailed in the csv file included in each subfolder. 

- dataset_YYYYMMDD
  - el_images_test   # el images for testing
  - el_images_train  # el images for training
  - el_images_val    # el images for validation
  - el_masks_rgb     # RGB ground truth masks for all EL images in the train, val, test folders
  - el_masks_test    # indexed ground truth masks for testing
  - el_masks_train   # indexed ground truth masks for testing
  - el_masks_val     # indexed ground truth masks for testing
 
# Unlabelled dataset
The 'dataset_unlabelled' folder includes of over 20,000 images of cells with padding cropped from module level images. 
  
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
