# PhenoV Pro v1.0

Welcome to PhenoV Pro! Developed based on Qt and OpenCV, PhenoV Pro is a lightweight plant image analysis tool designed to provide cutting-edge image processing solutions and analytical support for plant phenotyping researchers and enthusiasts.

## Project Structure

> 📁 **Key files and folders in this repository:**

- **RawData** — All the raw images used in this study.
- **SampleImages** — Example result images for each analysis function (seed counting, lesion counting, lesion area measurement, leaf growth estimation, root analysis, etc.), providing a quick preview of the software's capabilities.
- **User Guide** — [`PhenoV Pro v1-user guide.pdf`](file:///d:/exp/phenoVpro/PhenoV%20Pro%20v1-user%20guide.pdf): Detailed user manual covering installation, operation, and troubleshooting.
- **Installation File** — [`PhenoV_Pro_Setup_v1.0_x64.exe`](file:///d:/exp/phenoVpro/PhenoV_Pro_Setup_v1.0_x64.exe): The Windows 64-bit installer for PhenoV Pro v1.0.

## Table of Contents

- [Project Structure](#project-structure)
- [Important Notes](#important-notes)
- [System Requirements](#system-requirements)
- [Dependencies](#dependencies)
- [Key Features](#key-features)
- [Quick Start](#quick-start)
- [Troubleshooting](#troubleshooting)
- [Version Information](#version-information)

## Important Notes

> ⚠️ **Read Before Running**
> To ensure the software can correctly read images and execute algorithms, please strictly adhere to the following rules:

### 1. English Path Requirements

- **Installation Path**: Ensure the software is installed in a directory with an all-English path (e.g., `D:\Software\PhenoV Pro`). Avoid folder names containing Chinese characters, spaces, or special symbols.
- **Image Path**: The target image files and their parent folders must also be named in pure English. If the path contains non‑ASCII characters, the OpenCV library may fail to load the image, leading to analysis errors.

### 2. System Requirements

| Requirement      | Specification           |
| ---------------- | ----------------------- |
| Architecture     | Windows 64‑bit          |
| Operating System | Windows 10 / Windows 11 |

### 3. Dependencies

The installation package includes necessary Qt and OpenCV Dynamic Link Libraries (DLLs). Do not delete any `.dll` files in the installation directory, or the program will fail to launch.

## Key Features

- **Seed Counting**: Automated counting and morphological analysis of seeds in images.
- **Lesion Counting**: Automated detection and counting of necrotic spots/lesions on leaves.
- **Lesion Area Measurement**: Automatic leaf contour recognition and total area calculation, supporting precise lesion capture via threshold adjustment.
- **Leaf Growth Estimation**: Measurement and analysis of plant growth regions.
- **Root Analysis**: Measurement and distribution analysis of root system length.
- **Image Processing Tools**: Built‑in features for:
  - Binarization
  - Brightness
  - Contrast
  - Target Isolation

## Quick Start

1. **Launch**: Download the package, double‑click the installer, and follow the prompts.
2. **Import**: Click the **Open Image** button and select a clear leaf photo with a simple background (Recommended path: `D:\TestImages\leaf01.jpg`).
3. **Analyze**: Click **Start Analysis** and observe the results in the right‑hand panel.
4. **Adjust**: If recognition is inaccurate, try adjusting the threshold or increasing the image brightness/contrast.

## Troubleshooting

- **Program fails to start**: Please check if the VC++ Redistributable runtime is missing.
- **Image fails to load**: Verify if the image path contains Chinese characters or if the format is a standard `.jpg`, `.png`, or `.bmp`.
- **Results are all black/white**: Try resetting the function and ensure the original image has uniform lighting.

## Version Information

- **Version**: v1.0.0
- **Environment**: Qt 5.12.10 (MSVC 2017 64‑bit) / OpenCV 3.4.1
- **Updated**: February 2026

---

_Return to [top](#phenov-pro-v10)_
