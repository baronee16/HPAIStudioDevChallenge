# Question and Answer with BERT

 [1. Project Setup on AI Studio](#1-project-setup-on-ai-studio)

 [2. Structure of the experiment](#2-structure-of-the-experiment)

# Reference materials for Using AI Studio
[AI Studio Reference Guide](https:https://zdocs.datascience.hp.com/docs/aistudio/overview)


 ---

 ## 1. Project Setup on AI Studio
 ---
  >We recommend 16 GB of RAM and 8 GB for VRAM for training the model. For inference in GPU, 4 GB of VRAM are sufficient.


 For this experiment:
 1. You will need to create or use a preexiting project. If you are new to AI Studio, you may want to create a new dedicated project as a best practice for your learning. Using a dedicated project will help you understand the layout and use of AI Studio. 
 1. Once you have created a project or during project creation you will create a container for your work. This is called a *Workspace*. For more information, please see the AI Studio Reference Guide Link listed above.
 1. There are different options for workspaces. Each workspace has a basic set of starting libraries within it. Part of the magic of AI Studio is you can start with libraries already configured for your needs. 
 This will enable you to get right to work on your Data Science experiments. 
 1. For this demo you will want to select two options within the workspace creation screens.
 -Select ***Deep Learning GPU-based image.***
 -Add Custom Libraries 
 1. A simple way to modify the workspace image and make other libraries available for your work is use a Requirements.txt file or add custom libraries individually. Using one of these options to add libraries to your workspace will ennsure these will be included in your workspace every time it launches.  
 1. For this experiment, select the Requirements.txt file in the same directory as these instructions. You are welcome to open the requirements file to get an idea of the custom libraries that will be added to the workspace.  
 
 >Power User Tip: The Requirements.txt file is a great way to leverage library configurations between workspaces.  


 
## 2. Structure of the experiment

   ### Running inference and deploying models

   Deployment.ipynb notebook has all the necessary code to download the available model from Hugging Face and running the model for inference inside the notebook. This notebook also contains the code to log and register the model in ML Flow, for deploying the model locally. 

   The same deployment can be achieved by running the deploy.py fila

   ### Retraining the model

   For those interested in retraining the model and understand deeply how to work with deep learning, the Training.ipynb notebook provides the code for that.