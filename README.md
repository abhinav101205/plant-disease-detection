# plant-disease-detection
project folder flow:
📁 PlantDiseaseDetection
 |-     📄 abhi.h5                 → (Your pre-trained model)
 ┣ 📁 static                      → (For storing uploaded images)
 ┃    ┗ 📁 uploads                 → (Uploaded plant images)
 ┣ 📁 templates                   → (HTML templates for the GUI)
 ┃    ┣ 📄 index.html              → (Upload page)
 ┣ 📄 app.py                       → (Main Flask app to run the GUI)


About the project:
*****************Project Aim:************************
The Plant Disease Detection project leverages neural networks in deep learning to accurately identify plant diseases from images. By analyzing visual patterns, the model can classify plant diseases, enabling early intervention and prevention.
******************Model Training Process************************
#Dataset Collection:

The dataset consists of images of plants with various diseases.

Each image is labeled with its corresponding disease class.

#Model Development:

The dataset is used to train a deep learning model.

The model learns to identify disease-specific visual features, such as:

->Leaf discoloration.

->Spots or lesions.

->Irregular shapes or patterns.

The trained model (abhi.h5) can then predict the disease in new plant images by comparing them with the learned features.

*******************Practical Use of the Project*****************************
#For Farmers:

This project is designed for farmers to identify crop pathogens early.

Farmers can capture images of affected plants and use the tool to detect the specific disease.

#Early detection helps in:

Preventing the spread of the disease to other crops.

Taking timely action with appropriate treatments.

Reducing crop loss and improving overall yield quality.

#For Agricultural Research:

The project can be used by agricultural experts to study the spread of plant diseases.

It can aid in research and development of new treatments and preventive measures.

Note: The model abhi.h5 will automatically save to the folder, and the code supports both image folders and ZIP files, extracting images using the zipfile library. 













 dataset link:"https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset"
