# Projects

## Materials Journal Information Extraction and Database Construction
- **Time**: Oct 2024 – Present
- **Technologies**: APIs: \[Claude, GPT-4, CrossRef, Elsevier, Springer, Wiley\], Pandas, Requests
- **Methodology**:
  1. Designed a benchmark database builder using API calls from journal publishers with a list of DOIs and API keys user provided to download the full text in PDF and XML format
  2. Collected metadata for each journal entry and applied data cleaning techniques as handling missing data 
  3. Engineered chain-of-thought prompt design for different visual and textual models to extract material information from journals, including full text, table and captions.
  4. Evaluating model performance across GPT-4, Claude 3.7, Llama 3.2 using a variation of prompts

## Scanning Track Topology Analysis of Laser Power Bed Fusion
- **Time**: Jan 2025 – Present
- **Technologies**: NumPy, scikit-image, Three.js, HTML, CSS, matplotlib
- **Methodology**:
	- Vertical Slice 1D signal analysis approach
		- Grouped similar local minima and maxima points to estimated valley points location, critical to scan track separations
		- Implemented the adjusted A* algorithm for the shortest path linking of valley points.
	- Flow direction algorithm approach
		- Utilized the D8 algorithm to model water flow on terrains, aiding in the identification of drainage basins and valley lines
	- 3D interaction display
		- Leveraged Three.js to build a web-based interface for visualizing top-view terrain, facilitating better interpretation of data
    - Built a interactive annotation tool using matplotlib including chunk selection and shortest path connection between user selected points
- **Results**:

## Video Surface Analysis of Laser Powder Bed Fusion Bead-Up Effect
- **Time**: Aug 2023 – Dec 2024
- **Technologies**: NumPy, scikit-image, Three.js, HTML, CSS, matplotlib
- **Methodology**:
  - Automated file I/O and preprocessing workflow (contrast enhancement, surface-area cropping) for high-speed video frames 
  - Evaluate effectiveness of capturing surface boundary while balancing noise reduction and detail preservation using various edge detection algorithms (Canny, Sobel, Farid) and convolutional filters (DoG, LoG)
  - Trained U-Net model for surface feature segmentation using manually annotated frames
- **Results**: Created correlation model between processing parameters and surface waveform features

## Cell Segmentation and Mitotic Stage Classification
- **Time**: Fall 2024
- **Technologies**: PyTorch, OpenCV, scikit-image, NumPy
- **Methodology**:
  1. Implemented pre-processing pipeline with data normalization and adaptive contrast enhancement
  2. Applied DBSCAN clustering to identify cell nuclei regions
  3. Used watershed algorithm for precise boundary delineation as cell segmentatioin
  4. Extracted over 15 morphological features per cell including texture, shape, and intensity
  5. Trained ResNet50 model to classify mitotic stages reaching 91.3% accuracy
- **Results**: Created end-to-end pipeline from raw microscopy images to classified cells with visualization

## FIFA Player Statistic Analyzation and Prediction
- **Time**: Fall 2023
- **Technologies**: Spark, PostgreSQL, GCP, AWS, PyTorch, matplotlib
- **Methodology**:
  - Facilitated Spark-based analytics with PostgreSQL integration
  - Constructed Spark and PyTorch ML models predicting player value, achieving an R2 value of over 92%
  - Deployed the data engineering and training pipeline on Google Cloud Platform

## VAMPIRE Software Simulations for Magnetic Memory Device Dynamics
- **Time**: September 2019 – July 2022
- **Technologies**: C++, Linux, MPI and Parallelism
- **Methodology**:
  - Computed the energy barrier of the minimum path for changing the state of magnetic memory devices
  - Performed simulations of domain wall movement under temperature variance and shape constraints
  - Analyzed the atomistic dynamic spin flipping at interfaces under changes in electric and magnetic fields
