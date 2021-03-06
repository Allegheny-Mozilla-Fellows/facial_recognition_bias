## Convolution neural network(CNN)

Info about the algorithm

## Run

### With Poetry

- Navigate to `src/CNN` directory and run: `poetry run python classify.py`

NOTE: You may run `python classify.py` directly, if you are inside the poetry shell.

### Without Poetry

- After installing all the dependencies locally Navigate to `src/CNN` directory and run: `python classify.py`

## Required arguments

  - `--females` number of images of females, maximum amount is 5407.
  - `--males` number of images of males, maximum amount is 4372.

sample command: `python classify.py --females 1500 --males 1500`

You may adjust the numbers as necessary to experiment with the algorithm.or example increase the number of input images for one group and observe how that affect the precision of the trained model. The input data
will be split into training and test data, where test data share is 0.3.

## Output

The output is a classification report, and labeled sample image, press any key to get labels for more images.

(https://www.tensorflow.org/tutorials/images/cnn)