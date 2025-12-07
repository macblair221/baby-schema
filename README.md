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
- ResNet18 embeddings carry baby-schema signal despite small N (Good to know!)
## Skills
- Computer Vision (PyTorch, ResNet)
- Linear Models (Ridge, cross-validation)
- Cognitive/Psychological data analysis
- Interdisciplinary research documentation
## Files Included
- Baby_Schema.ipynb (notebook)
- Baby_Schema_Presentation (A presentation I created on Baby Schema)
