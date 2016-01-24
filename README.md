# Mastermind-with-AI
This is a mastermind implementation on the command line.
To start a new game just create a new game class.
```
a = Game.new()
```
This should ask you to create a code.
Write it in the following format
ex. rrgg 
The code can be any length 
If the code is more than 4 letters long you will be asked if youe are sure you want to make the code x letter long.
If you want to solve the code yourself use the  ```.player.play ``` method
Example 
```
a.player.play
```
and then type your code.

to make the computer solve it use ``` .player.analyze ```
Example 
```
a.player.analyze
```
to make the computer genrate a secret code,set the guesser attribute of the player to 1.
Check the ``` Game.initialize ``` method for more information and more options.
Please leave reviews and pull requests for any modfications.
Be free to refactor the code as it needs refactoring
P.S the computer uses the Five-guess algorithm (Donald Knuth) to solve the code.
