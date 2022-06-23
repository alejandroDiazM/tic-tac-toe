# TIC-TAC-TOE

These game of tic-tac-toe written in Python will pin you against two different kind of opponents: one, fairly easy, that picks a random square for its next move, and another that's written to never loose, only win or draw.

To play, just clone the repo and run:

```python
python game.py
```

The default settings are as follow (lines 99 and 100 of game.py):

```python
x_player = SmartComputerPlayer('X')
o_player = HumanPlayer('O')
```

If you want to play as X (who plays first), copy and paste the next lines in 99 and 100 instead:

```python
o_player = SmartComputerPlayer('O')
x_player = HumanPlayer('X')
```

Also, if you need to win at least once, change the "Smart" part in the other player for "Random", and then run the program.