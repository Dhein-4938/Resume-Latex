1. LPBF print track top-view topology analysis
	- Vertical Slice 1D signal analysis approach
		- Grouped similar local minima and maxima points to estimated valley points location, critical to scan track separations
		- Implemented the adjusted A* algorithm for the shortest path linking of valley points.
	- Flow direction algorithm approach
		- Utilized the D8 algorithm to model water flow on terrains, aiding in the identification of drainage basins and valley lines
	- Web 3D terrain display
		- Leveraged Three.js to build a web-based interface for visualizing top-view terrain, facilitating better interpretation of data
2. Material Database Building from Literature Information Extracted by LLM
    - Table Extraction:
        - Benchmarked various models (e.g., GPT-4, Claude) for tabular data extraction, enhancing accuracy in multi-column scenarios
        - Implemented LaTeX conversion for precise numerical representation
        - Annotated the passage relations of the model retrieved related papers for model evaluation
    - Graph Extraction:
        - Evaluated existing models, noting their performance issues or lack of accessibility.
        - Used Claude for zero-shot, one-shot and writing style prompting to extract axis titles and data but refined outputs via chain-of-thought mechanisms.
        - Designed a random plot generator to train a plot digitization model from scratch. (Working progress)
    - Paper Collection
        - Established a pipeline to scrape DOIs from material science databases and retrieve metadata via Crossref's API
        - Utilized Elsevier's API for obtaining XML full-text papers, streamlining data collection
3. Surface Analysis of Laser Powder Bed Fusion Bead-Up Effect
    - Data Cleaning & Preprocessing:
        - Automated file organization and processing to standardize video and measurement data.
        - Enhanced contrast and applied surface-level detection techniques for better analysis.
    - Edge Detection & Denoising:
        - Experimented with multiple edge detection algorithms (Canny, Sobel, Farid, etc.), balancing noise reduction and detail preservation.
        - Applied convolutional filters (DoG, LoG) and morphology operations for improved wave detection.
    - Feature Annotation:
        - Annotated video frames manually to train a U-net model.
        - Developed a method for correlating PV values with features like amplitude, complexity, and clarity.
