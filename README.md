# Cancer Detection with YOLOv7 on Google Colab


This repository contains the code and resources for training a cancer detection model using YOLOv7 on a custom dataset, all within the Google Colab environment. YOLOv7 is a powerful object detection algorithm known for its accuracy and real-time performance. By leveraging Google Colab, we can utilize the computational resources and convenience of cloud-based training for cancer detection.

# Dataset
To train the cancer detection model, we collected and annotated a custom dataset of medical images related to cancer. The dataset includes images of various cancer types and conditions, along with corresponding annotations indicating the presence and location of cancerous regions. The dataset was carefully curated to ensure diversity and representation of different cancer cases.

# Model Training on Google Colab
Google Colab provides a free cloud-based environment with access to powerful GPUs, making it an ideal choice for training deep learning models. Here's an overview of the training process using YOLOv7 on Google Colab:

# Data Preparation:
We organized the dataset into training and validation sets. Each image was preprocessed and resized to meet the input requirements of the YOLOv7 model.

# Setting up Google Colab: 
We created a new notebook on Google Colab and mounted the necessary Google Drive to access the dataset and store the trained models.

# Model Configuration:
YOLOv7 requires a configuration file specifying the model architecture and hyperparameters. We fine-tuned the configuration file according to our specific requirements, such as the number of classes (cancer and background) and anchor sizes.

# Training on Google Colab: 
Leveraging the GPU acceleration on Google Colab, we trained the YOLOv7 model using the prepared dataset and configuration. The training process involved optimizing the model's weights to minimize the detection loss and improve its ability to identify cancerous regions accurately.

# Model Evaluation:
After training, we evaluated the performance of the trained model on the validation set. We computed metrics such as precision, recall, and mean Average Precision (mAP) to measure the model's effectiveness in cancer detection.

# Contact
If you have any questions, suggestions, or would like to collaborate, feel free to reach out to us at kamranumer@gmail.com . We appreciate your feedback and contributions to cancer detection research!


# Full page:


![screencapture-colab-research-google-github-KamranUmer-cancer-detection-blob-main-Training-YOLOv7-on-Custom-Data-ipynb-2023-07-14-09_14_50](https://github.com/KamranUmer/cancer-detection/assets/86089489/15b1b6e5-06dd-4a7c-a45a-1a93c16b8a26)
