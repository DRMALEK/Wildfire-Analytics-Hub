# Wildfire Vision Research Resources 🌳🔥

<p align="center">
  <img src="https://user-images.githubusercontent.com/27784386/127931404-22f76cc6-4d64-4b6a-aadd-2fc7e04b9df2.jpg" width="750px" height="400px"/>
</p>

A curated list of **computer vision** resources for wildfire understanding (fire/smoke detection, segmentation, tracking, and remote-sensing mapping), inspired by the heartbreaking wildfires in Turkey ❤️.

## Contents
- [Vision Research 🔬](#vision-research-)
  - [Surveys](#surveys)
  - [Fire/Smoke Detection (RGB/IR)](#firesmoke-detection-rgbir)
  - [Segmentation & Mapping (satellite/UAV)](#segmentation--mapping-satelliteuav)
  - [Change detection & damage assessment](#change-detection--damage-assessment)
  - [Multi-modal fusion](#multi-modal-fusion)
  - [UAVs & aerial vision](#uavs--aerial-vision)
- [Vision Datasets 📊](#vision-datasets-)
  - [Ground RGB (images)](#ground-rgb-images)
  - [Aerial/UAV (images & video)](#aerialuav-images--video)
  - [Satellite / Remote sensing](#satellite--remote-sensing)
  - [Curated lists](#curated-lists)
- [Projects & Code 😎](#projects--code-)
- [APIs & Platforms 🤓](#apis--platforms-)
- [Forecasting / non-vision (optional)](#forecasting--non-vision-optional)
- [Contributing 🤝](#contributing-)
- [Author](#author)

---

## Vision Research 🔬

### Surveys
| Title | URL |
|---|---|
| A review of machine learning applications in wildfire science and management | https://arxiv.org/pdf/2003.00646v2.pdf |

### Fire/Smoke Detection (RGB/IR)
| Title | URL |
|---|---|
| Saliency Detection and Deep Learning-Based Wildfire Identification in UAV Imagery | https://www.mdpi.com/1424-8220/18/3/712/html |
| Detecting natural disasters, damage, and incidents in the wild | https://arxiv.org/pdf/2008.09188v1.pdf |
| Active Fire Detection in Landsat-8 Imagery: a Large-Scale Dataset and a Deep-Learning Study | https://arxiv.org/pdf/2101.03409v2.pdf |
| FIRe-GAN: A novel Deep Learning-based infrared-visible fusion method for wildfire imagery | https://arxiv.org/pdf/2101.11745v2.pdf |

### Segmentation & Mapping (satellite/UAV)
| Title | URL |
|---|---|
| Wildfire Segmentation on Satellite Images using Deep Learning | https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9067475 |
| Near Real-Time Wildfire Progression Monitoring with Sentinel-1 SAR Time Series and Deep Learning | https://www.nature.com/articles/s41598-019-56967-x |

### Change detection & damage assessment
| Title | URL |
|---|---|
| Monitoring the Impact of Wildfires on Tree Species with Deep Learning | https://arxiv.org/pdf/2011.02514v2.pdf |

### Multi-modal fusion
| Title | URL |
|---|---|
| FIRe-GAN: A novel Deep Learning-based infrared-visible fusion method for wildfire imagery | https://arxiv.org/pdf/2101.11745v2.pdf |

### UAVs & aerial vision
| Title | URL |
|---|---|
| Coordinated Control of UAVs for Human-Centered Active Sensing of Wildfires | https://arxiv.org/pdf/2006.07969v1.pdf |
| Image-based Guidance of Autonomous Aircraft for Wildfire Surveillance and Prediction | https://arxiv.org/pdf/1810.02455v2.pdf |
| Distributed Wildfire Surveillance with Autonomous Aircraft using Deep Reinforcement Learning | https://arxiv.org/pdf/1810.04244v1.pdf |
| Safe Coordination of Human-Robot Firefighting Teams | https://arxiv.org/pdf/1903.06847v1.pdf |

---

## Vision Datasets 📊

### Ground RGB (images)
| Data type | Title | URL |
|---|---|---|
| Kaggle - Images - RGB | Forest Fire | https://www.kaggle.com/kutaykutlu/forest-fire |
| General - Images - RGB | UCI Forest Fires (data.world mirror) | https://data.world/uci/forest-fires |
| General - Mixed (images/videos) | Wildfire dataset portal | http://wildfire.fesb.hr/ |

### Aerial/UAV (images & video)
| Data type | Title | URL |
|---|---|---|
| UAV - RGB/Thermal + Segmentation | FLAME 2 Wildfire Dataset | https://arazi2.github.io/aisends.github.io/publication/FLAME%202%20Wildfire%20Dataset |
| UAV - Detection + Smoke Segmentation | Boreal Forest Fire dataset (paper) | https://www.nature.com/articles/s41597-025-05634-0 |
| UAV - Dataset landing page | Boreal Forest Fire dataset record (Fairdata/ETSIN) | https://etsin.fairdata.fi/dataset/1dce1023-493a-4d63-a906-f2a44f831898 |

### Satellite / Remote sensing
| Data type | Title | URL |
|---|---|---|
| General - Active Fires (NRT + archive) | NASA FIRMS (MODIS/VIIRS active fire detections) | https://firms.modaps.eosdis.nasa.gov |
| General - Remote Sensing (GEE-ready) | FIRMS in Google Earth Engine | https://developers.google.com/earth-engine/datasets/catalog/FIRMS |
| General - Burn Severity (Landsat-derived) | MTBS Burn Severity Portal | https://burnseverity.cr.usgs.gov/products/mtbs |
| General - Burn Severity (GEE-ready) | MTBS annual burn severity mosaics (GEE) | https://developers.google.com/earth-engine/datasets/catalog/USFS_GTAC_MTBS_annual_burn_severity_mosaics_v1 |
| General - Fire dynamics (global) | Global Fire Atlas | https://www.earthdata.nasa.gov/data/catalog/ornl-cloud-cms-global-fire-atlas-1642-1 |
| General - Images - Remote Sensing | Wildfires tracked by MN DNR | https://gisdata.mn.gov/dataset/env-wildfires-tracked-by-mndnr |

### Curated lists
| Data type | Title | URL |
|---|---|---|
| Github - Mixed | awesome-wildfire | https://github.com/ubc-lib-geo/awesome-wildfire |

---

## Projects & Code 😎
| Project Title | URL |
|---|---|
| Collection of resources for fire-detection using Nueral nets | https://github.com/robmarkcole/fire-detection-from-images |
| Computer vision library for wildfire detection | https://github.com/pyronear/pyro-vision |
| Using U-Net Model to Detect Wildfire from Satellite Imagery | https://github.com/yueureka/WildFireDetection |
| Wildfire Detection with Deep Neural Networks | https://github.com/tomek-l/fire-detect-nn |
| Smoke-Detection-using-Tensorflow 2.2 | https://github.com/abg3/Smoke-Detection-using-Tensorflow-2.2 |
| Hermes (DeepStream accelerated wildfire detection) | https://github.com/kn1ghtf1re/Hermes-Deepstream |

---

## APIs & Platforms 🤓
| Project Title | URL |
|---|---|
| WIFIRE (UC San Diego) | https://wifire.ucsd.edu/ |
| Spotfire (crowd-sourcing for detection/monitoring) | https://github.com/AhmedMaghawry/SPOFI |
| API for wildfire prevention, detection & monitoring | https://github.com/pyronear/pyro-api |
| Detection & monitoring platform of wildfires | https://github.com/pyronear/pyro-platform |

---

## Forecasting / non-vision (optional)
| Title | URL |
|---|---|
| FireCast: Leveraging Deep Learning to Predict Wildfire Spread | https://www.ijcai.org/Proceedings/2019/0636.pdf |
| Deep Learning Models for Predicting Wildfires from Historical Remote-Sensing Data | https://arxiv.org/pdf/2010.07445v3.pdf |
| Modeling Wildfire Perimeter Evolution using Deep Neural Networks | https://arxiv.org/pdf/2009.03977v1.pdf |
| A 3D Convolutional Neural Network for Predicting Wildfire Profiles | https://openreview.net/pdf?id=aia4HejvBmY |
| Dense Forecasting of Wildfire Smoke Particulate Matter Using Sparsity Invariant Convolutional Neural Networks | https://arxiv.org/pdf/2009.11362v1.pdf |
| From Static to Dynamic Prediction: Wildfire Risk Assessment Based on Multiple Environmental Factors | https://arxiv.org/pdf/2103.10901v1.pdf |
| RtFPS: An Interactive Map that Visualizes and Predicts Wildfires in the US | https://arxiv.org/pdf/2105.10880v2.pdf |
| An insight into machine-learning algorithms to model human-caused wildfire occurrence | https://doi.org/10.1016/j.envsoft.2014.03.003 |
| EscapeWildFire: Assisting People to Escape Wildfires in Real-Time | https://arxiv.org/pdf/2102.11558v1.pdf |
| Reinforcement Learning based Proactive Control for Transmission Grid Resilience to Wildfire | https://arxiv.org/pdf/2107.05756v1.pdf |
| Slash or burn: Power line and vegetation classification for wildfire prevention | https://arxiv.org/pdf/2105.03804v1.pdf |

---

## Contributing 🤝
- If there's anything you think should be included here, you can submit an issue and I'll check it out.
- When adding a paper/dataset, please place it in the most specific vision subsection (Detection vs Segmentation vs Remote sensing).

## Author
@DRMALEK
