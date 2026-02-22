YOLOv11–EfficientViT: Unified Traffic Light and Sign Detection with State Recognition
- Overview

This repository contains the official PyTorch implementation of the paper:

"A Lightweight YOLOv11–EfficientViT Framework for Unified Traffic Light and Sign Detection with State Recognition"

The proposed framework integrates:

YOLOv11 backbone

Convolutional Block Attention Module (CBAM)

Efficient Vision Transformer (EfficientViT)

Joint multi-task learning for detection and state recognition

The model jointly performs:

Traffic light detection

Traffic sign detection

Traffic light state recognition (Red / Yellow / Green)

Experimental Datasets

BDD100K (Traffic Light Detection + State Recognition)

TT100K (Traffic Sign Detection)

LISA (Cross-dataset evaluation)

Bosch (Cross-dataset evaluation)

Curated subsets were used as described in the paper.
