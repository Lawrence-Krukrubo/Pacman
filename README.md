<h1 align="center">Welcome to Pacman</h1>
<br>
<p align="center">
<img src="https://github.com/Lawrence-Krukrubo/Pacman/blob/master/images/pacman-img.jpg?raw=true" alt="pacman image">
</p>
<br>

<p>
Pacman lives in a shiny blue world of twisting corridors and tasty round treats. Navigating this world efficiently will be Pacman's first step in mastering his domain.

The simplest agent in searchAgents.py is called the GoWestAgent, which always goes West (a trivial reflex agent). This agent can occasionally win:

<b>`python pacman.py --layout testMaze --pacman GoWestAgent`</b>
But, things get ugly for this agent when turning is required:

<b>`python pacman.py --layout tinyMaze --pacman GoWestAgent`</b>
If Pacman gets stuck, you can exit the game by typing `CTRL-c` into your terminal.

Soon, your agent will solve not only tinyMaze, but any maze you want.

Note that pacman.py supports a number of options that can each be expressed in a long way (e.g., --layout) or a short way (e.g., -l). You can see the list of all options and their default values via:

python pacman.py -h
Also, all of the commands that appear in this project also appear in commands.txt, for easy copying and pasting. In UNIX/Mac OS X, you can even run all these commands in order with bash commands.txt.
</p>

<p>
After downloading the code (search.zip), unzipping it, and changing to the directory, you should be able to play a game of Pacman by typing the following at the command line:

<b>`python pacman.py`</b>
</p>

<h3>Creators:</h3>
<p>
This pacman project was created as a learning resource to teach Informed and Uninformed search AI algorithms. It is part of the Udacity Artificial Intelligence Nanodegree program and should only be used for learning and study without publishing answers in blogs or social media.
</p>

For more details, contact the creators at this **[UC Berkley](http://ai.berkeley.edu/search.html)** site.