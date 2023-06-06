# <h1 align="justify">Transfer Learning in Deep Multi-Layer Perceptrons: An Appraisal for Predictive Quality Assessment in Roll-Forming Processes 🏭🎯</h1>
<div id="badge" align="center">
  
  [![Python](https://img.shields.io/badge/Python-FFD43B?style=plastic&logo=python&logoColor=blue)](https://www.python.org/)
  [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=pytorch&logoColor=white)](https://pytorch.org/)
  [![NVIDIA](https://img.shields.io/badge/NVIDIA-GeForce_MX230-76B900?style=plastic&logo=nvidia&logoColor=white)](https://www.nvidia.com/en-us/geforce/gaming-laptops/geforce-mx230/specifications/)
   
 </div>
<p align="justify">
The adoption of machine learning (ML) and deep learning (DL) models for discrete production processes has garnered much success, especially for predictive quality assessment based on machine parameter settings. However, on account of the dynamic nature of the production process and inherent product variability, there is limited time and monetary feasibility in the traditional data generation and acquisition approaches through experimentation or unrepresentative simulations. Furthermore, the ML and DL models would have to be trained tabula rasa for new product profiles which would require time and resource complexity. Considering these challenges, this thesis introduces transfer learning (TL) as a potential solution. TL leverages the existing related pre-trained model source domain knowledge when training on a sparse target domain, thereby enhancing model performance, convergence, and generalizability while exhibiting reduced target domain data
dependency.<br><br>
This thesis investigated the viability of TL in refining deep multi-layer perceptron (MLP) models commonly used for predictive quality assessment of the sheet metal roll-forming process. This investigation incorporated a comparative appraisal between a control model trained on the target domain and four parameter-based TL models, developed on the principles of freezing and fine-tuning source domain pre-trained model parameter layer connections, with the target task of predicting the regression outcome of the outgoing thickness of the roll-formed product. The relative performances of these models were assessed through benchmarking experiments on the number of training epochs and variations in the data proportions. The results indicated that TL models improved performance and generalization when fine-tuned to the target domain. Additionally, the fine-tuned TL models exhibited reduced dependence on data proportions indicating their potential to learn from smaller target domain datasets, as compared to the control model. Even with certain limitations in the assumptions used to build the source and target domains, the lack of hyperparameter optimization and the absence of a cross-validated evaluation, these findings were correlated with previous theoretical and empirical deep TL studies. Furthermore, this thesis also provided foundational insights into the effectiveness of parameter-based TL for MLP models and set the stage for future research directions.
</p>




