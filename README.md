<h1>PLANT DISEASE PREDICTION</h1>
This project aims to predict plant diseases using deep learning techniques. The model is built using Tensorflow and keras, and the application is deployed using streamlit.

<h2>Table of Contents</h2>
<h4>1. Introduction</h4>
<h4>2. Features</h4>
<h4>3. Dataset</h4>
<h4>4. Usage</h4>
<h4>5. Model Training</h4>
<h4>6. Deployment</h4>
<h4>7. Results</h4>


<h2>Introduction</h2>
Plant diseases are a major threat to food security, affecting crop yield and quality. Early and accurate detection of diseases can help in taking preventive measures. This project leverages convolutional neural networks (CNNs) to classify images of plant leaves into healthy or diseased categories.
<h2>Features</h2>
<h4>Image classification using a trained deep learning model.</h4>
<h4>User-friendly web interface for disease prediction.</h4>
<h4>Real-time image upload and prediction.</h4>
<h4>Detailed prediction results including confidence scores</h4>

<h2>Dataset</h2>
The dataset used for this project consists of images of plant leaves. Each image is labeled with the type of disease or as healthy. The dataset can be obtained from New Plant Diseases Dataset.
<h3>About Dataset</h3>
This dataset is recreated using offline augmentation from the original dataset. The original dataset can be found on this github repo. This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.

<h2>Usage</h2>
Run the Streamlit app: This command starts the Streamlit server and runs the application.
<h4>streamlit run app.py</h4>
Open your browser: After running the above command, you need to open your web browser and navigate to the local URL where Streamlit is running. By default, Streamlit runs on port 8501.
<h4>http://localhost:8501</h4>
Once you've followed these steps, you should be able to interact with the plant disease prediction application through your web browser. You can upload images of plant leaves and the application will use the trained model to predict whether the plant is healthy or diseased.

<h2>Model Training</h2>
Prepare the dataset and place it in the directory.
Run the training script
<h4>python train.py</h4>
The trained model will be saved in the models directory.

<h2>Deployment</h2>
The application is deployed using Streamlit. For local deployment, follow the usage instructions. To deploy the app on a cloud platform, refer to the Streamlit deployment documentation.

<h2>Results</h2>
The trained model achieves an accuracy of 94% on the test set









