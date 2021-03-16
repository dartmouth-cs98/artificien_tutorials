# artificien_tutorials

## Code Details

This repo contains a single jupyter notebook with a simple linear regression model prewritten.     
This machine learning model represents a basic version of what an Artificien customer can create and upload. The mode will subsequently be trained on client devices using federated learning.    
The simple linear regression model developed in this turotial, defined in PyTorch syntax, predicts a single variable 'Y' using another variable 'X'.     
After training, this model is then uploaded to our 'PyGrid' node. Models sent to this PyGrid node will be downloaded by client devices (iPhones, Androids, etc.) and trained on local data.     
Each time a device or set of devices trains your model, the model stored on the PyGrid node will be updated, to reflect the newly improved model.    

As soon as you execute the tutorial in jupyterhub, it will be entered into our database and subsequently your artificien.com account's 'models' page.   
There, you'll be able to check the model progress and download the newly trained model once training is complete.    

#### PLEASE READ:

Because this is a tutorial and this model is not built to make predictions on real data, models uploaded via this tutorial will not actually be sent to client devices. You cannot save changes made to this tutorial - this file is shared by all Artificien users and cannot be altered. To create your own notebooks (which can be edited and saved), create a new notebook in your root ('/') directory, or make a copy of this notebook and place it in your root directory. To build models for deployment to actual devices running Artificien partner apps, ensure that your model can train on and make predictions using the provided sample dataset corresponding to the type of data you'd like to build on top of.

## Execution

In order to execute the model, simply run all cells in order. You will recieve a json response with a "success" message if the model has been stored properly on our node.    

## Example

Your tutorial notebook should appear as [such](tutorial_sc_example.png)

## Authors

- Matthew Kenney '21
- Jake Epstein '21

## Acknowledgements

Special thanks to Professor Tim Tregubov for his guidance during COSC 098 20F
