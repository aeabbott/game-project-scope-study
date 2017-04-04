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

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?
-   How will you use version control to backup / track your project?
-   Do you plan to attempt any of the bonuses?

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).

Data-Structure:
I'm currently on the fence about creating an arrays for the winning combinations and player choices.

Game-Board MarkUp:
Right now, I am thinking of making 9 divs and floating them to make a tic tac toe board.

User Stories:
1. As player one, I want to be 'X' so that I alway starts.
2. As player two, I want to be 'O' so that I will always go second.
3. As a player, I don't want player one or player two to be able to go twice in a row so that a fair game is played
4. As a player, once a winner is called, I want the game to present me with an option to play again so that I can play again.
5. As a player, if a cats game has occurred, I want the game to present me with an option to play again so that I can play again.
6. As a player, if I chose to play again, I want the board to be cleared so that I will be able to start clean.
5. As a player, I want the traditional rules of tic tac to be enforced(three in the row of either X or O will win the game) so that I will know how to play. Horizontal winning combinations.
6. As a player, I want the traditional rules of tic tac to be enforced(three in the row of either X or O will win the game) so that I will know how to play. Vertical winning combinations.
7. As a player, I want the traditional rules of tic tac to be enforced(three in the row of either X or O will win the game) so that I will know how to play. Dianogial winning combinations.
8. As a user, I want to be able to visually see if a "cat-game" has occured, so that I know that neither player 1 nor player 2 won.
8. As a user, I want to be able to create a username so that I can login into the game console.
9. As a user, I want to be able to log into the game console.
10. As a user, I want to see my game history (wins, loses and cats) when I log into the game console so that I can see my wins and loses.
11. As a user, I want to be able to log out of the game console when I am finished so that no on else can play under my account.
12. As a user, I want to be able to update my password so that I have the liberty to change my password if I want to.
13. As a user, when a cats game has occrued, I want a picture of Ellie Gouldfish to display.


Code Modular:
To keep my code modular, I plan on having an index.html file, a style folder with my css and images inside, an assets folder with my index.js, api.js and events.js.

I will attempt to my make my functions small and simple so that my code will be more readable.

Creative Spin:
When a cat's game has occurred, I would like a picture of my cat to display.

Version Control:
I play on coorelating all my git pushes to a user story. Before I push my changes, I will commit early and often!

Bonuses:
I'm going to attempt the user name player history.

Additional Questions-- I need some clarification on the following requirements:
 1. RQ: Support playing multiple games at one time
    Quesiton: Does this mean that the same user wants to play multiple games at once or does multiple games mean different users playing all at the same time.
 2.  Is there a mobile requirement?
