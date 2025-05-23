# Hair Disease Detection using CNN

This project presents a deep learning–based solution for detecting hair and scalp diseases using image classification. The model is trained using a Convolutional Neural Network (CNN) to recognize and classify dermatoscopic images into one of ten common hair disease categories. To enhance usability, a user-friendly interface is developed using Streamlit, allowing anyone to upload a scalp image and receive an instant diagnostic prediction.

Hair and scalp conditions such as Alopecia, Dandruff, Psoriasis, and others often go undiagnosed or misdiagnosed due to a lack of accessible dermatological care. This project aims to bridge that gap by leveraging artificial intelligence to assist in early detection and promote timely treatment. By automating the classification process, this system offers a potential tool for both clinical support and personal health monitoring.

The project is built on a dataset structured into training, validation, and test sets. Each subset contains folders named after the disease class, with relevant image samples inside. Images are resized to 224x224 pixels and undergo preprocessing and augmentation during training to improve model generalization.

The CNN architecture consists of multiple convolutional and pooling layers, followed by a fully connected layer and a softmax output layer corresponding to the ten disease classes. The model is compiled using the Adam optimizer and categorical cross-entropy loss function and trained over several epochs. Once trained, the model achieves high accuracy on both validation and test sets, proving its effectiveness in real-world conditions.

Looking ahead, the system could be enhanced by expanding the dataset, integrating explainable AI techniques like Grad-CAM for model transparency, and developing a mobile version for broader accessibility. Incorporating additional patient metadata such as age, symptoms, and history would also enable more personalized and holistic diagnostic outcomes.

This project was developed by Ayesha Siddiqua (Team Lead), Sufiya Nazneen Khan, and Seema Afreen, students from the Department of Computer Science & Engineering – Data Science at Nawab Shah Alam Khan College of Engineering and Technology. The work was completed under the mentorship of Mr. Mainak Dev. This repository serves as both a proof of concept and a foundation for future research and development in AI-assisted dermatological care.

