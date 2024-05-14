# paddleBall
Amiga Paddle Ball Game - 2024

I'm getting back in to Amiga Land after quite along time.
I had an Amiga 1000, from about it's beginning in 84 or 85, and then an Amiga 2000.
They worked into the 90's.   I gave away the 1000, and the 2000 eventually broke down.

Well now I'm back, unfortunately working in an emulator, but soon, I hope to in a real Amiga.

Here is a simple Amiga Basic game, of the type people wrote back then.

I think mine is a unique version of a paddle ball type game.
You move the mouse up and down to move the paddle up and down.

The object is to score points by bouncing the tennis ball against the left side of the screen.
Two twists:   The paddle has 2 sides, and you can flip the paddle by clicking the main mouse button. 
One side of the paddle speeds the ball up on each hit. The other side slows it down.
Your bounce score is greater the faster the ball is going.

The other twist is that as the game progresses, your paddle will move closer and closer to the left side, making it harder to play.
However, there is a flying football!  If the football hits your paddle while going to the right it moves your paddle to the right.
If it hits it while going left it moves your paddle further left.

The game keeps track of the top five high scores.

INSTALLATION:
Just copy all the files in this repository to a floppy
and run with the floppy in DF0:  
If you want to run it from a hard drive you can copy all the
files to a directory there, but then youll have to adjust
the paths in the several OPEN statements. 

RUNNING:
Start AmigaBASIC, then type:
   run "df0:paddleBall"
