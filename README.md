# Fourier Transform Magnitude/Phase Mixer  

A desktop application for visualizing and mixing Fourier Transform components of images, demonstrating the importance of magnitude and phase in signal processing.  

![Application Screenshot]((https://drive.google.com/file/d/17rj3RjNTjVcck0GLYtjA9PpQPFLU_Zc-/view?usp=sharing))  

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
- **Encapsulation**:  
  - All image processing and Fourier Transform operations are encapsulated within an `Image` class.  
  - The `PhasedArray` class handles Fourier Transform component manipulation.  
  - No mathematical manipulation or direct interaction with image/phased array data occurs outside their respective classes.  
- **Minimal Main Function**:  
  - The main function is clean and acts as a controller to initialize classes and manage the application flow.  
  - Most logic and data handling occur within the encapsulated classes.  

### Logging  
- **Purpose**: Logging is implemented using Python's `logging` library to track key interactions and steps in the application.  
- **Debugging Assistance**: Logs provide insight into how problems occurred and helped resolve issues during development.  
  - Example: Logged image loading errors to identify unsupported formats.  
  - Example: Tracked Fourier Transform calculation steps to debug incorrect component outputs.  
- **Usage**: Log files are stored in a `logs` directory and record user interactions, system errors, and application flow for future analysis.  

---

## Demo  

🎥 **[Watch Demo Video Here](link_to_your_video)**  

---

## Installation  

To install and run the application, follow these steps:  

```bash  
# Clone the repository
git clone https://github.com/yourusername/ft-mixer  
cd ft-mixer  

# Additional setup steps (e.g., install dependencies)
# Example:
pip install -r requirements.txt  