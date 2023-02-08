# Name-Entity-Recognition-Using-BERT
## Table of Contents.
  * [Demo](#demo)
  * [Problem Statement](#problem-statement)
  * [Description Overview](#description-overview)
  * [Workflow Diagram](#workflow-diagram)
  * [Installation](#installation)
  * [Run](#run)
  * [Comparision](#comparision)
## Demo
### Deplyment Link: http://3.233.173.97:5001/ (Deployment is on Amazon Web Services)
<img width="960" alt="ner" src="https://user-images.githubusercontent.com/62692329/217649657-7960e411-668c-4839-9b49-21b50b670fec.png">

## PROBLEM STATEMENT
``` In this project we will be prforming one of the most famous task in the field of nautal language processing i,e Name Entity Recognition. ```
## DESCRIPTION OVERVIEW
- Named EntitiesRecognition (NER) is a basic task of Natural Language Processing (NLP). The purpose is to identify named entities such as person names, place names, and organization names in the corpus. Due to the increasing number of these named entities, it is usually impossible to exhaustively list them in the dictionary, and their constituent methods have some regularities. Therefore, the recognition of these words is usually included in the task of morphological processing (such as Chinese segmentation). Independent processing, called named entity recognition. 

- Named entity recognition technology is an indispensable part of many natural language processing technologies such as information extraction, information retrieval, machine translation, and question answering systems.

- Named entities are the research subjects for named entity recognition. Generally, named entities include 3 categories (entity, time, and number) and 7 categories (person, place, institution, time, date, currency, and percentage). Judging whether a named entity is correctly identified includes two aspects: whether the boundary of the entity is correct; and whether the type of the entity is correctly labeled.

## WORKFLOW DIAGRAM
![image](https://user-images.githubusercontent.com/62692329/217648006-d38a83a7-7144-48c8-907a-d470e76930e4.png)
## Technical Aspect
This project is divided into two part:
1. Training a deep learning and machine learning model using Keras.
2. Building deployed, and hosting a Flask web app on Amazon Web Services(AWS)( http://3.233.173.97:5001/ ).

## Installation
The Code is written in Python 3.6.9. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [downloading it](https://github.com/IamVicky90/Name-Entity-Recognition-Using-BERT/archive/main.zip):
```bash
pip install -r requirements.txt
```
## Run
To run the app in a local machine, shoot this command in the project directory:
__Run the follwing command after installing requirements.txt__
```bash
python app.py
```
## COMPARISION
``` More data or better larger dataset can be used to build a better model. We can also try out better pre trained model with fine tuning to increase the performance. ```
