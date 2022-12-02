# Hot Potato

A WebSockets application demo.
The app is the hot-potato-starter which get provide by the Codecademy for hands-on for

# Files
* server.js => the file that server broadcast the data to the clients who get connected to the server.
* public/index.html => the file for it display the data from the server the clients connected.
* utils/constans.js => the file has the common constant value to use the type for it deliver the data between the server and clients.

## Rules

* Upon connecting to the server, choose a name. This name will be displayed to other players at the start of the game. Your own player will show the text "You".
* Once the 4th player has joined the game, the game will start and the clock will begin counting down from 30.
* When the game starts, one player will be chosen randomly to hold the potato.
* If you are holding the potato, click on another player to pass the potato.
* If you are holding the potato when the time is up, you will lose!
* Only 4 players may join a game.
