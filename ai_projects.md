# AI and Data Science Projects

## Cell Segmentation and Mitotic Stage Classification
- **Technologies**: PyTorch, OpenCV, scikit-image, NumPy
- **Methodology**:
  1. Implemented pre-processing pipeline with adaptive contrast enhancement
  2. Applied DBSCAN clustering to identify cell nuclei regions
  3. Used watershed algorithm for precise boundary delineation
  4. Extracted 15+ morphological features per cell including texture, shape, and intensity
  5. Trained ResNet50 model to classify mitotic stages with 90% accuracy
  6. Implemented attention mechanisms to focus on morphological changes during division
- **Results**: Created end-to-end pipeline from raw microscopy images to classified cells with interactive visualization

## LLM-based Material Database Construction
- **Technologies**: Claude API, GPT-4, Python, Pandas
- **Methodology**:
  1. Developed prompt engineering techniques to extract tabular data with proper formatting
  2. Created a chain-of-thought prompting system for graph digitization
  3. Implemented LaTeX conversion for preserving numerical precision in extracted data
  4. Designed verification system comparing extracted data with original sources
- **Results**: Successfully extracted data from 200+ research papers with 92% accuracy for tables and 85% accuracy for graphs

## Laser Powder Bed Fusion Surface Analysis
- **Technologies**: OpenCV, scikit-image, NumPy, U-Net
- **Methodology**:
  1. Developed automated preprocessing workflow for video frames
  2. Implemented and compared multiple edge detection algorithms (Canny, Sobel, Farid)
  3. Applied convolutional filters for enhancing wave detection in surface images
  4. Trained U-Net model for surface feature segmentation using manually annotated frames
- **Results**: Created correlation model between processing parameters and surface waveform features
```
