# Square Online
Demo unity online game using [`UnityWebRequest`](https://docs.unity3d.com/ScriptReference/Networking.UnityWebRequest.html) to send and receive position updates of the squares.

The client is the unity game and the server is built using spring boot + redis to expose rest services to create and update the game status. 

## Controls
Move your square with `W A S D` keys.

## Play
The first person to enter will be player one (blue) and it will create the game. Once the game is created the next person to enter will be player two (red). 
The game will expire after `20` seconds of inactivity.

[`https://pazzesko.github.io/square-online-webgl`](https://pazzesko.github.io/square-online-webgl/)
