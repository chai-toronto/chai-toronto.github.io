---
title: 'ChromaFlash: Snapshot Hyperspectral Imaging Using Rolling Shutter Cameras'
authors: 
- dhruv_verma
- ian_ruffolo
- David B. Lindell
- Kiriakos N. Kutulakos
- mariakakis
venue: $IMWUT$
date: 2024-09-09
link: https://doi.org/10.1145/3678582
thumbnail: /images/pubs/chromaflash.png
abstract: |
  Hyperspectral imaging captures scene information across narrow, contiguous bands of the electromagnetic spectrum. Despite its proven utility in industrial and biomedical applications, its ubiquity has been limited by bulky form factors, slow capture times, and prohibitive costs. In this work, we propose a generalized approach to snapshot hyperspectral imaging that only requires a standard rolling shutter camera and wavelength-adjustable lighting. The crux of this approach entails using the rolling shutter as a spatiotemporal mask, varying incoming light quicker than the camera's frame rate in order for the captured image to contain rows of pixels illuminated at different wavelengths. An image reconstruction pipeline then converts this coded image into a complete hyperspectral image using sparse optimization. We demonstrate the feasibility of this approach by deploying a low-cost system called ChromaFlash, which uses a smartphone's camera for image acquisition and a series of LEDs to change the scene's illumination. We evaluated ChromaFlash through simulations on two public hyperspectral datasets and assessed its spatial and spectral accuracy across various system parameters. We also tested the real-world performance of our prototype by capturing diverse scenes under varied ambient lighting conditions. In both experiments, ChromaFlash outperformed state-of-the-art techniques that use deep learning to convert RGB images into hyperspectral ones, achieving snapshot performance not demonstrated by prior attempts at accessible hyperspectral imaging.
category:
- Active Sensing
devices:
- Smartphone
skills:
- Computer Vision
- Hardware
---
