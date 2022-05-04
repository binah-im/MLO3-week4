This repo includes the files to construct and deploy a containerized, local web application capable of analyzing the sentiment of any given sentence.

* Image is created using Docker
* Local web app is written using FastApi
* Sentiment model is using HuggingFace DistilBERT fine-tuned on the Stanford Sentiment Treebank v2 (SST2) task from the GLUE Dataset


Step by Step: Container Deployment

Step 1 - Create the environment
Create a conda virtual environment using the following code 
  conda create -n aws_fastapi python=3.8 pip
 
Step 2 - Create an image of the api from main.py

Step 3 - Deploy the container

Step 4 - Testing