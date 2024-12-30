# Frequency sweep app
Dash app to visualise oscillatory rheology data collected from Anton Paar rheometer MCR502 series. This data is obtained from a custom project on the Anton Paar rheocompass software that was developed to study the viscoelastic properties of emulsions. The rheocompass software outputs the raw data in an excel spreadsheet. The data of interest is the storage moduli $G'$, the loss moduli $G"$ and frequency $\omega$. The user can use the app to select the samples of interest and make comparisons between them. The user can also use the app to find the cross over frequency, $\omega_{G'=G''}$. 

This web app was built as part of a masters project to compare the effect of changing formulation levers on the viscoelastic profile of emulsions. Having the app made it faster to make quick comparisons between the different emulsions and output the data as scientific plots. Although the code is used to visualise the frequency sweep plots of emulsions for a specific Rheocompass software, the code can equally be used for other Rheocompass projects provided that the output from each project is an excel spreadsheet with columns selected from the Rheocompass software given in the format shown in [Usage]

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Configuration](#configuration)
5. [Contact](#contact)

## Installation
The app was made using Dash , a web based framework that provides pure Python abstraction around HTML. Before installing the app, the user needs to install the necessary libraries into your python virtual environment
```
pip install pandas 
pip install numpy 
pip install dash 
pip install scipy 
pip install matplotlib
```
After installing the necessary dependencies, the user can download a copy of the git hub repo and run the code in their python environment.
## Usage
Once the code is run in the users virtual environment, the output of the code in the jupyter notebook cell will look like below:

![alt text]([http://127.0.0.1:2235/])

The data that is outputted from the Rheocompass software is in an excel spreadsheet format and has the following column headings shown in the picture below:
![IMG_2052](https://github.com/user-attachments/assets/8b7ec19b-0168-4e34-8886-000ac1e9de61)

Alternatively, after running the code you can copy the link http://127.0.0.1:2235/ which is the local host IP address. If there is an error when running this try changing the last 4 digits of the from 2235 to any other 4 digit number. The browser should look like this:
![image](https://github.com/user-attachments/assets/1262f2fb-5259-4571-9bef-661d90bf7bc6)

 
## Features
In the app you have the option of uploading the excel file downloaded from the Rheocompass software. 
You can select multiple test samples of interest to be plotted on the app from the dropdown menu and adjust the color of each plot line.

In this text box, you can choose the marker type for the each plot line, this useful to compare b
![image](https://github.com/user-attachments/assets/9c4af953-d82a-4d57-a60b-026420f43452)



## Configuration
...

## Contact
Email: ssivakumar1@sheffield.ac.uk
