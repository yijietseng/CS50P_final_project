    # Little Dino rush
    #### Video Demo: https://youtu.be/g6d4SsQZ8ks
    #### Description:
    This project contains the following:
    1. project.py
    2. test_project.py
    3. img/
    4. sound/
    project.py is the main game script, which can be exeuted by python project.py. After the main function in project.py is called, it sets some global varibles and it will initiate pygame and load in the animation images and sounds. While it is in the actual game loop, it checks if a player has pressed any keys to start the game. Once the game is started, it will update the game with FPS of 60. When a player is dead, it will enter another game loop to execuate a game over function to show the game over screen and prompt the player to restart. On the other hand, test_project.py contains the unit tests for some of the functions in project.py.

    This game is developed for the final project of CS50’s Introduction to Programming with Python. It is under the inspiration of google's running dinosaur game. The code of this game is written using the pygame module. Player will be controlling a running little dinosaur by pressing the space bar to jump over obstacles. The score is recorded at the top center of the window and the highest score is recored on the top right corner. When a player runs into an obstacle, the game is finished. However, it can be restarted by pressing "R".

    Before running the game, a player must install pygame module via pip install pygame. In order for the game to be executed successfully, the folds name img/ and sound/ should be placed at the same level as the project.py. There is a module in python called auto-py-to-exe that can make this game into a .exe file which can then be executed without installing pygame. However, the .exe file still needs to be placed in the same level as the img/ and sound/ in order to be successfully executed.


    TODO
    To run this game:
    1. before running the game, install pygame module using 'pip install pygame' in the terminal
    2. In the terminal, input python project.py

    GAMEPLAY:
    1. The running speed increases as the player scores during the game.
    2. The game will end when the player hits an obstacle.
    3. If a player wishes to restart the game, just simply press "R".
    4. The game is set to record the highest score from the previous runs.



