# Plant-Disease-Detection-Utilizing-Deep-Learning-Techniques-CNN-(Research-Paper and Webpage-Deployement)**

**Project Summary: Plant Disease Detection: Utilizing Deep Learning Techniques (CNN)**

In this project, I collaborated in a team of three members to conduct an extensive analysis of state-of-the-art Convolutional Neural Network (CNN) models and advanced optimizers for accurate identification of plant diseases. Our research aimed to develop an efficient model that could classify plant diseases across a wide range of classes.

To begin the project, we gathered a large-scale dataset consisting of 87,000 augmented images and 54,000 non-augmented images. This dataset was carefully curated to cover 38 different classes of plant diseases. We ensured a diverse representation of diseases to provide a comprehensive evaluation of the models' performance.
In our comparative analysis, we evaluated three popular CNN architectures: AlexNet, VGG-16, and ResNet-9. These architectures were chosen for their proven success in computer vision tasks. Additionally, we explored two advanced optimizers: Adam and SGD (Stochastic Gradient Descent). By systematically comparing these models and optimizers, we aimed to identify the most effective combination for plant disease detection.

After rigorous experimentation and fine-tuning, we achieved exceptional results with the ResNet-9 architecture combined with the SGD optimizer. This combination yielded an impressive accuracy of 99.69% on the augmented dataset. This high accuracy demonstrated the effectiveness of deep learning techniques in accurately identifying plant diseases.

To enhance the performance of our models, we implemented robust data preprocessing techniques. This involved applying data augmentation methods such as rotation, flipping, and scaling, which increased the diversity of the training data. Additionally, we applied normalization techniques to ensure consistent data representation and resizing methods to standardize the input dimensions across all images.

To document our methodology, findings, and valuable insights gained throughout the project, we authored a comprehensive research paper. The paper outlined the entire process, from dataset collection and preprocessing to model selection and optimization. We provided detailed descriptions of the experimental setup, including the hyperparameters and training configurations used. Furthermore, we discussed the results, highlighting the exceptional performance achieved by the ResNet-9 model with the SGD optimizer on the augmented dataset.

In addition to the research and development work, I also took the initiative to create a user-friendly web application for plant disease detection using the final model. Leveraging my web development skills, I designed and developed a webpage that allowed users to upload plant images and receive predictions on whether the plants were affected by any diseases.

To deploy the web application and make it accessible to users, I utilized Heroku, a cloud platform that supports the hosting of web applications. Heroku provided a reliable and scalable infrastructure for our application, ensuring that it could handle multiple user requests concurrently.
The webpage integrated the trained ResNet-9 model with the SGD optimizer, which had demonstrated exceptional accuracy in plant disease detection. Once a user uploaded an image, the model would process it and generate predictions on the presence of diseases. The results were then displayed on the webpage, providing the user with valuable information about the health of their plants.

By deploying the web application on Heroku, we made our plant disease detection system easily accessible to a wider audience. This enabled farmers, researchers, and plant enthusiasts to utilize the power of deep learning technology for identifying and monitoring diseases in their plants. The user-friendly interface and real-time predictions provided a convenient and efficient tool for plant disease diagnosis.

Overall, the project "Plant Disease Detection: Utilizing Deep Learning Techniques (CNN)" demonstrated the power of deep learning techniques, specifically CNN models, in accurately detecting and classifying plant diseases.By leveraging advanced optimization techniques and carefully curated datasets, we achieved remarkable accuracy, which can have significant implications for early disease detection in agricultural practices.

