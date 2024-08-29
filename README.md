# LLMs-Human-Text-Classification-using-GAN-Bert

## Project Overview

This project presents two sophisticated approaches to text classification:

* Bert-based Feature Extraction with Fully Connected Neural Network (FCNN)
Harnesses the power of BERT (Bidirectional Encoder Representations from Transformers) to adeptly extract features from textual data spanning various classes.
Implements a robust Fully Connected Neural Network (FCNN) for streamlined classification based on the meticulously extracted features.I have also integrated adapter modules into our architecture, strategically reducing the model complexity (# of parameters) . This not only streamlines the computational load but also contributes to a more seamless and rapid convergence towards precise results.

* Generative Adversarial Network (GAN)Classification
Strategically employs a cutting-edge GAN discriminator for the classification endeavor, incorporating an additional facet with a synthetic "fake" class.
Incorporates advanced semi-supervised techniques to adeptly learn the nuanced marginal distribution over not only synthetic data but also the core dataset.
Leverages the potent mechanism of adversarial learning to discerningly classify Language Model-generated texts (LLMs) and authentic human-generated texts with unparalleled precision.
This implementation is based on the techniques discussed in the following paper: [GAN-BERT: Generative Adversarial Learning for Robust Text Classification with a Bunch of Labeled Examples](https://aclanthology.org/2020.acl-main.191/).


![alt text](<Plots/model_structure.png>)


## Dataset

The dataset leveraged in this project can be accessed directly from [here](https://drive.google.com/drive/folders/11YeloR2eTXcTzdwI04Z-M2QVvIeQAU6-) on Google Drive. It is also available through Kaggle Datasets.




## Requirements

To seamlessly set up the requisite Python environment, execute the following command in your terminal:

```
pip install -r requirements.txt
```
## Result

This implementation has achieved remarkably satisfying accuracy levels for the task, showcasing its efficacy and prowess in text classification.


![alt text](<Plots/Picture3.png>)


## Discussion and Feedback

I encourage discussions and feedback on my implementation! (aaminmola@gmail.com)

Thanks.
