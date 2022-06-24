# Interactive Scene Classifier using Google Earth Engine
This project includes a jupyter notebook that allows the user to import, view, and classify images from the Sentinel-2 Surface Reflectance collection. The user supervises the classification of an original image. Then, the trained classifier can be reused to classify additional images. The project would be improved by adding a procedure to validate the classifier.

## Usage
You can clone this repo in a terminal by typing

        C:\Users\<USERNAME>\Documents\code\>git clone XXXXX

Change into the new directory 

        C:\Users\<USERNAME>\Documents\code\> cd XXXXX     

and start a virtual environment from the command line 

        C:\Users\<USERNAME>\Documents\code\XXXXXX> pipenv shell 
        Launching subshell in virtual environment...
        Microsoft Windows [Version 10.0.19043.1526]
        (c) Microsoft Corporation. All rights reserved.

The first time you use the code in this repo you need to install the dependencies of the virtual environment

        (XXXX-YYYYY) C:\Users\USERNAME\Documents\code\XXXXX> pipenv install
Then you can run the notebook on a browser using the following command
(XXXX-YYYYY) C:\Users\USERNAME\Documents\code\XXXXX> jupyter-lab

## Dependencies
To run the code in this repo you need to have installed 
- pyenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/KXWBnnQrSS_Uu4)
- pipenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/tO10k0gX_U-6Ve)

## Tips and other notes
See the other GEE Repos on the NGI Natural Hazards DevOps page to get started with Google Earth Engine!

The code in this repo has been succsessfully ran on: 
- cmd Windows 10