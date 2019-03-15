## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/BoseEinstein/platformer/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

# Platformer! by Team2



## Download!

[Click here to download!]


## Documentation
[Click here for documentation](Docs/html/index.html)

## Gameplay Trailer






## Screenshots




## Platformer Post Mortem
The main thing that could be improved is the design of the level loader and the enemy controller class. In the course of development a circular dependency was accidentally created between these two, requiring a less than ideal work around to prevent a full redesign.

Similarly, I would like to decouple the physics from the player and develop a standalone physics system that could apply to everything. This would allow for the enemies to be more dynamic and exist on the underside of platforms, allowing the creation of levels that could better utilise our gravity flip mechanic.

The GameController class also has split duty between keeping track of game state and updating the UI, this should be separated out to different classes.

A robust and smooth menu interace would also greatly improve the user experience.

### Team Limit Break
- James Thomas
