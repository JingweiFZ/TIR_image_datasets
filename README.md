# Thermal Infrared (TIR) Image Datasets

A curated list of publicly available thermal infrared image datasets for computer vision research and applications.

## Table of Contents

- [Object Detection & Tracking](#object-detection--tracking)
- [Pedestrian Detection](#pedestrian-detection)
- [Semantic Segmentation](#semantic-segmentation)
- [Scene Understanding](#scene-understanding)
- [Face & Person Recognition](#face--person-recognition)
- [Multi-Modal Datasets](#multi-modal-datasets)
- [Other Applications](#other-applications)
- [Contributing](#contributing)
- [License](#license)

## Object Detection & Tracking

### FLIR ADAS Dataset
- **Description**: Large-scale thermal dataset for autonomous driving applications with over 10,000 annotated thermal images
- **Link**: [FLIR ADAS Dataset](https://www.flir.com/oem/adas/adas-dataset-form/)
- **Key Features**: Pre-labeled objects (person, bike, car, etc.), day/night scenarios, aligned RGB-thermal pairs
- **Paper**: N/A (Industry dataset)

### OSU Color-Thermal Database
- **Description**: Sequences of color and thermal imagery for object tracking
- **Link**: [OSU Thermal Database](http://vcipl-okstate.org/pbvs/bench/)
- **Key Features**: 50 sequences, synchronized color-thermal pairs, various lighting conditions
- **Paper**: N/A

### KAIST Multispectral Pedestrian Dataset
- **Description**: Multispectral dataset captured from a vehicle with RGB-Thermal camera pairs
- **Link**: [KAIST Dataset](https://soonminhwang.github.io/rgbt-ped-detection/)
- **Key Features**: 95,328 densely annotated pedestrian instances, day/night scenarios, campus and city environments
- **Paper**: "Multispectral Pedestrian Detection: Benchmark Dataset and Baseline" (CVPR 2015)

## Pedestrian Detection

### CVC-14 Thermal-RGBD Dataset
- **Description**: Thermal and RGB-D sequences for pedestrian detection
- **Link**: [CVC-14 Dataset](http://adas.cvc.uab.es/elektra/enigma-portfolio/cvc-14-visible-fir-day-night-pedestrian-sequence-dataset/)
- **Key Features**: Day/night sequences, thermal-RGB-Depth fusion
- **Paper**: N/A

### OTCBVS Benchmark Dataset Collection
- **Description**: Collection of thermal and visible imagery for various computer vision tasks
- **Link**: [OTCBVS](http://vcipl-okstate.org/pbvs/bench/)
- **Key Features**: Multiple datasets including pedestrian detection, segmentation, and tracking
- **Paper**: Various papers

## Semantic Segmentation

### MF Dataset (Multi-spectral Fusion)
- **Description**: Urban scenes with RGB and thermal imagery for semantic segmentation
- **Link**: [MF Dataset](https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/)
- **Key Features**: Pixel-level annotations, 9 object categories, challenging urban scenarios
- **Paper**: "MFNet: Towards Real-Time Semantic Segmentation for Autonomous Vehicles with Multi-Spectral Scenes" (IROS 2017)

### PST900 Dataset
- **Description**: RGB-Thermal dataset for semantic segmentation in indoor/outdoor environments
- **Link**: [PST900 Dataset](https://github.com/ShreyasSkandanS/pst900_thermal_rgb)
- **Key Features**: 894 RGB-thermal image pairs, 4 object classes, diverse environmental conditions
- **Paper**: "PST900: RGB-Thermal Calibration, Dataset and Segmentation Network" (ICRA 2020)

## Scene Understanding

### SODA Dataset (Salient Object Detection in Adverse Conditions)
- **Description**: Thermal images for salient object detection
- **Link**: [SODA Dataset](https://github.com/zwbx/SODA)
- **Key Features**: 1,900 thermal images with pixel-level annotations
- **Paper**: "Salient Object Detection in Thermal Images" (ACM MM 2020)

## Face & Person Recognition

### Tufts Face Database
- **Description**: Multi-modal face database including thermal imagery
- **Link**: [Tufts Face Database](https://www.cs.tufts.edu/~face/publications/)
- **Key Features**: 10,000+ images, multiple modalities (visible, thermal, 3D), various poses and expressions
- **Paper**: "A Comprehensive Database for Benchmarking Imaging Systems" (BTAS 2016)

### IRIS Thermal/Visible Face Database
- **Description**: Dual-spectrum face database for recognition research
- **Link**: [IRIS Database](http://www.cse.ohio-state.edu/otcbvs-bench/)
- **Key Features**: Thermal and visible face images under various conditions
- **Paper**: N/A

## Multi-Modal Datasets

### LLVIP Dataset (Low-Light Visible-Infrared Paired)
- **Description**: Paired visible and infrared images for low-light vision tasks
- **Link**: [LLVIP Dataset](https://bupt-ai-cz.github.io/LLVIP/)
- **Key Features**: 30,976 aligned visible-infrared image pairs, captured in low-light environments
- **Paper**: "LLVIP: A Visible-infrared Paired Dataset for Low-light Vision" (ICCV 2021)

### M³FD Dataset (Multi-Modal Multi-Scene Fusion Detection)
- **Description**: Large-scale RGB-infrared dataset for object detection
- **Link**: [M³FD Dataset](https://github.com/dlut-dimt/TarDAL)
- **Key Features**: 4,200 image pairs, 6 object categories, diverse scenes
- **Paper**: "Target-aware Dual Adversarial Learning and a Multi-scenario Multi-Modality Benchmark To Fuse Infrared and Visible for Object Detection" (CVPR 2022)

### VEDAI Dataset (Vehicle Detection in Aerial Imagery)
- **Description**: Aerial imagery dataset with infrared and visible spectrums
- **Link**: [VEDAI Dataset](https://downloads.greyc.fr/vedai/)
- **Key Features**: 1,210 image pairs, 9 vehicle categories, aerial perspective
- **Paper**: "Vehicle Detection in Aerial Imagery: A small target detection benchmark" (Journal of Visual Communication and Image Representation 2016)

## Other Applications

### TerraSAR-X Dataset
- **Description**: Thermal infrared images for various remote sensing applications
- **Link**: Various sources - check research papers
- **Key Features**: High-resolution thermal imagery, remote sensing applications
- **Paper**: Various

### UAV-Based Thermal Dataset
- **Description**: Thermal images captured from UAV platforms
- **Link**: Various sources - check research papers
- **Key Features**: Aerial thermal imagery, various applications (agriculture, search & rescue, etc.)
- **Paper**: Various

### Thermal Pedestrian Tracking Benchmark
- **Description**: Benchmark dataset for tracking pedestrians in thermal imagery
- **Link**: [Tracking Benchmark](http://www.cvlibs.net/datasets/)
- **Key Features**: Sequences with ground truth annotations
- **Paper**: Various

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
