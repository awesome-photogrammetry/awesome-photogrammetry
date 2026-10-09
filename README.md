![Awesome Photogrammetry](./img/logo.svg)

This repo is a collection of AWESOME photogrammetry projects, applications, tools, resources. [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Items marked with ![Open-Source Software][OSS Icon] are open-source software and link to the source code. Items marked with ![Commercial Software][Money Icon] are nonfree and may cost money to use.

Feel free to **contribute** / **star** / **fork** / **pull request** . Any **recommendations** and **suggestions** are welcome.

# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Definition](#definition)
  - [Photogrammetric software](#photogrammetric-software)
  - [Structure from motion (SFM) software](#structure-from-motion-sfm-software)
  - [Gaussian splatting software](#gaussian-splatting-software)
  - [Calibration software](#calibration-software)
  - [Least squares optimization libraries](#least-squares-optimization-libraries)
  - [Datasets and benchmarks](#datasets-and-benchmarks)
  - [Journals](#journals)
  - [Conference proceedings](#conference-proceedings)
  - [Books](#books)
  - [Introductory and review papers](#introductory-and-review-papers)
  - [Courses and tutorials](#courses-and-tutorials)
  - [Scientific conferences](#scientific-conferences)
  - [Related awesome lists](#related-awesome-lists)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Definition

Definition of **photogrammetry** according to K. Schindler and W. Förstner:

> "Photogrammetry is the science and technology of obtaining information about the physical environment from images, with a focus on applications in surveying, mapping and high-precision metrology. The aim of photogrammetry is to provide automated or semi-automated procedures for these engineering tasks, with emphasis on a specified accuracy, reliability, and completeness of the information."

Source: [Photogrammetry](https://ethz.ch/content/dam/ethz/special-interest/baug/igp/photogrammetry-remote-sensing-dam/documents/pdf/Papers/Photogrammetry%202020.pdf) by K. Schindler and W. Förstner (2020). In: [Computer Vision: A Reference Guide, 2nd edition](https://www.springer.com/gp/book/9783030634155).

## Photogrammetric software

* ![Commercial Software][Money Icon] [3DF Zephyr](https://www.3dflow.net/3df-zephyr-photogrammetry-software/) - Photogrammetry software for automatic 3D reconstruction from photos
* ![Commercial Software][Money Icon] [Agisoft Metashape](https://www.agisoft.com) - Process digital images and generate 3D spatial data
* ![Commercial Software][Money Icon] [Beholder Desktop](https://beholder.vision/desktop) - Easy to use photogrammetry software, free for personal, non-commercial use. Also available as a SaaS.
* ![Commercial Software][Money Icon] [ContextCapture](https://www.bentley.com/software/contextcapture/) - Produce 3D models of existing conditions from photographs and/or point clouds
* ![Open-Source Software][OSS Icon] [Meshroom](https://alicevision.org)[![GitHub stars](https://img.shields.io/github/stars/alicevision/Meshroom.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/alicevision/Meshroom) - A user-friendly 3D Computer Vision software
* ![Open-Source Software][OSS Icon] [MicMac](https://micmac.ensg.eu)[![GitHub stars](https://img.shields.io/github/stars/micmacIGN/micmac.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/micmacIGN/micmac/) - A free open-source photogrammetric suite that can be used in a variety of 3D reconstruction scenarios
* ![Open-Source Software][OSS Icon] [MVE](https://github.com/simonfuhrmann/mve) [![GitHub stars](https://img.shields.io/github/stars/simonfuhrmann/mve.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/simonfuhrmann/mve/) - Includes Structure from Motion, Multi-View Stereo and Surface Reconstruction
* ![Open-Source Software][OSS Icon] [OpenDroneMap](https://github.com/OpenDroneMap/ODM) [![GitHub stars](https://img.shields.io/github/stars/OpenDroneMap/ODM.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/OpenDroneMap/ODM/) - An open source command line toolkit for processing aerial drone imagery
* ![Commercial Software][Money Icon] [PhotoModeler](https://www.photomodeler.com) - Precise measurements and 3D models from photographs
* ![Commercial Software][Money Icon] [Pix4D](https://www.pix4d.com) - A unique photogrammetry software suite for mobile and drone mapping
* ![Commercial Software][Money Icon] [PixPro](https://www.pix-pro.com) - Professional photogrammetry for everyone
* ![Commercial Software][Money Icon] [RealityCapture](https://www.capturingreality.com) - The state-of-the-art photogrammetry software solution that is changing the industry
* ![Commercial Software][Money Icon] [SURE by nFrames](https://www.nframes.com) - Software for 3D reconstruction from images with unique performance and flexibility
* ![Open-Source Software][OSS Icon] [TeleSculptor](https://github.com/Kitware/TeleSculptor) [![GitHub stars](https://img.shields.io/github/stars/Kitware/TeleSculptor.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/Kitware/TeleSculptor/) - A cross-platform desktop application for photogrammetry
* ![Commercial Software][Money Icon] [Trimble Inpho](https://geospatial.trimble.com/products-and-solutions/inpho) - Industry Leading Software for Digital Photogrammetry
* ![Open-Source Software][OSS Icon] [WebODM](https://github.com/OpenDroneMap/WebODM) [![GitHub stars](https://img.shields.io/github/stars/OpenDroneMap/WebODM.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/OpenDroneMap/WebODM/) - User-friendly, commercial-grade software for processing aerial imagery

## Structure from motion (SFM) software

* ![Open-Source Software][OSS Icon] [AliceVision](https://github.com/alicevision/AliceVision) [![GitHub stars](https://img.shields.io/github/stars/alicevision/AliceVision.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/alicevision/AliceVision/) - 3D Computer Vision framework including Structure-from-Motion, Multi-View Stereo and surface reconstruction
* ![Open-Source Software][OSS Icon] [BoofCV](https://boofcv.org/) [![GitHub stars](https://img.shields.io/github/stars/lessthanoptimal/boofcv.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/lessthanoptimal/BoofCV/) - Includes SFM, Multi-View Stereo, Android Support and various calibration tasks
* ![Open-Source Software][OSS Icon] [Bundler](https://github.com/snavely/bundler_sfm/) [![GitHub stars](https://img.shields.io/github/stars/snavely/bundler_sfm.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/snavely/bundler_sfm/) - SFM system for unordered image collections
* ![Open-Source Software][OSS Icon] [COLMAP](https://colmap.github.io/index.html) [![GitHub stars](https://img.shields.io/github/stars/colmap/colmap.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/colmap/colmap/) - Structure-from-Motion and Multi-View Stereo
* ![Open-Source Software][OSS Icon] [openMVG](https://github.com/openMVG/openMVG) [![GitHub stars](https://img.shields.io/github/stars/openMVG/openMVG.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/openMVG/openMVG/) - Multiple View Geometry library
* ![Open-Source Software][OSS Icon] [openMVS](https://github.com/cdcseacave/openMVS) [![GitHub stars](https://img.shields.io/github/stars/cdcseacave/openMVS.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/cdcseacave/openMVS/) - Open Multi-View Stereo reconstruction library
* ![Open-Source Software][OSS Icon] [openSFM](https://github.com/mapillary/OpenSfM/) [![GitHub stars](https://img.shields.io/github/stars/mapillary/OpenSfM.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/mapillary/OpenSfM/) - Structure from Motion library written in Python
* ![Open-Source Software][OSS Icon] [VisualSFM](http://ccwu.me/vsfm/) - GUI application for 3D reconstruction using SFM

## Gaussian splatting software

* ![Open-Source Software][OSS Icon] [3D Gaussian Splatting (Inria reference)](https://github.com/graphdeco-inria/gaussian-splatting) [![GitHub stars](https://img.shields.io/github/stars/graphdeco-inria/gaussian-splatting.svg?style=social&label=Star&maxAge=2592000)](https://github.com/graphdeco-inria/gaussian-splatting/) - Reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" (SIGGRAPH 2023)
* ![Commercial Software][Money Icon] [DJI Terra](https://enterprise.dji.com/dji-terra) - Drone mapping software with built-in 3D Gaussian Splatting reconstruction alongside mesh and point cloud outputs
* ![Open-Source Software][OSS Icon] [gsplat](https://github.com/nerfstudio-project/gsplat) [![GitHub stars](https://img.shields.io/github/stars/nerfstudio-project/gsplat.svg?style=social&label=Star&maxAge=2592000)](https://github.com/nerfstudio-project/gsplat/) - CUDA-accelerated rasterization library for 3D Gaussian Splatting
* ![Open-Source Software][OSS Icon] [LichtFeld Studio](https://lichtfeld.io/) [![GitHub stars](https://img.shields.io/github/stars/MrNeRF/LichtFeld-Studio.svg?style=social&label=Star&maxAge=2592000)](https://github.com/MrNeRF/LichtFeld-Studio/) - Native desktop app to train, inspect, edit, automate, and export 3D Gaussian Splatting scenes
* ![Commercial Software][Money Icon] [Luma AI](https://lumalabs.ai/) - Cloud-based 3D Gaussian Splatting from smartphone photos and video
* ![Commercial Software][Money Icon] [MakeSplat](https://makesplat.com/) - Cloud 3D Gaussian Splatting from a single video, in the browser or through a REST API
* ![Open-Source Software][OSS Icon] [Nerfstudio](https://docs.nerf.studio/) [![GitHub stars](https://img.shields.io/github/stars/nerfstudio-project/nerfstudio.svg?style=social&label=Star&maxAge=2592000)](https://github.com/nerfstudio-project/nerfstudio/) - Research framework for training NeRF and 3D Gaussian Splatting models
* ![Open-Source Software][OSS Icon] [OpenSplat](https://github.com/pierotofy/OpenSplat) [![GitHub stars](https://img.shields.io/github/stars/pierotofy/OpenSplat.svg?style=social&label=Star&maxAge=2592000)](https://github.com/pierotofy/OpenSplat/) - Production-grade 3D Gaussian Splatting in C++ with CPU/GPU support for Windows, Mac, and Linux
* ![Commercial Software][Money Icon] [Polycam](https://poly.cam/tools/gaussian-splatting) - Mobile and cloud 3D scanning combining LiDAR, photogrammetry, and 3D Gaussian Splatting
* ![Commercial Software][Money Icon] [Postshot](https://www.jawset.com/) - Desktop app for reconstructing 3D scenes from photos and video using NeRF and 3D Gaussian Splatting, processed locally without cloud
* ![Commercial Software][Money Icon] [Scaniverse](https://scaniverse.com/) - On-device 3D Gaussian Splatting capture for iOS and Android (by Niantic)
* ![Open-Source Software][OSS Icon] [SuperSplat](https://superspl.at/) [![GitHub stars](https://img.shields.io/github/stars/playcanvas/supersplat.svg?style=social&label=Star&maxAge=2592000)](https://github.com/playcanvas/supersplat/) - Browser-based editor for 3D Gaussian Splatting scenes (by PlayCanvas)

## Calibration software

* ![Open-Source Software][OSS Icon] [camera_calibration](https://github.com/puzzlepaint/camera_calibration) [![GitHub stars](https://img.shields.io/github/stars/puzzlepaint/camera_calibration.svg?style=social&label=Star&maxAge=2592000)](https://github.com/puzzlepaint/camera_calibration/) - Accurate geometric camera calibration
* ![Open-Source Software][OSS Icon] [kalibr](https://github.com/ethz-asl/kalibr) [![GitHub stars](https://img.shields.io/github/stars/ethz-asl/kalibr.svg?style=social&label=Star&maxAge=2592000)](https://github.com/ethz-asl/kalibr/) - Multi-camera, visual-inertial and rolling shutter camera calibration toolbox
* ![Open-Source Software][OSS Icon] [mrcal](http://mrcal.secretsauce.net) [![GitHub stars](https://img.shields.io/github/stars/dkogan/mrcal.svg?style=social&label=Star&maxAge=2592000)](https://github.com/dkogan/mrcal/) - Toolkit for camera calibration and more

## Least squares optimization libraries

* ![Open-Source Software][OSS Icon] [Ceres solver](http://ceres-solver.org) [![GitHub stars](https://img.shields.io/github/stars/ceres-solver/ceres-solver.svg?style=social&label=Star&maxAge=2592000)](https://github.com/ceres-solver/ceres-solver) - C++ library for modeling and solving large, complicated optimization problems
* ![Open-Source Software][OSS Icon] [dlib/optimization](http://dlib.net/optimization.html) [![GitHub stars](https://img.shields.io/github/stars/davisking/dlib.svg?style=social&label=Star&maxAge=2592000)](https://github.com/davisking/dlib) - C++ toolkit which provides also functions for solving least-squares problems
* ![Open-Source Software][OSS Icon] [Eigen](http://eigen.tuxfamily.org) - C++ template library for linear algebra with a variety of built-in solvers and wrappers to external solvers
* ![Open-Source Software][OSS Icon] [g2o](https://github.com/RainerKuemmerle/g2o) [![GitHub stars](https://img.shields.io/github/stars/RainerKuemmerle/g2o?style=social&label=Star&maxAge=2592000)](https://github.com/RainerKuemmerle/g2o) - C++ framework for optimizing graph-based nonlinear error functions
* ![Open-Source Software][OSS Icon] [GTSAM](https://gtsam.org/) [![GitHub stars](https://img.shields.io/github/stars/borglab/gtsam?style=social&label=Star&maxAge=2592000)](https://github.com/borglab/gtsam) - C++ library for factor graphs and bayes networks optimizations towards SLAM, VO and SFM
* ![Open-Source Software][OSS Icon] [lmfit](https://lmfit.github.io/lmfit-py/) [![GitHub stars](https://img.shields.io/github/stars/lmfit/lmfit-py.svg?style=social&label=Star&maxAge=2592000)](https://github.com/lmfit/lmfit-py) - Python package which builds on and extends many of the optimization methods of [scipy.optimize](https://docs.scipy.org/doc/scipy/reference/optimize.html)
* ![Open-Source Software][OSS Icon] [scipy.optimize.least_squares](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.least_squares.html) [![GitHub stars](https://img.shields.io/github/stars/scipy/scipy.svg?style=social&label=Star&maxAge=2592000)](https://github.com/scipy/scipy) - Powerful least-squares optimization function for python
* ![Open-Source Software][OSS Icon] [SymForce](https://symforce.org) [![GitHub stars](https://img.shields.io/github/stars/symforce-org/symforce.svg?style=social&label=Star&maxAge=2592000)](https://github.com/symforce-org/symforce) - Fast symbolic computation, code generation, and nonlinear optimization for robotics
* ![Commercial Software][Money Icon] [Matlab/OptimizationToolbox](https://www.mathworks.com/products/optimization.html) - Toolbox for local optimizations, including functions for solving least squares problems

## Datasets and benchmarks

* [Bundle adjustment in the large](https://grail.cs.washington.edu/projects/bal/) - Bundle adjustment data sets for five different scenes (2010)
* [ETH3D](https://www.eth3d.net/) - Multi-view stereo benchmark with high-resolution images and accurate ground truth (2017)
* [Hessigheim 3D (H3D) benchmark](https://ifpwww.ifp.uni-stuttgart.de/benchmark/hessigheim/default.aspx) - Benchmark on semantic segmentation of high-resolution 3D point clouds and textured meshes (2021)
* [Tanks and Temples](https://www.tanksandtemples.org/) - Benchmark for image-based 3D reconstruction with realistic indoor and outdoor scenes (2017)

## Journals

* [ISPRS Journal of Photogrammetry and Remote Sensing](https://www.journals.elsevier.com/isprs-journal-of-photogrammetry-and-remote-sensing) — JIF 2024: 12.2
* [Remote Sensing of Environment](https://www.journals.elsevier.com/remote-sensing-of-environment) — JIF 2024: 11.4
* [IEEE Transactions on Geoscience and Remote Sensing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=36) — JIF 2024: 8.6
* [International Journal of Applied Earth Observation and Geoinformation](https://www.sciencedirect.com/journal/international-journal-of-applied-earth-observation-and-geoinformation) — JIF 2024: 8.6
* [IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4609443) — JIF 2024: 5.3
* [IEEE Geoscience and Remote Sensing Letters](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8859) — JIF 2024: 4.4
* [Remote Sensing](https://www.mdpi.com/journal/remotesensing) — JIF 2024: 4.1
* [The Photogrammetric Record](https://onlinelibrary.wiley.com/journal/14779730) — JIF 2024: 3.6
* [PFG – Journal of Photogrammetry, Remote Sensing and Geoinformation Science](https://www.springer.com/journal/41064) — JIF 2024: 3.3
* [Photogrammetric Engineering & Remote Sensing (PE&RS)](https://www.asprs.org/asprs-publications/pers) — JIF 2024: 2.0
* [Open ISPRS Journal of Photogrammetry and Remote Sensing](https://www.journals.elsevier.com/isprs-open-journal-of-photogrammetry-and-remote-sensing) — JIF: n/a

Last update of [Journal Impact Factors (Clarivate JCR 2024)](https://en.wikipedia.org/wiki/Impact_factor): 2026-05-18

See also:

* [Top cited journals/proceedings at Google Scholar for Remote Sensing](https://scholar.google.com/citations?view_op=top_venues&hl=en&vq=eng_remotesensing)

## Conference proceedings

* [ISPRS Annals](https://www.isprs.org/publications/annals.aspx)
* [ISPRS Archives](https://www.isprs.org/publications/archives.aspx)

## Books

* [Close-Range Photogrammetry and 3D Imaging](https://www.degruyter.com/view/title/539949) by T. Luhmann, S. Robson, S. Kyle and J. Boehm (2014)
* [Observations and Least Squares](https://www.amazon.com/Observations-Least-Squares-Edward-Mikhail/dp/0819123978) by E. Mikhail (1983)
* [Photogrammetric Computer Vision](https://www.springer.com/de/book/9783319115498) by W. Förstner and B. P. Wrobel (2016)
* [Photogrammetrie und Fernerkundung](https://www.springer.com/de/book/9783662470930) (german) by C. Heipke (editor) (2017)
* [Photogrammetry - Geometry from Images and Laser Scans](https://doi.org/10.1515/9783110892871) by K. Kraus (2011)

## Introductory and review papers

* [Deep learning in remote sensing applications: A meta-analysis and review](https://www.scopus.com/record/display.uri?eid=2-s2.0-85064709843&origin=inward&txGid=562dd2da004c4333bc90a079dba66d5f) by L. Ma et al. (2019)
* [Mathematical foundations of photogrammetry](https://www.research-collection.ethz.ch/handle/20.500.11850/93024) by K. Schindler (2014)
* [UAV for 3D mapping applications: a review](https://link.springer.com/article/10.1007/s12518-013-0120-x) by F. Nex and F. Remondino (2013)
* [Unmanned aerial systems for photogrammetry and remote sensing: A review](https://www.sciencedirect.com/science/article/pii/S0924271614000501) by I. Colomina and P. Molina (2014)

## Courses and tutorials

* ["Online Training – Photogrammetric Computer Vision" by Cyrill Stachniss at the University of Bonn](https://www.ipb.uni-bonn.de/online-training-pcv) (2021)
* ["Photogrammetry I" by Cyrill Stachniss at the University of Bonn](https://www.youtube.com/playlist?list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1) (2015)
* ["Photogrammetry II" by Cyrill Stachniss at the University of Bonn](https://www.youtube.com/playlist?list=PLgnQpQtFTOGQEXN2Qo571uvwIGNGAM8uf) (2020)

## Scientific conferences

* [ISPRS conferences](https://www.isprs.org/calendar/Default.aspx)

## Related awesome lists

* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) [![GitHub stars](https://img.shields.io/github/stars/jbhuang0604/awesome-computer-vision.svg?style=social&label=Star&maxAge=2592000)](https://github.com/jbhuang0604/awesome-computer-vision/)
* [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) [![GitHub stars](https://img.shields.io/github/stars/sacridini/Awesome-Geospatial.svg?style=social&label=Star&maxAge=2592000)](https://github.com/sacridini/Awesome-Geospatial/)
* [Awesome Lidar](https://github.com/szenergy/awesome-lidar) [![GitHub stars](https://img.shields.io/github/stars/szenergy/awesome-lidar.svg?style=social&label=Star&maxAge=2592000)](https://github.com/szenergy/awesome-lidar/)
* [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience) [![GitHub stars](https://img.shields.io/github/stars/softwareunderground/awesome-open-geoscience.svg?style=social&label=Star&maxAge=2592000)](https://github.com/softwareunderground/awesome-open-geoscience/)
* [Awesome Robotics](https://github.com/kiloreux/awesome-robotics) [![GitHub stars](https://img.shields.io/github/stars/kiloreux/awesome-robotics.svg?style=social&label=Star&maxAge=2592000)](https://github.com/kiloreux/awesome-robotics/)
* [Awesome 3D Reconstruction](https://github.com/openMVG/awesome_3DReconstruction_list) [![GitHub stars](https://img.shields.io/github/stars/openMVG/awesome_3DReconstruction_list.svg?style=social&label=Star&maxAge=2592000)](https://github.com/openMVG/awesome_3DReconstruction_list/)
* [Awesome Point Cloud Analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis) [![GitHub stars](https://img.shields.io/github/stars/Yochengliu/awesome-point-cloud-analysis.svg?style=social&label=Star&maxAge=2592000)](https://github.com/Yochengliu/awesome-point-cloud-analysis/)
* [Photogrammetry-Guide](https://github.com/mikeroyal/Photogrammetry-Guide) [![GitHub stars](https://img.shields.io/github/stars/mikeroyal/Photogrammetry-Guide.svg?style=social&label=Star&maxAge=2592000)](https://github.com/mikeroyal/Photogrammetry-Guide)

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgments

Icons created by <a href="https://www.flaticon.com/authors/pixel-perfect" title="Pixel perfect">Pixel perfect</a> and <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/de/" title="Flaticon"> www.flaticon.com</a>

[OSS Icon]: ./img/oss.svg
[Money Icon]: ./img/money.svg
