# Part A: Fourier Transform Image Mixer  

A desktop application for visualizing and mixing Fourier Transform components of images, demonstrating the importance of magnitude and phase in signal processing.  

![Application Screenshot](https://drive.google.com/uc?export=view&id=17rj3RjNTjVcck0GLYtjA9PpQPFLU_Zc-)
  

---

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

---

## Coding Practices  

This project emphasizes clean and maintainable code by adhering to the following practices:  

### Object-Oriented Programming (OOP)  
### Logging  
- **Purpose**: Logging is implemented using Python's `logging` library to track key interactions and steps in the application.  
- **Debugging Assistance**: Logs provide insight into how problems occurred and helped resolve issues during development.  
  - Example: Logged image loading errors to identify unsupported formats.  
  - Example: Tracked Fourier Transform calculation steps to debug incorrect component outputs.  
- **Usage**: Log files are stored in a `logs` file and record user interactions, system errors, and application flow for future analysis.  

---

## Demo  

🎥 **[Watch Demo Video Here](https://drive.google.com/file/d/1HM8Ey05vmTT4qDcWbxkq-qMnfJPvujA9/view?usp=sharing)**  

---

## Installation  

To install and run the application, follow these steps:  

```bash  
# Clone the repository
git clone https://github.com/yourusername/ft-mixer  
cd ft-mixer
```
## Troubleshooting:
**if you are having problems with the application, please consult the following troubleshooting tips:**

- Make sure that you have installed the required Python packages, such as NumPy, Pandas, and Qt.
- Make sure that you are using a supported signal format.
- Try restarting the application.
- If you are still having problems, please post a question on the project's GitHub page.
