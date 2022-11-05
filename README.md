# The sum game - React + Node.js game

### Information
[Current application link](https://ghaarp.github.io/TheSumGame/ "TheSumGame").

### Overall
TheSumGame - easy game application, made to learn basics of React and Node.js development. In this game, you need to guess 3 of 9 cells with maximal numbers. The sum of cells you guessed is your score. Application has a high-scores page, where you can see everyone's scores and your own scores only.

### How to start
[This is actual link](https://ghaarp.github.io/TheSumGame/ "TheSumGame") to GitHub pages with a game client. You need to register or login to start the game.

### Some technical details
TheSumGame is an easy game, but not that easy as an application. It uses a Node.js server to avoid cheating, so you can't to know which number are hiding behind cells without opening them. Also, the server uses a PostgreSQL database to save all game data, so you can break the game at any moment and continue it later, if you know the game ID. You can't continue the game if it isn't yours. Game ID always shown on a game page. Server is configurable, so you can set up cell count, and number of cells to open. I didn't expose that variables anywhere, so it only may be configured via source code changes. You can see a full project source code (client + server) [here](https://github.com/Ghaarp/TheSumGameReact "TheSumGame")

### Why i made this application
I created this application to practice my full-stack development skills and to learn how to deploy applications on cloud hosting. 
