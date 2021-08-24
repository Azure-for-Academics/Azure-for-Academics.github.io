---
layout: page
title: "Azure Machine Learning: Advanced Topics"
header:
  image_fullwidth: head.jpg
---

## Course Overview 
Course Date: October 2020

**Course Instructor: <a href="/about/#shwars">Dmitry Soshnikov</a>, PhD**

In this course, we will learn different ways you can use Azure Machine Learning to perform your ML tasks in the cloud. We will see how Azure ML differs from using Data Science Virtual Machine, and how you can benefit from it, and how to effectively use Azure ML compute to perform more complex tasks, such as hyperparameter optimization. Finally, we will show to specific examples of using Azure ML: to train GAN model to generate pictures of art, and to train open domain questions answering model.  

In this course, we will cover the following topics:  

 * How does Azure ML differ from using Data Science Virtual Machine 
 * How to use Azure ML logging when performing massive experimentation to keep track of all results   
 * How to schedule experiments on the cluser, both interactively from Visual Studio Code, and through Python SDK
 * How to perform hyperparameter optimization by automatically scheduling a set of experiments through Hyperdrive 
 * How to use Azure ML to train complex Generative Adversarial Network
 * How to use DeepPavlov NLP library in Azure ML to train open domain question answering model

The following hands-on exercises are available through accompanying [GitHub Tutorial](http://github.com/CloudAdvocacy/AzureMLStarter): 
 * Train MNIST digit classification model on Azure ML through Visual Studio Code 
 * Submit training experiement through Azure ML SDK
 * Perform Hyperparameter optimization of MNIST model using Hyperdrive 
 * Train GAN on pictures of art from [Wikiart](http://wikiart.org) 

## Prerequisites  

Complete the [Introduction to Machine Learning on Azure](../ml/) course by [Francesca Lazzeri](/about/#frlazzeri). 

## Course Materials 

 * On-demand course videos
 * Have Questions? Submit your questions to [https://aka.ms/university-azure/questions](https://aka.ms/university-azure/questions) 

> To fulfil the course, you would need to [get your Azure subscription](/getting-azure/)

[Download all materials for offline use](https://aka.ms/university-azure/MachineLearning)

## Course Videos 

[**Start watching**](1)

| Video Name | Video Title | Video Description | Video Time |
|------------|-------------|-------------------|------------|
| Video 4A | [Azure Machine Learning vs. Data Science Virtual Machine](1) | Simplest deep learning setup includes using one or more data science virtual machines. We will discuss how you can benefit from using Azure ML, and how it can help solve all your problems of traditional VM-based setup.  | 8:12 | 
| Video 4B | [Using Azure ML from VS Code](2) | We will learn how to use Visual Studio Code to author training scripts, submit them to Azure ML cluster for execution, and how to track experiment results via logging.  | 12:47 | 
| Video 4C | [https://youtu.be/Aa8urDM0D3k](3) | You will learn about simplest way to use Azure ML - through Jupyter Notebooks, and how you can switch computes according to the training requirements. We will also explore hyperparameter optimization using Hyperdrive | 14:51 |
| Video 4D | [Case Study - Training Generative Adversarial Network on Azure ML](4) | We will explore how Azure ML can be used for training relatively large deep learning models, such as GAN, and how we can use image logging to keep track of the training progress. | 17:48 |
| Video 4E | [Case Study - Training Open Domain Question Answering Model on COVID Papers Dataset using Azure ML and DeepPavlov](5) | We will learn how to use external web datasets in Azure ML, how to attach and use them in Jupyter Notebooks, and how to train large NLP models | 22:49 |

## Additional Resources 

 * [Azure ML Starter Tutorial](http://github.com/CloudAdvocacy/AzureMLStarter)  
 * [Getting Started with Azure ML and VS Code](https://soshnikov.com/azure/best-way-to-start-with-azureml/)
 * [Using Azure Machine Learning for Hyperparameter Optimization](https://soshnikov.com/azure/using-azureml-for-hyperparameter-optimization/)
 * [Creating Generative Art using GANs on Azure ML](https://soshnikov.com/scienceart/creating-generative-art-using-gan-on-azureml/)
 * [DeepPavlov: "Keras" for Natural Language Processing Answers COVID Questions](https://towardsdatascience.com/deeppavlov-keras-for-natural-language-processing-answers-covid-questions-9da6199c5489)
 * [DeepPavlov Framework](http://deeppavlov.ai)
