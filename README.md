# A Deep Learning Approach to Classifying MonkeyPox from Lesion Images

### Link to Paper - [Download PDF](docs/paper.pdf)

<ul>
Following the outbreak of the COVID-19 virus, the Monkeypox virus poses a new threat of a potential global
pandemic. Although the severity of the Monkeypox virus is not yet at the level of COVID-19, important
measures are needed to prevent another major outbreak. Deep learning methods have proven efficient at
classifying monkeypox lesions, which can help with preventing the spread of the virus as it can be a substitute
for in-person testing. Our research implements the “Monkeypox Skin Lesion Dataset”, a collection of
monkeypox, measles, and chickenpox images collected from websites, news portals, and publicly accessible
case reports. The original images were augmented to increase the dataset size. Our deep learning approaches
include training fine-tuned convolutional neural networks as well as a deep hybrid learning approach in which
we extract features using a convolutional neural network. We then proceed by passing the features into a variety
of machine learning classifiers including XGBoost, K-Nearest Neighbors, and Logistic Regression, yielding
respective accuracies of 95.81%, 97.07%, and 97.28%.
</ul>


## Data Augmentation Example
![](images/before.png)

<ul>
image before augmentation
</ul>


![](images/after.png)

<ul>
image after augmentation
</ul>

## Model Workflow

![](images/workflow.png)
<ul>
proposed dhl approach workflow
</ul>

### Contributors

- [@AyuCode](https://github.com/AyuCode)



