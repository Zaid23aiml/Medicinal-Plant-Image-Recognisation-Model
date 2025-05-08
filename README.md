Plant Image Recognition System 🌿
Welcome to the Plant Image Recognition System, a machine learning project that uses MobileNetV2 with TensorFlow and Keras to recognize plant species based on their images. This tool helps identify the plant name, scientific name, and medicinal benefits of a plant through a single uploaded image.

🔍 Introduction
This project is built to classify 150 unique plant species. Each plant in the dataset is represented by a single image, and the model predicts the plant’s identity and its medicinal uses. It serves as a valuable aid for plant enthusiasts, students, and researchers.

⚙️ Setup
Install required dependencies:

bash
Copy
Edit
pip install tensorflow opencv-python matplotlib pandas  
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Plant-Image-Recognition-System.git  
cd Plant-Image-Recognition-System  
📁 Data Structure
The system uses an Excel file (plants_data.xlsx) that contains plant names, scientific names, and benefits. Each plant image is named according to the plant name and stored in a single folder.

🧠 Model
We use MobileNetV2, a lightweight deep learning architecture ideal for image classification tasks, especially where limited data is available.

🛠️ Technologies Used
Python

TensorFlow & Keras

OpenCV

Pandas

Matplotlib

Jupyter Notebook

🏁 Inference
Run the prediction:

bash
Copy
Edit
python predict.py --image path/to/image.jpg  
The model will output the plant’s name, scientific name, and its medicinal benefits.

🔄 Future Scope
This project can be improved by adding more images per plant, text-based search, real-time camera input, and expanding the database.

📜 License
This project is open-source and available under the MIT License.
