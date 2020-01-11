# Android Game (About)
The following app contains 3 different games, Maze, Tapioca Launcher, and Tiles while
also having a log-in system allowing you to save your progress and in-game stats.
While playing games, you can also earns coins, that can be used to purchase items.
You can also customize your experience by changing the language, theme, and your sprite for the maze.

# Setup 

1. Open Android studio and checkout from version control 
2. Enter https://github.com/TomKan0909/android_games.git and clone the project
3. Open emulator and select PIXEL 3 API 28 and run the app 

# Parts I implemented 

1. Maze Navigator game. Goal of the game is to escape the maze in the fewest number of steps.
Collect coins to increase your score by a random amount. There are three difficulty levels.
![easy][images/maze_easy.png] ![medium][images/maze_medium.png] ![hard][images/maze_hard.png]

At the end of each game, the score is recorded and the score is also converted to coins. This also
applies to the other games(Tiles and Tapioca Launcher).
![record_score][images/record_score.png]

2. All CRUD operations in the game. The login & register functionality. 

![login][images/login.png] ![register][images/register.png]

Retrieving display user's high score, average score, best time ,average time taken for each game.

![user_stats][images/user_stats.png]

And recording in game micro-transactions.

![store][images/store.png] ![store_bought.png]












