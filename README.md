### Built With

* [React](https://reactjs.org/)
* [Python](https://www.python.org/)
* [Tensorflow](https://www.tensorflow.org/), [Keras](https://keras.io/about/)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [OpenCV](https://opencv.org/)

<!-- GETTING STARTED -->
## Getting Started

Instructions will be posted shortly
### Prerequisites

#### Backend
* [NumPy](https://numpy.org/)
```pip install numpy```
* [OpenCV](https://opencv.org/)
```pip install opencv-python```
* [Tensorflow](https://www.tensorflow.org/)
```pip install tensorflow```
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
```pip install Flask```
* [python-chess](https://python-chess.readthedocs.io/en/latest/)
```pip install chess```

#### Frontend
* [ChessboardJSX](https://chessboardjsx.com/)
```npm install --save chessboardjsx```
* [React Webcam](https://www.npmjs.com/package/react-webcam)
```npm install react-webcam```

#### Hardware
* Webcam
* Tripod (or any other way to mount the webcam)

### Start the app
In the directory named "frontend", run:
<br/>
```npm start```
<br/>
In the directory named "Backend", run:
<br/>
```python api.py```

<!-- USAGE EXAMPLES -->
## Usage

### Web App

<strong> Note: Due to a lack of training images, the ScanChess app works only on chess sets similar to the one shown in the demo video: black and white chess pieces with green and white chess board. </strong>

1. Set up your webcam to capture an overhead view of the chess board.
2. Make sure the chess board is empty, and press "Calibrate".
3. Set up the chess pieces and press "Calibrate" again to complete the calibration.
4. Play a chess move. Press "Confirm Move" once the chess move has been made. The digital chess board should update accordingly. 
5. Continue playing the game until checkmate or stalemate. Remember to press "Confirm Move" after every move.
6. Watch the game unfold on the digital chess board, copy the pgn notation for your records, or plug the FEN position into an engine to analyze the game!

### Chess Image Classification

The file named ChessImageClassification holds the notebook I used for gathering a training dataset and training the convolutional neural network. The model classifies whether an image is a white piece, a black piece, or an empty square. The dataset I used to train my model is not included in this file because the it is too large. Feel free to download the code yourself to train a model on your own dataset.

<!-- CONTACT -->
## Contact

Email: bz88keys@gmail.com

Project Link: [https://github.com/brian386/ScanChess](https://github.com/brian386/ScanChess)



 
