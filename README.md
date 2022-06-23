# alphabet_soup
An app that analyzes startup applicants' risk profile using a neural network

## Technologies
[pathlib](https://docs.python.org/3/library/pathlib.html)
[pandas](https://pandas.pydata.org/docs/)
[sklearn](https://scikit-learn.org/stable/user_guide.html)
[tensorflow](https://www.tensorflow.org/api_docs/)
[google colab](https://colab.research.google.com/)


## Installation Guide
Upload the notebook file and "resources" folder into a google colab. Run the notebook.


## Usage
This app analyzes risk from a list of applicants using deep neural networks. It uses neural networks to analyze the likelihood that an applicant will be successful based on a number of other parameters (an accuracy score of 1 would be 100% accurate.) The model uses training and testing data found in a csv file that is fit into a pandas dataframe.

The number of input neurons and hidden nodes can be adjusted at the bottom of the notebook to test the functionality of different configurations when the model is run. The higher the accuracy score (the closest to "1"), the better the model is at analyzing risk for a given applicant.


## Contributors
Tim Tennyson


## License
Open Source
