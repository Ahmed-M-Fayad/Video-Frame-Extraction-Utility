# Video Frame Extraction Utility

This repository contains two versions of a video frame extraction utility designed for different environments:

### Desktop Version
A Python notebook named `Frame Capture Program.ipynb` to process video files locally on your computer. It reads a video, extracts frames at specified intervals, saves them to your system, and optionally displays the frames.

### Google Drive Version
A link provided in `Google Drive Version.txt` for cloud-based use. This version utilizes Google Drive for file storage and is optimized for execution in Google Colab notebooks. It includes functionality to save output files directly to your Google Drive for easy access and sharing.

Both versions are linked in the repository, ensuring quick navigation to the appropriate solution based on your environment.

## Features
- **Frame Extraction:** Extract frames from a video at regular intervals or specific points.
- **Multiple Environment Support:** Works seamlessly on both local machines and cloud platforms like Google Drive and Google Colab.
- **File Linking:** Centralized links to each version for easy access.
- **User-Friendly Code:** Clear, commented, and easy-to-modify Python scripts for beginners and advanced users alike.

## Organized Directory Structure:
- `Videos/`: Directory containing the input video files.
- `Frames/`: Directory where the extracted frames are saved.

## Usage

### Desktop Version
1. Clone or download this repository.
2. Place your video files in the `Videos/` directory.
3. Open and run the `Frame Capture Program.ipynb` notebook on your local system using Python 3.x.
4. Ensure OpenCV is installed using:
   ```bash
   pip install opencv-python
