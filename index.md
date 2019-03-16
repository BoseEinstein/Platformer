## Gravity Reversal Platformer


## Download!

[Click here to download!](https://drive.google.com/file/d/1XUS9kCdc3grlqoUV-f6pDagH1nQa_pti/view?usp=sharing)


## Documentation
[Click here for documentation](Docs/html/index.html)

## Gameplay Trailer


<iframe width="560" height="315" src="https://www.youtube.com/embed/nuksXo96LBw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## Screenshots

![img1](/images/scrrenshot1.png)
![img2](/images/screenshot2.png)
![img3](/images/screenshot3.png)


## Platformer Post Mortem
The main thing that could be improved is the design of the level loader and the enemy controller class. In the course of development a circular dependency was accidentally created between these two, requiring a less than ideal work around to prevent a full redesign.

Similarly, I would like to decouple the physics from the player and develop a standalone physics system that could apply to everything. This would allow for the enemies to be more dynamic and exist on the underside of platforms, allowing the creation of levels that could better utilise our gravity flip mechanic.

The GameController class also has split duty between keeping track of game state and updating the UI, this should be separated out to different classes.

A robust and smooth menu interace would also greatly improve the user experience.

### Team Limit Break
- James Thomas
- Leslie Xu
-Ruby Tartakovsky

