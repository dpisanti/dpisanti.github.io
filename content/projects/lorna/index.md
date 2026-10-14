---
title: "LoRNA: Long-range Navigation for Mars Helicopters"
summary: "Vision-based map-relative localization for next-generation Mars rotorcraft. NASA JPL, 2023 to 2024."
weight: 30
---

**Role:** Visiting Student Researcher, Mobility and Robotics Systems, NASA Jet Propulsion Laboratory (Feb 2023 to Dec 2024)

LoRNA studies how next-generation Mars rotorcraft can fly long distances without GNSS. The key capability is map-relative localization: registering images from the onboard navigation camera to georeferenced orbital maps, even when the Sun lights the terrain very differently from the moment the map was acquired.

## Contributions

- **Geo-LoFTR.** I conceived and developed a geometry-aided deep learning model for image registration that fuses orbital imagery and elevation data through cross-attention, improving robustness to large changes in illumination and scale.
- **Map-based localization pipeline.** I implemented a pipeline that uses Geo-LoFTR to register navigation images onto orbital maps, improving localization accuracy at 1 m by up to 31.8% over prior methods under challenging illumination.
- **MARTIAN.** I built an open-source Blender framework that synthesizes pose-annotated aerial Mars imagery from HiRISE orbital data, and used it to generate a dataset of 150k labeled examples.
- **Embedded deployment.** I adapted and benchmarked learning-based localization on NVIDIA Jetson AGX Xavier and ModalAI VOXL 2, using ONNX and the Qualcomm Neural Processing SDK.

## Outputs

- [Geo-LoFTR project page](https://dpisanti.github.io/geo-loftr/)
- Papers at [ICRA 2026](https://ieeexplore.ieee.org/abstract/document/11696980), the [ICRA 2026 Workshop on Perceptual Challenges for Planetary Exploration](https://arxiv.org/abs/2605.29647) (Best Poster Award) and [IEEE Transactions on Field Robotics](https://doi.org/10.1109/TFR.2025.3612364)
- Code: [MbL-Mars](https://github.com/nasa-jpl/mbl_mars) and [MARTIAN](https://github.com/nasa-jpl/martian); [trained weights](https://huggingface.co/dpisanti/mbl-mars); [dataset](https://doi.org/10.48577/jpl.7JFBOE)
