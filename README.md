Automatic detection of parking slot occupancy using a Bag of Visual Words and SVM classifier on the CNRPark dataset.
The project focuses on recognizing whether parking slots in an image are busy or free using classical computer vision and machine learning techniques.  
Each slot is processed through SIFT feature extraction, Bag of Visual Words encoding, and SVC classification.

- Language: Python  
- Environment: Anaconda (virtual env: `computervision`)  
- Main tools: JupyterLab, OpenCV, NumPy, SciPy, scikit-learn, Matplotlib  
- Dataset: [CNRPark-Patches-150x150](http://cnrpark.it)  
- `first_attempt.ipynb` – Initial prototype using SIFT matching  
- `FINAL_PROJECT.ipynb` – Main implementation using Bag of Visual Words + SVC  
- `proCV.ipynb` – Dynamic approach for multiple images and ground truth parsing

  More details in the report.
