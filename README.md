# htr-archives

This repository contains a collection of notebooks for HTR (Handwritten Text Recognition) including model training and inference with YOLOv9, trocr, pylaia, and htrflow. These models and tools form the basis of the transciptions shown in the NextJS/React/Supabase archive viewer [archives-app](https://https://archives-app.vercel.app).

## YOLOv9

YOLOv9 is a state-of-the-art object detection model that incorporates the latest techniques in deep learning and computer vision to achieve high accuracy and efficiency in real-time object detection tasks and segmentation. The model is designed to be lightweight and fast, making it suitable for deployment on various platforms.

[Ultralytics](https://github.com/ultralytics/ultralytics)

## pylaia

pylaia is a Python library for handwritten text recognition (HTR) that provides tools and models for training and evaluating HTR systems. 

[pylaia](https://gitlab.teklia.com/atr/pylaia)

## htrflow

htrflow is a framework for building HTR pipelines based on yaml configuration files. it easily integrates with SOTA models and allow  

[htrflow](https://github.com/AI-Riksarkivet/htrflow)

## trocr

trocr is a transformer-based model for text recognition that leverages the power of transformers to achieve state-of-the-art performance on various HTR benchmarks. It is designed to be efficient and scalable, making it suitable for large-scale HTR tasks. trocr includes pre-trained models, data preprocessing utilities, and evaluation metrics to facilitate the development of HTR applications.

(trocr)[https://huggingface.co/docs/transformers/model_doc/trocr]

## Datasets

The finetuning of the trocr was performed on homemade datasets datasets from [CATMuS](https://huggingface.co/CATMuS)

## Resources

Models and datasets can be found at [https://huggingface.co/sylvain471](https://huggingface.co/sylvain471)
