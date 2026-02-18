# ArchaeoSightDesktop

ArchaeoSight is a cross-platform mobile application built to assist archaeologists in the field by integrating data from pXRF spectrometers, GPS, and image analysis. It leverages machine learning to predict potential anthropogenic hotspots and enables offline-first functionality to ensure usability in remote locations. Developed in Flutter, ArchaeoSight aims to modernize how field data is collected, analyzed, and visualized.

ArchaeoSightDesktop is meant to serve as a Python rewrite of the mobile app, allowing for direct integration with Python's rich supply of ML libraries, as well as Python's kriging libraries. Unlike the mobile app, the desktop version will allow users to train their own models and upload them to the central model hub, download other models, as well as use the built in kriging functionality. 

The two model format's we will support for the start are Gradient Boosted Decision Trees and Autoencoders+HDBSCAN models. 
