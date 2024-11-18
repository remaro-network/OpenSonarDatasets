# OpenSonarDatasets 🌊

Welcome to **OpenSonarDatasets**, a repository dedicated to consolidate open-source sonar datasets for underwater research and development. We encourage researchers in the field to expand the current collection, aiming to increase the visibility of open-source sonar datasets and provide an easier way to find and compare datasets.

### Why This Repository?
The lack of consolidated and accessible sonar datasets makes research in underwater robotics challenging. This repository aims to bridge that gap by offering an organized collection of open-source sonar datasets with their link repository to help researchers interested in open-source sonar datasets start their projects efficiently.

### Original Dataset Collection
This dataset comparison originates from the journal paper "Sonar-based DL in Underwater Robotics: Overview, Robustness, and Challenges," submitted to the IEEE Journal of Oceanic Engineering, which will soon be available. The initial datasets included here are part of this journal paper. However, please note that any future datasets contributed by the community will not be part of the original journal comparison, as the paper content remains fixed, while this repository will continue to evolve.

### Dataset Comparison Table
The following table compares the state-of-the-art sonar underwater datasets by analyzing the type of sonar (Sonar), type of data (Data), number of data samples (No Data), objects labeled in the data (Object Labels), if the data is annotated, DL tasks (Annotation), if the data collection set up such as sonar frequency, altitude, etc. are described in the dataset or not (Set-up), and finally the year of the dataset publication (Year). The * symbol indicates that the dataset is not only limited to sonar but extended to other sensors such as optical cameras.

In addition, for readability, the sonar acronyms are SSS (Side-Scan Sonar), FLS (Forward-Looking Sonar), MSIS (Mechanical Scanning Imaging Sonar), and MBES (Multi-Beam Echo Sounder) represent the different types of sonar used in these datasets.

| Dataset                    | Sonar     | Data       | No Data | Object labels                        | Annotation         | Set-up   | Year | Paper |
|----------------------------|-----------|------------|---------|--------------------------------------|--------------------|----------|------|------|
| [Northern Adriatic Reefs](https://doi.org/10.5281/zenodo.4608083)    | SSS       | GeoTIFF    | 7       | Reefs                                | ✗                  | ✓        | 2010 | ✗ |
| [Lago Grey](https://data.mendeley.com/datasets/jpz52pm9sc/1)                  | SSS       | Raw        | ✗       | Glacier, Walls                       | ✗                  | ✓        | 2019 | [Paper](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2018GL081441) |
| [UCI ML](https://doi.org/10.24432/C5T01Q)                     | ✓        | Raw        | 211     | Mines, Rocks                         | Classification     | ✗        | ✗    | ✗ |
| [SeabedObjects-KLSG](https://www.kaggle.com/datasets/enochkwatehdongbo/seabedobjects-klsg-dataset)         | SSS       | Images     | 1190    | Wrecks, Humans, Mines                | Classification     | ✗        | 2020 | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9026963) |
| [Marine_PULSE](https://doi.org/10.5281/zenodo.7922705)               | SSS       | Images     | 627     | Pipes, Mounds, Platforms             | Classification     | ✗        | 2023 | [Paper](https://www.researchgate.net/publication/374547500_Revealing_the_Potential_of_Deep_Learning_for_Detecting_Submarine_Pipelines_in_Side-Scan_Sonar_Images_An_Investigation_of_Pre-Training_Datasets) |
| [NKSID](https://github.com/Jorwnpay/Sonar-OLTR)                      | FLS       | Images     | 2617    | Infrastructures, Propellers, Tires   | Classification     | ✓        | 2024 | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417424003609?via%3Dihub) |
| [UATD](https://figshare.com/articles/dataset/UATD_Dataset/21331143/3)                       | FLS       | Images     | 9200    | Tires, Mannequins, Boxes             | Object Detection   | ✓        | 2022 | [Paper](https://www.nature.com/articles/s41597-022-01854-w) |
| [SSS for Mine Detection](https://figshare.com/articles/dataset/_i_Side-scan_sonar_imaging_for_Mine_detection_i_/24574879)     | SSS       | Images     | 1170    | Mines                                | Object Detection   | ✗        | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340924001045?dgcid=rss_sd_all) |
| [SWDD](https://zenodo.org/records/13692547)                       | SSS       | Images     | 7904    | Walls                                | Object Detection   | ✓        | 2024 | [Paper](https://arxiv.org/abs/2410.10554#:~:text=14%20Oct%202024%5D-,ROSAR%3A%20An%20Adversarial%20Re%2DTraining%20Framework%20for%20Robust,Side%2DScan%20Sonar%20Object%20Detection&text=This%20paper%20introduces%20ROSAR%2C%20a,underwater%20vehicles%20using%20sonar%20sensors.) |
| [SubPipe](https://zenodo.org/records/12666132)                    | SSS *     | Images     | 10030   | Pipelines                            | Object Detection   | ✓        | 2024 | [Paper](https://ieeexplore.ieee.org/document/10682150) |
| [UXO](https://zenodo.org/records/13778485)                        | FLS       | Images/Raw | 74437   | Unexploded Ordnances                 | Object Detection   | ✓        | 2024 | [Paper](https://www.researchgate.net/publication/384061712_An_Acoustic_and_Optical_Dataset_for_the_Perception_of_Underwater_Unexploded_Ordnance_UXO) |
| [MDT](https://github.com/mvaldenegro/marine-debris-fls-datasets)                        | FLS       | Images     | 2471    | Infrastructures, Debris              | Segmentation       | ✓        | 2021 | [Paper](https://www.semanticscholar.org/paper/The-Marine-Debris-Dataset-for-Forward-Looking-Sonar-Singh-Valdenegro-Toro/e6a16a2dbc11b25d8f2dd778532bf510178e6049) |
| [SASSED](https://data.mendeley.com/datasets/s5j5gzr2vc/4)                     | SAS       | Images     | 129     | Muds, Sea Grass, Rocks, Sands        | Segmentation       | ✗        | 2023 | ✗  |
| [Seafloor Sediments](https://zenodo.org/records/10209445)         | SSS       | Images     | 434164  | Rocks, Marine life                   | Segmentation       | ✓        | 2023 | [Paper](https://www.sciencedirect.com/science/article/pii/S0029801823020310) |
| [DIDSON](https://smithsonian.figshare.com/articles/dataset/DIDSON_fish_data_and_code_for_analysis/19611510)                     | FLS       | Images     | 1000| Fishes Species                      | Segmentation       | ✓     | 2022    | [Paper](https://www.mdpi.com/2073-4441/13/9/1304) |
| [AI4Shipwreck](https://umfieldrobotics.github.io/ai4shipwrecks/)               | SSS       | Images     | 286     | Shipwrecks                           | Segmentation       | ✓        | 2024 | [Paper](https://journals.sagepub.com/doi/10.1177/02783649241266853) |
| [Cave Sonar](https://cirs.udg.edu/caves-dataset/)                 | MSIS *    | Rosbag     | 500 meters       | Cave Seabed                          | SLAM               | ✓        | 2017 | [Paper](https://journals.sagepub.com/doi/pdf/10.1177/0278364917732838) | 
| [Aurora](https://ieee-dataport.org/open-access/aurora-multi-sensor-dataset-robotic-ocean-exploration)                     | MBES, SSS * | Raw      | MBES: 81km, SSS: 15h       | Seabed, Marine habitats             | SLAM               | ✓        | 2020 | [Paper](https://nora.nerc.ac.uk/id/eprint/532651/1/AURORA__A_multi_sensor_dataset_for_robotic_ocean_exploration.pdf) | 
| [MBES-Slam](https://seaward.science/data/pos/)                  | MBES      | Rosbag     | 4 missions      | Seabed                               | SLAM               | ✓        | 2022 | [Paper](https://journals.sagepub.com/doi/full/10.1177/02783649211044749) |



### Contributing

We welcome contributions from the community! If you have an open-source sonar dataset that you would like to add to this repository, please create a pull request with the line description for the dataset table and the dataset link (and, if any, the published paper). This repository does not store the datasets but is a central directory to find links to most available datasets. By contributing, you help create a central location for researchers to easily access and compare sonar datasets, ultimately benefiting the field of underwater robotics.

## Acknowledgements
This project has received funding from the European Union's Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement No. 956200.

This work is part of the Reliable AI for Marine Robotics (REMARO) Project. For more info, please visit: https://remaro.eu/

![Remaro-logo](images/remaro-right-1024.png "Remaro-logo")
