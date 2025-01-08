# First Part: Fourier Transform Image Mixer  

A desktop application for visualizing and mixing Fourier Transform components of images, demonstrating the importance of magnitude and phase in signal processing.  

https://github.com/user-attachments/assets/d2f7e094-f729-4fa4-904e-7ab6e8117a55

## Features  

### Image Viewing and Processing  
- **Multi-Image Support**: Load and view multiple grayscale images (auto-converts color images).  
- **Automatic Size Unification**: Images are resized to match the smallest loaded image.  
- **Real-Time Fourier Transform Visualization**: Display the following components:  
  - Magnitude spectrum  
  - Phase spectrum  
  - Real component  
  - Imaginary component  
- **Quick Image Switching**: Browse and load images effortlessly via double-click.  
- **Brightness/Contrast Adjustment**: Adjust dynamically with mouse drag gestures.  

### Fourier Transform Component Mixing  
- **Mix Components**: Combine Fourier Transform components from up to 4 images.  
- **Intuitive Sliders**: Control mixing weights with a user-friendly slider interface.  
- **Dual Output Viewports**: Compare results side-by-side.  
- **Mixing Options**: Supports magnitude/phase and real/imaginary component mixing.  

### Region-Based Frequency Selection  
- **Interactive Selection**: Draw rectangles to select frequency regions.  
- **Frequency Controls**: Toggle and refine inner (low frequency) or outer (high frequency) regions.  
- **Visual Feedback**: Highlights selected frequency regions for clarity.  
- **Consistent Region Selection**: Unified across all loaded images.  
- **Adjustable Regions**: Resize selection areas using sliders or handles.  



## Coding Practices  

This project emphasizes clean and maintainable code by adhering to the following practices:  

### Object-Oriented Programming (OOP)  
### Logging  
- **Purpose**: Logging is implemented using Python's `logging` library to track key interactions and steps in the application.  
- **Debugging Assistance**: Logs provide insight into how problems occurred and helped resolve issues during development.  
  - Example: Logged image loading errors to identify unsupported formats.  
  - Example: Tracked Fourier Transform calculation steps to debug incorrect component outputs.  
- **Usage**: Log files are stored in a `logs` file and record user interactions, system errors, and application flow for future analysis.  




## Installation  

To install and run the application, follow these steps:  

```bash  
# Clone the repository
https://github.com/MuhamedSalah10/image-mixer.git
```
## Troubleshooting:
**if you are having problems with the application, please consult the following troubleshooting tips:**

- Make sure that you have installed the required Python packages, such as NumPy, Pandas, and Qt.
- Make sure that you are using a supported signal format.
- Try restarting the application.
- If you are still having problems, please post a question on the project's GitHub page.


---

# Second Part: Beamforming Simulator

## Overview
This Beamforming Simulator is a 2D visualization tool designed to help users understand and experiment with beamforming concepts, widely used in modern technologies such as wireless communications, 5G, radar, sonar, and biomedical applications (e.g., ultrasound and tumor ablations). The core concepts implemented in this simulator are delays/phase shifts and constructive/destructive interference.



https://github.com/user-attachments/assets/bdf0630b-65b9-4e2e-9aee-8075b2a723db


## Features
- **Real-Time Beam Steering Customization:**
  - Adjust the number of transmitters/receivers.
  - Apply variable delays and phase shifts.
  - Configure multiple operating frequencies and their values.
- **Phased Array Geometry:**
  - Customize the geometry of the phased array (linear or curved with adjustable curvature parameters).
- **Visualization Tools:**
  - Display constructive/destructive interference maps.
  - Beam profile shown in synchronized viewers.
- **Multiple Phased Array Units:**
  - Add multiple phased array units.
  - Customize location and parameters for each unit.
- **Predefined Scenarios:**
  - Three parameter settings files included for direct loading, visualization, and fine-tuning.
  - Scenarios inspired by 5G, Ultrasound, and Tumor Ablation.

## Code Design Principles
### Object-Oriented Programming (OOP)
- Proper encapsulation with minimal code in the main function.
- Separate classes for:
  - **PhasedArray:** Manages array configurations and calculations.
  - **ImageVisualizer:** Handles image display and visualization.
- Avoid code repetition with reusable class structures.

### Logging
- Python's `logging` library is integrated for:
  - Tracking user interactions.
  - Logging major simulation steps.
  - Debugging issues effectively.

## Requirements
- Python 3.x
- Required libraries: `matplotlib`, `numpy`, `logging`

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/MuhamedSalah10/image-mixer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-mixer
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the simulator:
   ```bash
   python program.py
   ```

## Usage
- Customize the parameters via the GUI.
- Select predefined scenarios for visualization.
- Fine-tune settings for personalized experimentation.

## File Structure
- `BeamFormingSimulator.py`: Main simulator logic.
- `program.py`: Manages program flow.
- `visulizer.py`: Handles data visualization.
- `beamPlot.py`: Plots beamforming results.
- `scenarios.py`: Contains predefined parameter settings files.
- `task4.ui`: UI definition file.
- `logs/`: Contains log files for debugging purposes.

## Contributors        

 [Mohamed Salah](https://github.com/MuhamedSalah10),
 [Mohamed Abdelhamid](https://github.com/mohamed5841), 
 [Shaimaa Kamel](https://github.com/Shaimaakamel474),
 [Bassant Rabie](https://github.com/bassantrabie),
 [Malak Emad](https://github.com/malak-emad) 


## Acknowledgments
Inspired by Matlab's beamforming toolboxes and modern beamforming applications in communications and biomedical technologies.













