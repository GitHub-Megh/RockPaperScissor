
# Project Title

# rock-paper-scissors

An AI to play the Rock Paper Scissors game

## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV

## Set up instructions
1. Clone the repo.
```sh
$ git clone https://github.com/Github-Megh/RockPaperScissor.git
$ cd rock-paper-scissors
```

2. Install the dependencies

3. Gather Images for each gesture (rock, paper and scissors, and None)

In this example, I collected 70 images for the "rock" gesture
```sh
$ python3 Collect_images.py rock 200
```

4. Train the model and test the model performance
```sh
this is done on Google Colab to make use of GPU acceleration. 
```

5. define the logic of the game and start the play
```sh
$ python3 play.py
```