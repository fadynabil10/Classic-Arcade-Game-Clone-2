# Classic Arcade Game Clone: Frogger

This game is a [project](https://github.com/udacity/frontend-nanodegree-arcade-game) from the [Front End Web Developer nanodegree](https://udacity.com/course/front-end-web-developer-nanodegree--nd001/) by [Udacity](https://udacity.com).

## Objective
Catgirl is not like those cats that hate water, she wants to cross the stoned path so she can finally go for a swim at the lake. So all you need to do is
get Catgirl to the water and you **win** the game.
But beware the bugs! They are Catgirl's mortal enemies and you can't touch them at all or you **lose**!

So, to sum it up:
1. Get to the water
2. Don't touch the bugs

## Getting Started
**Click [here](http://calaca.github.io/fend-arcade-game) to play the game.**

Or, if you want to play it locally on your computer, you can either download the files from this repository or clone them:
- **Download:** Click the "Clone or download" button then click "Download ZIP" and soon you'll get a zip file when your download finishes. Unzip the file, open the index.html file on your browser of choice and that's it!
- **Clone:** Type into your terminal or command prompt the following:
`$ git clone https://github.com/calaca/fend-arcade-game.git`
When it finishes cloning the files, open the index.html file on your browser of choice and that's it!

## Controls
* **left ←** to move Catgirl to the left
* **right →** to move Catgirl to the right
* **up ↑** to move Catgirl up
* **down ↓** to move Catgirl down

<br>

## Getting Started

###### Local

###### 1. Clone this repo

```
$ git clone https://github.com/mikejoyceio/arcade-game
```

###### 2. Serve the application

```
$ python -m SimpleHTTPServer
```

Detailed Python Simple Server instructions can been found [here](https://docs.python.org/2/library/basehttpserver.html).

###### 3. Open the application

```
$ open "http://localhost:8000"
```

<br>

<h1>Arcade Game Demo</h1>
<br><br>
<p>Classic arcade game clone https://www.youtube.com/embed/kaifTslArtY</p>
<br><br>
# Introduction

An HTML5 Canvas powered video game, developed using the best practices in Object Oriented JavaScript. 


# Play the application

1. Moving player (left, right, up or down) by using arrow key on the keyboard against any enemy.

2. If player have a collision with an enemy, the player will be back to a default position (at the bottom of game screen), and a point will be decreased.

3. If player reach the top of the game screen without any enemy's collision, the player will have a point. 

4. Default 10-points are bonus at the beginning

5. When player arrives to Gem at the top without any enemy's collision, energy will be dramatically increased, blood will be filled until staying there without any enemy.

6.Some features Cooming Soon ......


# Code
## Building: 
1. Create class of 'Contestant'
Both Enemy and Player are Contestant, they have same method of 'render'

2. Declare global variables at the top

### Create its own method for 'Player' and 'Enemy'

1. update
2. handleInput
3. Create a class of Gem and its method. 
Render two Images Gem and blood when player coming that position.  
4. Create allEnemies as array of object of class Enemy

+ All enemy objects in an array called 'allEnemies'
+ All enemies have their own random positions and speeds running the screen. 


<h1>References</h1>
<ul>
	<li><a href="https://github.com/bahalps/frontend-nanodegree-arcade-game">bahalps's game</li>
	<li><a href="https://github.com/sheryllun/Project3-BugAvoider">sheryllun's game</li>
	<li><a href="https://github.com/ftchirou/frontend-nanodegree-arcade-game">ftchirou's game</li>
	<li><a href="https://github.com/udacity/frontend-nanodegree-arcade-game">Udacity JS helper</a></li>
</ul>
<br><br>
<h2>Fady Nabil</h2>
