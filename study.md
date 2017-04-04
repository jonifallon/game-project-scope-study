# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.  http://imgur.com/a/Ce5lc
-   The data structure you plan to use.
-    Entities include:
-     Player (Token choice: X or O, login name, password, player # (1st or 2nd) )
-     Gameboard (squares, color/image)
-     Game info and access:  (login button, reset password button, signup button,
-        logoff button, start game button, score indicator.)
-   How you will take the markup of the game board and represent it in JS
-      I'm not exactly sure what this is asking.  JS will be used for the logic--
-      EG determining if game is win/lose/cat, listening for interactions from
-      the user, presenting the user with scoring information.
-   How you plan to approach this project.
-      I started it last weekend, methodically approaching the html/css/js trying
-      to create a board that stayed a static size regardless of screen resizing.
-      I then created divs for each 'tile' on the game board, and id's for each
-      tile.  I then added listener events and console.log'd each time I hit one.
-      I then pushed that info to an empty array to capture which tiles had been hit.
-      All that didn't include any X's or O's or individual user info.  I was just
-      taking small steps to try to get the listening events in, and then tried to figure
-      out a piece of the logic.  I was at a standstill, because the way I approached it,
-      I ended up needing to compare one array (with 3-5 possible elements) to a nested
-      array of 8 individual arrays each with 3 elements.  All the possible ways I found
-      to compare arrays did not work, so I'm back at the drawing board.  At least it
-      got me deeper into working with arrays/js.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?  IF I still had photoshop and IF I
-      have time, I would love to add b/g images to each 'tile' and flip them when a
-      user selects the tile.  I would love to offer the user an option of "themes" to
-      choose from (EG baseball, Easter, football...) where different background images
-      and X's and O's could be used.  I'd also love to add sound, EG when some wins,
-      cheers could be heard.  So many good ideas, so little time.
-   How will you use version control to backup / track your project?  I already started
-      that when I was working this weekend.  I'm a frequent saver, so I am a proponent
-      of committing early and often.  There is nothing worse than rework because your
-      computer crashed and you didn't save something.
-   Do you plan to attempt any of the bonuses?  I would love to if time permits.
-    I'm especially interested in a visually appealing interface for both
-    desktop and mobile users.  If I had a photoshop license on my mac, I would
-    absolutely be putting it to use!


You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
