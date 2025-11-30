🧠 **Brain Tumor Classification using Deep Learning**  
AI-powered diagnosis support for brain MRI scans — combining custom CNNs, transfer learning, and interactive deployment. 


🚀 **Project Overview** 
Brain tumor detection is a critical step in medical diagnosis. This project leverages deep learning to classify MRI images into tumor categories with high accuracy.
We explore both custom CNN architectures and transfer learning models (ResNet50, MobileNet, InceptionV3, EfficientNetB0) to identify the most reliable solution.
Finally, the best-performing model is deployed via a Streamlit web application, enabling users to upload MRI scans and receive predictions with confidence scores. 

## 🛠️ Tech Stack 

| Component          | Tools / Frameworks                                                                 |
|--------------------|------------------------------------------------------------------------------------|
| ⚙️ Data Preprocessing | TensorFlow, Keras, NumPy, Pandas                                                   |
| 📊 Visualization      | Matplotlib, Seaborn                                                               |
| 🧩 Model Architectures| Custom CNN, ResNet50, MobileNet, InceptionV3                       |
| 🛡️ Training Utilities | Callbacks (EarlyStopping, ModelCheckpoint)                                        |
| 🌐 Deployment         | Streamlit, Python                                                                 |

## 📌 Project Workflow (Timeline Style)

| Step | Description                                                                 |
|------|-----------------------------------------------------------------------------|
| 🗂️ Dataset Understanding | Review categories (tumor types), sample images, check class imbalance & resolution consistency |
| 👀 Visualization         | Explore image distributions visually for insights                                         |
| ⚙️ Preprocessing         | Normalize pixel values (0–1), resize images to 224×224 pixels                              |
| 🎨 Augmentation          | Apply rotation, flipping, zoom, brightness adjustments, and shifts to enrich training data |
| 🧩 Model Building        | Custom CNN with dropout & batch normalization; Transfer Learning (ResNet50, MobileNet, InceptionV3, EfficientNetB0) |
| 🏋️ Training              | Train models with callbacks (EarlyStopping, ModelCheckpoint), track metrics               |
| 📈 Evaluation            | Measure accuracy, precision, recall, F1-score; visualize confusion matrix & training history |
| ⚖️ Comparison            | Compare custom CNN vs pretrained models, identify best-performing model                   |
| 🌐 Deployment            | Build Streamlit app: upload MRI images, predict tumor type, show confidence scores        |


## 📊 Results & Insights 
- Transfer learning models outperform custom CNN in accuracy and generalization. 
- EfficientNetB0 strikes a balance between speed and accuracy, making it ideal for deployment. 
- Augmentation significantly reduces overfitting and improves robustness. 

## 🎯 Key Features of the Streamlit App 
- Upload MRI scans easily 
- Instant prediction of tumor type 
- Confidence scores for transparency 
- Clean, user-friendly interface 




