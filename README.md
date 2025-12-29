# Thermal Infrared (TIR) Image Datasets

A curated list of publicly available thermal infrared image datasets for computer vision research and applications.

## Table of Contents

- [Object Detection & Tracking](#object-detection--tracking)
- [Pedestrian Detection](#pedestrian-detection)
- [Semantic Segmentation](#semantic-segmentation)
- [Scene Understanding](#scene-understanding)
- [Face & Person Recognition](#face--person-recognition)
- [Multi-Modal Datasets](#multi-modal-datasets)
- [Building Analysis](#building-analysis)
- [Contributing](#contributing)
- [License](#license)

## Object Detection & Tracking

### FLIR ADAS Dataset
- **Description**: Large-scale thermal infrared dataset for autonomous driving applications with over 10,000 annotated thermal images
- **Link**: [FLIR ADAS Dataset](https://www.flir.com/oem/adas/adas-dataset-form/)
- **Key Features**: Pre-labeled objects (person, bike, car, etc.), day/night scenarios, aligned RGB-thermal pairs
- **Paper**: N/A (Industry dataset)
- **Additional Modalities**: Includes aligned RGB images

### OSU Color-Thermal Database
- **Description**: Sequences of thermal infrared imagery paired with color images for object tracking
- **Link**: [OSU Thermal Database](http://vcipl-okstate.org/pbvs/bench/)
- **Key Features**: 50 sequences, synchronized color-thermal pairs, various lighting conditions
- **Paper**: N/A
- **Additional Modalities**: Includes synchronized color/RGB images

### KAIST Multispectral Pedestrian Dataset
- **Description**: Multispectral dataset with thermal infrared images captured from a vehicle with RGB-Thermal camera pairs
- **Link**: [KAIST Dataset](https://soonminhwang.github.io/rgbt-ped-detection/)
- **Key Features**: 95,328 densely annotated pedestrian instances, day/night scenarios, campus and city environments
- **Paper**: "Multispectral Pedestrian Detection: Benchmark Dataset and Baseline" (CVPR 2015)
- **Additional Modalities**: Includes aligned RGB images

## Pedestrian Detection

### CVC-14 Thermal-RGBD Dataset
- **Description**: Thermal infrared image sequences with RGB-D for pedestrian detection
- **Link**: [CVC-14 Dataset](http://adas.cvc.uab.es/elektra/enigma-portfolio/cvc-14-visible-fir-day-night-pedestrian-sequence-dataset/)
- **Key Features**: Day/night sequences, thermal-RGB-Depth fusion
- **Paper**: N/A
- **Additional Modalities**: Includes RGB and depth images

### OTCBVS Benchmark Dataset Collection
- **Description**: Collection of thermal infrared and visible imagery for various computer vision tasks
- **Link**: [OTCBVS](http://vcipl-okstate.org/pbvs/bench/)
- **Key Features**: Multiple datasets including pedestrian detection, segmentation, and tracking
- **Paper**: N/A (Collection of multiple datasets)
- **Additional Modalities**: Includes visible/RGB images

## Semantic Segmentation

### MF Dataset (Multi-spectral Fusion)
- **Description**: Urban scenes with thermal infrared and RGB imagery for semantic segmentation
- **Link**: [MF Dataset](https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/)
- **Key Features**: Pixel-level annotations, 9 object categories, challenging urban scenarios
- **Paper**: "MFNet: Towards Real-Time Semantic Segmentation for Autonomous Vehicles with Multi-Spectral Scenes" (IROS 2017)
- **Additional Modalities**: Includes RGB images

### PST900 Dataset
- **Description**: Thermal infrared and RGB dataset for semantic segmentation in indoor/outdoor environments
- **Link**: [PST900 Dataset](https://github.com/ShreyasSkandanS/pst900_thermal_rgb)
- **Key Features**: 894 RGB-thermal image pairs, 4 object classes, diverse environmental conditions
- **Paper**: "PST900: RGB-Thermal Calibration, Dataset and Segmentation Network" (ICRA 2020)
- **Additional Modalities**: Includes RGB images

## Scene Understanding

### SODA Dataset (Salient Object Detection in Adverse Conditions)
- **Description**: Thermal images for salient object detection
- **Link**: [SODA Dataset](https://github.com/zwbx/SODA)
- **Key Features**: 1,900 thermal images with pixel-level annotations
- **Paper**: "Salient Object Detection in Thermal Images" (ACM MM 2020)

## Face & Person Recognition

### Tufts Face Database
- **Description**: Multi-modal face database including thermal infrared imagery
- **Link**: [Tufts Face Database](https://www.cs.tufts.edu/~face/publications/)
- **Key Features**: 10,000+ images, multiple modalities (visible, thermal, 3D), various poses and expressions
- **Paper**: "A Comprehensive Database for Benchmarking Imaging Systems" (BTAS 2016)
- **Additional Modalities**: Includes visible images and 3D models

### IRIS Thermal/Visible Face Database
- **Description**: Dual-spectrum face database with thermal infrared and visible images for recognition research
- **Link**: [IRIS Database](http://www.cse.ohio-state.edu/otcbvs-bench/)
- **Key Features**: Thermal and visible face images under various conditions
- **Paper**: N/A
- **Additional Modalities**: Includes visible images

## Multi-Modal Datasets

### LLVIP Dataset (Low-Light Visible-Infrared Paired)
- **Description**: Paired visible and thermal infrared images for low-light vision tasks
- **Link**: [LLVIP Dataset](https://bupt-ai-cz.github.io/LLVIP/)
- **Key Features**: 30,976 aligned visible-infrared image pairs, captured in low-light environments
- **Paper**: "LLVIP: A Visible-infrared Paired Dataset for Low-light Vision" (ICCV 2021)
- **Additional Modalities**: Includes visible images

### M³FD Dataset (Multi-Modal Multi-Scene Fusion Detection)
- **Description**: Large-scale thermal infrared and RGB dataset for object detection
- **Link**: [M³FD Dataset](https://github.com/dlut-dimt/TarDAL)
- **Key Features**: 4,200 image pairs, 6 object categories, diverse scenes
- **Paper**: "Target-aware Dual Adversarial Learning and a Multi-scenario Multi-Modality Benchmark To Fuse Infrared and Visible for Object Detection" (CVPR 2022)
- **Additional Modalities**: Includes RGB images

### VEDAI Dataset (Vehicle Detection in Aerial Imagery)
- **Description**: Aerial imagery dataset with thermal infrared and visible spectrums
- **Link**: [VEDAI Dataset](https://downloads.greyc.fr/vedai/)
- **Key Features**: 1,210 image pairs, 9 vehicle categories, aerial perspective
- **Paper**: "Vehicle Detection in Aerial Imagery: A small target detection benchmark" (Journal of Visual Communication and Image Representation 2016)
- **Additional Modalities**: Includes visible spectrum images

## Building Analysis

### Building Energy Efficiency & Thermal Anomaly Detection

#### TBBRv2 Dataset (KIT)
- **Description**: Thermal infrared images for thermal bridge and rooftop detection in buildings
- **Link**: [TBBRv2 on Zenodo](https://zenodo.org/record/7650746)
- **Key Features**: 917 images with 6,895 annotations, benchmark for building thermal analysis
- **Paper**: N/A (Dataset release)
- **Additional Modalities**: Includes RGB and Height Map (2.5D point cloud)

#### TBBR Dataset (Thermal Building Boundary Recognition)
- **Description**: Thermal infrared images for building detection and boundary recognition
- **Link**: [TBBR Dataset](https://github.com/looooongChen/TBBR)
- **Key Features**: Building façade thermal images, boundary annotations, architectural analysis
- **Paper**: "Building Extraction from Remote Sensing Images with Sparse Token Transformers" (Remote Sensing 2021)
- **Additional Modalities**: May include range images

#### Thermal Anomaly Dataset (KIT District Heating)
- **Description**: Thermal infrared images for pipeline leak detection in district heating systems
- **Link**: [KIT Thermal Anomaly Dataset](https://publikationen.bibliothek.kit.edu/1000183573)
- **Key Features**: UAV thermal imagery for district heating network analysis, validates deep learning vs traditional vision
- **Paper**: Available at KITopen
- **Additional Modalities**: N/A

#### Windows-detect Dataset
- **Description**: Thermal infrared images for building facade analysis focusing on windows and walls
- **Link**: [Windows-detect on Roboflow](https://universe.roboflow.com/windows-detect)
- **Key Features**: Indoor and outdoor thermal infrared features of building elements (windows, walls)
- **Paper**: N/A
- **Additional Modalities**: N/A

### 3D Thermal Infrared Point Cloud Datasets

#### PointER Dataset (Points for Energy Renovation)
- **Description**: Large-scale 3D building point cloud dataset linked to energy renovation (framework extensible for thermal infrared mapping)
- **Link**: [PointER Dataset](https://github.com/kdmayer/PointER)
- **Key Features**: Over 1 million buildings with 3D point clouds, geometry and energy efficiency certificate (EPC) linkage
- **Paper**: Available on GitHub
- **Additional Modalities**: Includes 3D point clouds, energy performance data (thermal infrared extension supported)

#### ArCH Dataset (Architectural Cultural Heritage)
- **Description**: 3D RGB point cloud dataset for semantic segmentation of architectural heritage (research extensions include thermal infrared mapping)
- **Link**: [ArCH Dataset](https://github.com/HajarHajipourgolpayegan/ArCH)
- **Key Features**: RGB point clouds for ancient buildings, used in research for detecting thermal defects in heritage structures
- **Paper**: Research from University of Strasbourg
- **Additional Modalities**: Includes 3D RGB point clouds (thermal mapping available in research extensions)

#### TSDN Dataset (ThermalGS - Dynamic 3D Reconstruction)
- **Description**: Dynamic 3D thermal infrared reconstruction using Gaussian Splatting technique
- **Link**: [TSDN Dataset (MDPI)](https://www.mdpi.com/2072-4292/17/2/335)
- **Key Features**: UAV-captured 3D dynamic thermal distribution, suitable for studying building thermal response over time
- **Paper**: "ThermalGS: Dynamic 3D Thermal Reconstruction" (Remote Sensing)
- **Additional Modalities**: Includes 3D dynamic reconstruction data

### Multi-Modal Urban Datasets

#### KIT & Munich UAV Thermal Dataset
- **Description**: UAV-based thermal infrared imagery for urban scene analysis
- **Link**: [KIT Campus Dataset](http://www.cvlibs.net/datasets/karlsruhe_sequences/)
- **Key Features**: Aerial thermal imagery, urban environments, multi-sensor data
- **Paper**: N/A (Multiple datasets from KIT research)
- **Additional Modalities**: May include lidar point clouds, 3D models

#### TUM2TWIN Dataset
- **Description**: TUM (Technical University of Munich) multi-modal dataset for digital twin creation
- **Link**: [TUM2TWIN](https://www.asg.ed.tum.de/en/gis/research/datasets/)
- **Key Features**: Building-focused thermal imagery, registration with other modalities
- **Paper**: "TUM2TWIN: A Digital Twin Integrating Geodetic Monitoring for Risk Assessment of Transport Infrastructure" (Remote Sensing 2023)
- **Additional Modalities**: Includes lidar point clouds, 3D models, range images

#### TUM-MLS2016 Dataset
- **Description**: Mobile laser scanning dataset with thermal infrared imagery
- **Link**: [TUM-MLS2016](https://www.asg.ed.tum.de/en/gis/research/datasets/)
- **Key Features**: Mobile mapping system data, thermal images, urban environments
- **Paper**: "The TUM-MLS-2016 Dataset" (ISPRS Annals 2017)
- **Additional Modalities**: Includes lidar point clouds, 3D models, range images

### Indoor & Occupancy Monitoring

#### Thermo-presence Dataset
- **Description**: Low-resolution thermal infrared sensor data for occupancy detection in office environments
- **Link**: [Thermo-presence Dataset](https://zenodo.org/record/4431435)
- **Key Features**: 24x32 resolution thermal infrared sensor data for personnel detection, optimized for HVAC energy efficiency
- **Paper**: Available on Zenodo
- **Additional Modalities**: N/A

#### Thermal-IM Dataset
- **Description**: Thermal infrared sequences for indoor human-machine interaction
- **Link**: [Thermal-IM Dataset](https://github.com/Thermal-IM/Thermal-IM-Dataset)
- **Key Features**: Indoor thermal infrared sequences for interaction analysis
- **Paper**: Available on GitHub
- **Additional Modalities**: N/A

## Contributing

Contributions are welcome! If you know of additional publicly available thermal infrared datasets, please:

1. Fork the repository
2. Add the dataset information following the existing format
3. Submit a pull request with a clear description

Please ensure the datasets you add are:
- Publicly available
- Properly cited with relevant papers/sources
- Have appropriate access links

## License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The datasets listed here have their own respective licenses. Please check individual dataset pages for their specific terms of use.
