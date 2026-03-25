这是一份为您精心翻译的英文版软件说明，采用了国际通用的软件文档规范（Technical Documentation Standard），术语与您的代码（如 PlantAnalyzer.cpp 中的类名和功能）保持了高度一致。

PhenoV Pro v1.0
Welcome to PhenoV Pro! Developed based on Qt and OpenCV, PhenoV Pro is a lightweight plant image analysis tool designed to provide cutting-edge image processing solutions and analytical support for plant phenotyping researchers and enthusiasts.

⚠️ Important Notes (Read Before Running)
To ensure the software can correctly read images and execute algorithms, please strictly adhere to the following rules:

1. English Path Requirements
   Installation Path: Ensure the software is installed in a directory with an all-English path (e.g., D:\Software\PhenoV Pro). Avoid folder names containing Chinese characters, spaces, or special symbols.

Image Path: The target image files and their parent folders must also be named in pure English. If the path contains non-ASCII characters, the OpenCV library may fail to load the image, leading to analysis errors.

2. System Requirements
   Architecture: Windows 64-bit version.

Operating System: Windows 10 / Windows 11.

3. Dependencies
   The installation package includes necessary Qt and OpenCV Dynamic Link Libraries (DLLs). Do not delete any .dll files in the installation directory, or the program will fail to launch.

🌟 Key Features
Seed Count: Automated counting and morphological analysis of seeds in images.

Grow Area: Measurement and analysis of plant growth regions.

Leaf Lesion Count: Automated detection and counting of necrotic spots/lesions on leaves.

Leaf Area Computing: Automatic leaf contour recognition and total area calculation, supporting precise lesion capture via threshold adjustment.

Root Length: Measurement and distribution analysis of root system length.

Image Processing Tools: Built-in features for Binarization, Brightness/Contrast adjustment, and Background Removal.

🚀 Quick Start
Launch: Download the package, double-click the installer, and follow the prompts.

Import: Click the "Open Image" button and select a clear leaf photo with a simple background (Recommended path: D:\TestImages\leaf01.jpg).

Analyze: Click "Start Analysis" and observe the results in the right-hand panel.

Adjust: If recognition is inaccurate, try adjusting the threshold or increasing the image brightness/contrast.

🛠 Troubleshooting
Program fails to start: Please check if the VC++ Redistributable runtime is missing.

Image fails to load: Verify if the image path contains Chinese characters or if the format is a standard .jpg, .png, or .bmp.

Results are all black/white: Try resetting the function and ensure the original image has uniform lighting.

📅 Version Information
Version: v1.0.0

Environment: Qt 5.12.10 (MSVC 2017 64-bit) / OpenCV 3.4.1

Updated: February 2026
