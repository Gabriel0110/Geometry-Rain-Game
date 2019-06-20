# Geometry-Rain-Game
A personal game project that I came up with during my undergrad.  Most of the functionality and mechanics are complete, but not 100% -- it's playable, and can be quite difficult ;)

I always wanted to finish it and publish it to Steam or something, but maybe one day I'll come back to it after I accomplish my AI/ML goals.

I do, however, have a new use for it -- Reinforcement Learning practice.  I wanted to upload it here to showcase it and for anyone to test it out if they wanted to. My goal is to use OpenAI's CartPole RL with DQN program to help me create a DQN to learn to play my game.  Why?  Because the mechanics are quite the same.  You either move left, or you move right -- that's it.  Dodge the red and yellow shapes to survive, and collect green triangles to gain extra points and bonuses.  The longer you live, the higher your score.  Sounds like a perfect RL project to me.

The only thing I want to fix is the restart mechanic when it's game over.  It's a bit buggy, so in order to have a smooth and quick restart to jump right back in to a fresh run, I'll have to fix the restart.  Other than that, at this point I think it's good to go for testing.

# Play the Game
Simply download all files.  Unzip the .rar files with the other files and run the GeometryRainHardmode.exe to play the game.  I had to zip the data files because there was a lot of them for a GitHub upload.

Controls:
 - Move left: left arrow key
 - Move right: right arrow key

Shapes:
 - Red Hexagon: hit this and you lose the game
 - Yellow Square: slows you down significantly and reduces your score
 - Green Triangle: increases your score and resets your speed if you hit a yellow square.  Get 5 in a row without missing one or hitting a    yellow square, and you get a very large score boost with an activatable ability to slow down all falling shapes for a certain amount of    points.
 
