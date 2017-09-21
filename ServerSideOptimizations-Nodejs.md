### Game Server-side optimizations for Node.js

##### Socket.io and it's performance

Short answer: If you're using a socket.io version below 2.0, please update to > 2.0!

Long answer:
If you are using socket.io for handling websocket.io please note that the performance for versions below 2.0 have big performance penalties, make sure to update socket.io to the latest version to benefit from the performance improvements.

##### Fast-paced browser games

Games like Agar.io and Slither.io handle hundreds of players on a single server. They take advantage of low level API's.
