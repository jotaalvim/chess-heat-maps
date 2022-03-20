# chess-heatmaps


Heatmap representation of chess moves, it shows the squares that each piece has been moved to more times.

This are the heatmaps from the knigth, bishop, queen, rooks , pawns and the king, respectively, in the player's white games.

Heatmaps from a weak player (800 blitz lichess)

![Screen shot](./assets/1.png)

Heatmaps from a medium/average player (2000 blitz lichess)

![Screen shot](./assets/2.png)

Heatmaps from a very strong player (2700 blitz lichess)

![Screen shot](./assets/3.png)

## It's cool but not that informative
From simply looking at the maps there's not much information that we can collect, we can perhaps
conclude that the weaker players often move the queen to the more obvious d1-h5
diagonal instead of placing in c2 or d2. Another thing is
that the dark bishop in played far less times by the weaker and medium players
than by the stronger player. It's hard to say but those things might be happening due to different openings choices.

## Diferences between players 
A more useful and interesting data would be the logarithm diferencies between 
the moves from each player. Here is an example of the diferencies between a
stronger and a medium player, in this case the squares more highlighted tend 
to be "better" squares and not as frequently player for the medium player pieces.

![Screen shot](./assets/4.png)

## Opening analisys
The heatmap but restricting the search for only the x amount of moves. Here's
an example of the first 

