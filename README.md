# MDS & ISOMAP
This project includes implementations of the MDS and ISOMAP algorithms using Python and various libraries such as NumPy, Matplotlib, Scikit-learn, and NetworkX. 

## Requirements

To run this project, you will need to have the following software installed on your machine:

- Python 3.6 or higher
- NumPy
- Matplotlib
- Scikit-learn
- NetworkX
- Pandas

## Usage

To use this project, simply run the Jupyter notebook `MDS&ISOMAP.ipynb` provided in the root directory. The notebook includes code examples and explanations for each step of the process, making it easy to follow along and learn how the algorithms work.

The notebook is divided into two parts:

### Part 1: MDS

The first part of the notebook demonstrates how to use the MDS algorithm to draw a map of Iran using the distance table of Iranian cities. The notebook reads the distance table as a DataFrame using Pandas, implements the MDS algorithm to calculate the location of the cities in a two-dimensional space, and plots the resulting map using Matplotlib. Additionally, a Sklearn implementation of MDS is also provided for comparison.

### Part 2: ISOMAP

The second part of the notebook demonstrates how to use the ISOMAP algorithm to extract features from a set of images and reduce their dimensions to the R2 space. The notebook uses a dataset of grayscale images of human faces obtained from the Labeled Faces in the Wild (LFW) dataset. The ISOMAP algorithm is implemented using NetworkX and NumPy, and the resulting features are plotted using Matplotlib. Additionally, a Sklearn implementation of ISOMAP is also provided for comparison.


## Acknowledgments

This project was created as part of a course on Computational Data Mining at AUT . We would like to express our gratitude to our course instructors and fellow students for their guidance, support, and valuable feedback throughout the development of this project. Their contributions have been instrumental in shaping the project and improving its quality.
