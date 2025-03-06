# Description

In this folder, we move forward with valuable examples of Deep Learning applications on AI Studio. We focus mainly in Computer Vision with Convolutional Neural Networks and Natural Language with Transformers. There are three examples as outlined below. 

## Resources
For these experiments:

 1. You will need to create or use a preexiting project. If you are new to AI Studio, you may want to create a new dedicated project as a best practice for your learning. Using a dedicated project will help you understand the layout and use of AI Studio. 
 1. There are different options for workspaces. Each workspace has a basic set of starting libraries within it. Part of the magic of AI Studio is you can start with libraries already configured for your needs. 
 This will enable you to get right to work on your Data Science experiments. The notebooks in this folder require a Deep Learning workspace. 

## 1. Bert QA
This experiment shows a simple BertQA experiment, providing code to train a model, and other to load a trained model from Hugging Face, deploying a service in MLFlow to perform the inference

## 2. Text Generation
This experiment shows how to create a simple text generation, one character at a time. This example uses a dataset of Shakespeare's texts.

## 3. Super Resolution
This is a Computer Vision experiment that uses convolutional neural networks (CNN) for image transformation. More specifically, this experiment shows how to improve the resolution of an image using the CNN structure and configuration. This experiment requires the DIV2K dataset to run. You can downloaded this dataset from s3://dsp-demo-bucket/div2k-data into an assset called DIV2K.