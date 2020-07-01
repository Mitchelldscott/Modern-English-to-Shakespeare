# Modern-English-to-Shakespeare
This project is based out of a python3 notebook. Due to the size of the model it is best to use Google Colab to run everything.

### Supporting Files
The required files to run this project are in a folder named Data.
This folder contians and .h5 file and two text files.
The .h5 file is the saved model that can be loaded and ran.
The text files contain all of the collected text sorted by original and modern.

### Need to know
The program creates a sequence of ints based on the collected text, then passes this sequence through the predictive model.
Because the encoder only recognizes words from the three plays (Mid Summer Nights Dream, Richard iii, Romeo and Juliet) using a word not found in these plays will result in an error.
Even if you do not wish to train the model you still must load the data to initialize the encoder.

### Getting Started
The first step is to clone this repository.
There is a large green button in the header of the repo that says clone.
Once you can find the folder Modern-English-to-Shakespeare go to Google Colab (https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
In google colab you will be prompted to open a notebook, Select the notebook from the repo you just cloned. (ENGL.ipynb)
The next step is to upload the data and model.
To do this either choose the upload icon (*a rectangle with an upward arrow*) on the far left or drag and drop the files found in Data into the menu on the left. (*note you must select the FILE ICON, not the word file, before you can drag and drop*)
Now your session is all set up and ready to run!
