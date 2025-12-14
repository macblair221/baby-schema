## Baby Cuteness Prediction - A ML and Cognitive Science Project
 This project explores whether infant cuteness ratings can be predicted from image features. Building on research on baby schema—a set of infantile facial characteristics that elicit positive emotional and caregiving responses—I applied a computer vision pipeline to model human judgments.
 ## Methods
- Used 55 standardized infant images from the Japanese Cute Infant Face Dataset
- Extracted 512-dimensional embeddings using pretrained ResNet18
- Trained Ridge regression with multiple regularization strengths
- Evaluated performance using 5 fold cross-validation
## Results
- Baseline MAE: 0.3416
- Best model MAE: 0.2805 (α = 100)
- Indicates that ResNet18 features encode baby-schema cues in a predictable way
- ResNet18 embeddings carry baby-schema signal despite lack of large data set
## Skills
- Computer Vision (PyTorch, ResNet)
- Linear Models (Ridge, cross-validation)
- Cognitive/Psychological data analysis
- Interdisciplinary research documentation
## Files Included
- Baby_Schema.ipynb (notebook)
- Baby_Schema_Presentation (A presentation I created on Baby Schema)

---

My “Baby Schema” project is based on Konrad Lorenz’s proposed Baby Schema and aims to identify levels of reported cuteness ratings in human infant faces. I used ResNet18, an image classification model from PyTorch. ResNet is a family of convolutional neural network (CNN) architectures designed for image classification. CNNs are deep learning models that are effective at recognizing edges and textures, which works well for detecting subtle differences in infants’ facial features.
I aim to extend my research and development by accumulating a larger dataset of human infant faces. Additionally, I would like to eventually introduce other animal species so the model can learn the differences between juvenile and adult animal features.
My goal is to create a model that becomes highly accurate at detecting physical features in human infants and adults in order to better understand how the human mind responds to these features. My current dataset consists only of Japanese children, so gathering images of infants from other cultures would be useful for diversification.
Despite the small size of the dataset, the ResNet18 model performed surprisingly well, achieving a low mean absolute error, which quantifies the average absolute difference between the model’s predictions and the actual data points.

###  Citations
--
Nittono Hiroshi, Ohashi Akane, Komori Masashi. Creation and Validation of the Japanese Cute Infant Face (JCIF) Dataset, Frontiers in Psychology. Volume 13 - 2022, 2022
https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2022.819428. 10.3389/fpsyg.2022.819428. 1664-1078

