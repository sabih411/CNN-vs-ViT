# CMPSC-448-Final-Project
Course Work of CMPSC-448 (The Pennsylvania State University)

The work presented focuses on Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs), applying them to the task of facial emotion recognition. This motivation being the distinct architectural differences between CNNs and ViTs, and our interest in evaluating their respective performances in accurately classifying facial expressions into various emotional states. The project aims to provide insights into how these two prominent deep learning architectures handle the complexities and nuances of emotion recognition from facial images.

To Properly understand the organization of code in the .ipynb notebook, see the snippet below! 
![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/aafee277-7b36-4ce4-8a5d-6dfbce22c2bc)
![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/2794b315-987e-4ba3-b173-190258024ccd)

Over all the experiments conducted we have tried our best to preverse the outputs of almost all cells that we could!!! 

**Important Notes:** 
* The data  FER2013 is publicly available and can be found at [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013). We also uploaded the Dataset on [Drive](https://drive.google.com/drive/folders/1g8oSmjRX54X3iFKYlXEljUW9N8mDMCKM?usp=drive_link) for quick access. 
* The weight hdf5 files and model (keras) files can be found in the Weights Folder ( [emotionweights](https://drive.google.com/drive/folders/1Fok5Y0aOt1ZHwKf6mRq9m_9vxMCsV-2T?usp=sharing) ) The organization of the weight folder is shown below:
    ```
    |emotionweights
      |->CNN
        |->model_weights_epoch_40.hdf5
        |->after_data_play.hdf5
        |->...other weight files
      |->train_50_val_40.keras
      |->after_data_play2.hdf5
      |-> other files (not useful)
  ```
* For inferring the the model_conv (**CNN model**) post Training Phase-I:
  
  ```Best-Checkpoint```: [./emotionweights/CNN/model_weights_epoch_40.hdf5](https://drive.google.com/file/d/1-D4KPz3ruCIUN_GwczLRRstd7cFcnPnk/view?usp=sharing)
  
  Output (expected) and shown in the .ipynb Notebook (Inference cell output)!
  ![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/5024ea35-a592-49eb-98d5-b71c5f71279d)

  
* For inferring the the model_conv(**CNN model**) post Training Phase-II:
  
  ```Best-Checkpoint```: [./emotionweights/CNN/after_data_play.hdf5](https://drive.google.com/file/d/1wyWGc39OpnHw8ZEk9nYbguqdmjOpu6m6/view?usp=sharing)
  
  Output (expected) and shown in the .ipynb Notebook (Inference cell output)!
  ![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/ac3c8f3d-458c-4cba-b109-36c7010689ed)

  
* For inferring the the model (**ViT model**) post Training Phase-I:
  
  ```Best Saved Model```: [./emotionweights/train_50_val_40.keras](https://drive.google.com/file/d/1E9yvHvaZeHjVlNgZW4WJXgBMEZv714Ll/view?usp=sharing)
  
  Output (expected) and shown in the .ipynb Notebook (Inference cell output)!
  ![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/244f43b5-467d-4b00-9633-51fafd86543c)

  
* For inferring the the model (**ViT model**) post Training Phase-II:
  
  ```Best-Checkpoint```: [./emotionweights/after_data_play2.hdf5](https://drive.google.com/file/d/1-1kwZeJs9SSCVqn3FXrsmNvEf7yJbBy9/view?usp=sharing)
  
  Output (expected) and shown in the .ipynb Notebook (Inference cell output)!
  ![image](https://github.com/sabih411/CMPSC-448-Final-Project/assets/47940851/bdc85682-8c0d-499c-8e1e-80ce21d25f85)

  
**THANK YOU!**

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
