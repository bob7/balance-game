# balance-game


<p>Grid-cells are numbered naturally, from top-left to bottom right and</p>
<ul>
<li>Player-1 and player-2 click cells/numbers alternately</li>
<li>cells clicked by player-1 are indicated by a gray top-half fill</li>
<li>cells clicked by player-2 are indicated by a green bottom-half fill</li>
</ul>

<p>Player-2 is to keep his choices evenly distributed relative to those of player 1.</p>

<p>This is measured by the <strong>score</strong> at each cell n:</p> 

<p>the number of clicks in [1,n] that any player has achieved since the last click in [1,n] by the other player.</p>

![](./balance.png)

<p><strong>Rules</strong></p>
<ul>
<li>Player-2 needs to keep the score of each cell below 5</li>
<li>No player can pick any number he has previously picked</li>
<li>Player-2 cannot click a number which is adjacent to one he has previously clicked.</li>
<li>Player-2 may pass his turn by clicking outside the grid.</li>
</ul>

<p>Player 1 wins when player 2 violates one of the restrictions above</p>
<p>Player 2 wins if he has not lost by the time player-1 has picked all cells.</p>
<p>Press <strong>Auto1</strong> to play as player-2 against a random-picking player-1.</p>
