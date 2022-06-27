# Interactive Scene Classifier using Google Earth Engine
This project includes a jupyter notebook that allows the user to import, view, and classify images from the Sentinel-2 Surface Reflectance image collection. The user defines a site and study period, then supervises the classification of an original image there. The trained classifier can then be reused to classify additional images.

The project could be improved by adding a procedure to validate the classifier.

## Usage
You can clone this repo in a terminal by typing (change user name and file path to your local destination)

        C:\Users\<USERNAME>\<FILEPATH>>git clone https://github.com/nshobert/GEE-Interactive-Classifier.git

Change into the new directory 

        C:\Users\<USERNAME>\<FILEPATH>> cd GEE-Python-Interactive-Classifier     

and start a virtual environment from the command line 

        C:\Users\<USERNAME>\<FILEPATH>GEE-Python-Interactive-Classifier> pipenv shell 

The first time you use the code in this repo you need to install the dependencies of the virtual environment

        (GEE-Python-Interactive-Classifier-YYYYY) C:\Users\USERNAME\<FILEPATH>GEE-Python-Interactive-Classifier> pipenv install

Then you can run the notebook on a browser using the following command

        (GEE-Python-Interactive-Classifier-YYYYY) C:\Users\USERNAME\<FILEPATH>GEE-Python-Interactive-Classifier> jupyter-lab

## Dependencies
To run the code in this repo you need to have installed 
- pyenv
- pipenv

## Tips and other notes
See the other GEE Repos to get started with Google Earth Engine!

The code in this repo has been succsessfully ran on: 
- cmd Windows 10
