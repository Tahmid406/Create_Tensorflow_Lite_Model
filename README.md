# TensorFlow to TFLite Conversion

This repository contains a script to convert a pre-trained TensorFlow model into the **TFLite format**, enabling deployment on mobile devices or embedded systems.

## Features
- **Convert TensorFlow Models**: Easily transform `.pb` models into `.tflite` format.  
- **Optimize for Edge Devices**: Reduces model size and enhances inference speed for mobile and IoT applications.  
- **Customizable Conversion**: Options for quantization and other optimizations.  

## Why Use TFLite?
TensorFlow Lite is designed for on-device machine learning, offering:
- Lightweight models for resource-constrained devices.
- Faster inference with low latency.
- Compatibility with Android, iOS, and microcontrollers.

## How It Works
1. Load the TensorFlow model (e.g. `.pb` format).
2. Convert the model to TFLite format using TensorFlow Lite's `TFLiteConverter`.
3. Save the resulting `.tflite` file for deployment.

Install dependencies with:
```bash
pip install tensorflow
```
