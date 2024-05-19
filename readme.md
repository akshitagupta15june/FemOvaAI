## Inspiration 💡

**Polycystic Ovarian Syndrome (PCOS)** is a common endocrine disorder affecting women of reproductive age, often leading to complications such as infertility, metabolic issues, and psychological challenges. Early and accurate detection is crucial for effective management and treatment. Inspired by the potential of artificial intelligence in medical diagnostics, we embarked on creating **FemOvaAI**, a project aimed at leveraging state-of-the-art deep learning techniques to aid in the detection of PCOS. By providing a reliable and efficient tool for early diagnosis, we hope to make a significant impact on women's health globally.

## What it does 💘

**FemOvaAI** is an advanced AI-driven system designed to detect Polycystic Ovarian Syndrome (PCOS) from ultrasound images. Utilizing the power of YOLOv8, a cutting-edge object detection model, our system analyzes images to classify them into two categories: **"PCOS"** and **"No PCOS."** This enables healthcare professionals to make informed decisions quickly, enhancing the diagnostic process and potentially improving patient outcomes.

## How we built it ⚙️

We built **FemOvaAI** using the following steps:

**Public Dataset** Used👉🏻 :

▶️ [Kaggle PCOS Public Dataset](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos)

▶️[Roboflow PCOS Public Dataset](https://universe.roboflow.com/vanessas/pcos2)

**Data Collection and Preparation**: We used a publicly available dataset mentioned above containing 234 ultrasound images with 1363 labels, images are labeled into two classes: "PCOS" and "No PCOS." The dataset was split into training and testing sets to ensure robust model evaluation.

**Model Selection**: We chose **YOLOv8** for its superior performance in object detection tasks. YOLOv8x architecture allows for real-time detection and classification, making it ideal for medical image analysis.

**Training the Model**: The training process involved feeding the labeled ultrasound images into the YOLOv8 model. We applied various data augmentation techniques to enhance the model's generalization capabilities and prevent overfitting.

To checkout Kaggle👉🏻 [code](https://www.kaggle.com/code/akshitagupta1506/pcos-detection)

**Evaluation and Testing**: After training, the model was evaluated on the test set to assess its accuracy, precision, recall, and overall performance. Fine-tuning was performed to optimize the model further. **Achieved a test accuracy of 92.9%**.

**Deployment**: The trained model was then integrated into a user-friendly application, allowing healthcare professionals to upload ultrasound images and receive instant diagnostic results.

To view the code file in👉🏻 [GitHub](https://akshitagupta15june.github.io/FemOvaAI/)

## Challenges we ran into 🙁

Building FemOvaAI came with several challenges:

Data Scarcity: The limited number of images (234) made it challenging to train a highly accurate model. We had to employ sophisticated data augmentation techniques to mitigate this issue.

Model Complexity: Training a deep learning model like YOLOv8 required substantial computational resources and fine-tuning to achieve optimal performance.

Class Imbalance: Ensuring the model did not become biased towards one class due to an imbalance in the dataset was crucial. We had to implement strategies to handle this effectively.

Validation and Testing: Ensuring that the model's predictions were reliable and clinically valid required rigorous testing and validation.

## Accomplishments that we're proud of 🚀

We are proud of several key accomplishments in the FemOvaAI project:

**Successful Implementation**: We successfully implemented an AI-driven diagnostic tool using YOLOv8, achieving high accuracy in detecting PCOS from ultrasound images.

**Innovation in Healthcare**: Our project demonstrates the potential of AI in improving healthcare diagnostics, offering a novel solution for PCOS detection.

**Overcoming Data Limitations**: Despite the limited dataset, we achieved robust performance through innovative data augmentation and model training techniques.

## What we learned 🚀

Throughout the development of FemOvaAI, we gained valuable insights:

Importance of Data Quality: High-quality and diverse datasets are crucial for training effective AI models, especially in medical diagnostics.

Model Optimization: Fine-tuning deep learning models requires a balance between computational resources and model performance, highlighting the importance of efficient model training strategies.

Impact of AI in Healthcare: AI has the potential to revolutionize healthcare by providing rapid, accurate diagnostic tools, underscoring the need for continued research and development in this field.

## What's next for FemOvaAI 📟

Moving forward, we have several plans for FemOvaAI:

Dataset Expansion: We aim to collaborate with medical institutions to gather a larger, more diverse dataset, enhancing the model's accuracy and reliability.

Model Enhancement: Continuous improvement of the YOLOv8 model and exploring other advanced architectures to further boost performance.

Clinical Trials: Conducting clinical trials to validate the model's effectiveness in real-world settings and obtaining regulatory approvals.

User Interface Improvement: Developing a more intuitive and user-friendly interface to facilitate easy adoption by healthcare professionals.

Integration with Medical Systems: Integrating FemOvaAI with existing healthcare systems to streamline the diagnostic process and ensure seamless workflow integration.

By advancing FemOvaAI, we hope to make a lasting impact on women's health, providing a powerful tool for early detection and management of PCOS.

