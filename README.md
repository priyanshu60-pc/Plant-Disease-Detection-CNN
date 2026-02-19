🌿 Crop Disease Detection using Machine Learning

📌 Project Overview
This project presents an automated crop disease detection system designed for early diagnosis in Potato and Tomato plants. Developed as a 7th-semester B.Tech dissertation at Narula Institute of Technology, the system leverages deep learning to mitigate the limitations of manual inspection, which is often time-consuming and prone to human error.
+3

🦠 Targeted Diseases
Using the PlantVillage dataset, the models classify leaf images into six categories:
+1


Potato: Early Blight, Late Blight, Healthy.


Tomato: Mosaic Virus, Yellow Leaf Curl Virus, Healthy.



📂 Plant-Disease-Detection-CNN
├── 📂 datasets              # Sourced from PlantVillage (KaggleHub)
├── 📂 models                # Saved model architectures (.h5)
├── 📂 notebooks             # Final Google Colab Notebooks
│   └── Plant_Disease_Detection.ipynb
├── 📂 reports               # Project Proposal & Dissertation PDFs
├── .gitignore               # Python-specific exclusions
├── README.md                # Project documentation
└── requirements.txt         # Library dependencies


🚀 Experimental ResultsWe conducted a comparative study across three distinct architectures to determine the most effective approach for agricultural diagnosis:

+1ModelAccuracyAnalysisKNN74.01%Baseline; limited by distance measures on flattened pixels.

+2ANN84.45%Improved non-linear modeling; struggles with spatial data loss.

+1CNN98.29%Top Performer; automatically extracts complex spatial features.


Gemini said
Here is the comprehensive, professional README.md file for your repository, structured to reflect both your academic project proposal and the high-performance results achieved in your Colab notebook.

🌿 Crop Disease Detection using Machine Learning
📌 Project Overview
This project presents an automated crop disease detection system designed for early diagnosis in Potato and Tomato plants. Developed as a 7th-semester B.Tech dissertation at Narula Institute of Technology, the system leverages deep learning to mitigate the limitations of manual inspection, which is often time-consuming and prone to human error.
+3

🦠 Targeted Diseases
Using the PlantVillage dataset, the models classify leaf images into six categories:
+1


Potato: Early Blight, Late Blight, Healthy.


Tomato: Mosaic Virus, Yellow Leaf Curl Virus, Healthy.

🏗️ Project Structure
Plaintext
📂 Plant-Disease-Detection-CNN
├── 📂 datasets              # Sourced from PlantVillage (KaggleHub)
├── 📂 models                # Saved model architectures (.h5)
├── 📂 notebooks             # Final Google Colab Notebooks
│   └── Plant_Disease_Detection.ipynb
├── 📂 reports               # Project Proposal & Dissertation PDFs
├── .gitignore               # Python-specific exclusions
├── README.md                # Project documentation
└── requirements.txt         # Library dependencies
🚀 Experimental Results
We conducted a comparative study across three distinct architectures to determine the most effective approach for agricultural diagnosis:
+1

Model	Accuracy	Analysis
KNN	74.01%	
Baseline; limited by distance measures on flattened pixels.
+2

ANN	84.45%	
Improved non-linear modeling; struggles with spatial data loss.
+1

CNN	98.29%	

Top Performer; automatically extracts complex spatial features.


Key Insight: The CNN model's ability to automatically extract relevant features from raw images makes it the most effective tool for sustainable farming.
+1

🛠️ Methodology & Workflow

Data Ingestion: Images downloaded via kagglehub and standardized to 64x64 RGB pixels.
+1


Preprocessing: Normalization of pixel values (0-1 range) and an 80:20 stratified split for training and testing.
+1

Data Augmentation: Implemented ImageDataGenerator (rotation, zoom) to enhance model robustness against real-world lighting and noise.


Evaluation: Models were validated using Confusion Matrices and detailed Classification Reports (Precision, Recall, F1-score).

💻 Tech Stack

Core: Python 


Deep Learning: TensorFlow & Keras 


Image Processing: OpenCV & NumPy 


ML Tools: Scikit-learn 


Visualization: Matplotlib & Seaborn 










