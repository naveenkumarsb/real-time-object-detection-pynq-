# Real-Time Object Detection Using Hardware-Accelerated CNN on PYNQ-Z2

## 📌 Overview

This project focuses on implementing a real-time object detection system using a hardware-accelerated Convolutional Neural Network (CNN) on the Xilinx PYNQ-Z2 FPGA platform.

The project combines:

- Computer Vision
- Deep Learning
- FPGA acceleration
- Embedded systems
- Hardware/Software co-design
- Edge AI

The goal is to explore how CNN-based object detection can be deployed on an FPGA-based edge computing platform.

---

## 🎯 Objectives

- Implement an object detection pipeline on PYNQ-Z2.
- Explore CNN-based object detection.
- Accelerate computationally intensive operations using FPGA hardware.
- Utilize the ARM processor and programmable logic of the Zynq-7000 SoC.
- Perform inference locally at the edge.
- Study hardware/software co-design for AI applications.

---

## 🧠 System Architecture

```text
Camera / Input
      ↓
Image Acquisition
      ↓
Pre-processing
      ↓
CNN Model
      ↓
FPGA Hardware Acceleration
      ↓
ARM Processor
      ↓
Object Detection
      ↓
Output / Visualization
