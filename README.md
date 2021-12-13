# csv-conversion

## What to Expect

The code within this project intends to normalize (or manipulate) data within a csv file using python's dataframe and Google's Colaboratory. Python 3.7.12 ia used; however, older versions may be compatible.


## About Colab

The following project is implemented using Google's Colaboratory (also know as Colab).  Colab allows you to run python code in isolation, as well as, within a web browser.  You can create new code or text blocks by hovering over a pre-existing code or text block and hitting the + sign.  

![Adding New Code or Text](addCodeOrText.png).  


Colab files can be downloaded as a 'ipynb' or 'py'.  In this project, a 'ipynb' file was created.  Additional information regarding Colab can be found here: https://colab.research.google.com/?utm_source=scs-index.


## How to Run
Install jupyter:
`pip install jupyter` or `sudo -H pip install jupyter`

If you would like to run the web-based version of Jupyter, you can run:
`python -m notebook` or `jupyter notebook`

If you would like to run Jupyter from the command line, you can run:
`jupyter nbconvert --execute csv_conversion.ipynb > sampe.csv`
 