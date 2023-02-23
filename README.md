## __Battleship: Guadalcanal 1942__

Welcome to **Battleship: Guadalcanal 1942**. 

Battleship also known as Battleships or Sea Battle, is a strategy type guessing game for two players. It is played on ruled grids on which each player's fleet of warships are marked. The locations of the fleets are concealed from the other player.

On this project you will be able to play not only the multiplayer version (2 players) but also a History Mode (Player vs Computer) based on historical data with personalised dialogue.

[Live link to website](https://battleship-guadalcanal-1942.herokuapp.com/)

## __Tech Stack__

<img height="50" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png"> **VS Code**
<img height="50" src="https://raw.githubusercontent.com/gitpod-io/gitpod/master/components/dashboard/src/icons/gitpod.svg"> **Gitpod**
<img height="50" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png"> **Python**
<img height="50" src="https://user-images.githubusercontent.com/25181517/117364277-fc4eb280-aebd-11eb-8769-a3583c6a2037.png"> **Git**
## UX & Design

### User Stories

- As a player, I want to be able to see my opponent's board during the game so that I can make educated guesses about where their ships are located.

- As a player, I want to be able to make my moves by selecting the Row and Column on the game board so that I can play the game intuitively.

- As a player, I want to be notified when one of my ships is hit so that I can keep track of the game's progress.

- As a player, I want to be able to see which of my opponent's ships have been hit and which ones are still a mystery so that I can adjust my strategy accordingly.

- As a player, I want to be able to play against the computer or another player so that I can enjoy the game in different ways.

- As a player, I want to be able to see the results of the game, including which ships were sunk and which player won, so that I can review the game and improve my strategy for future games.

- As a player, I want to be able to play with different types of ships with varying sizes so that I can have a unique gameplay experience.

- As a player, I want to be able to play the game in different modes, such as a limited number of moves, so that I can add more challenge and variety to the gameplay.
### Flowchart

A flowchart is a graphical representation of a process or system that shows the steps or stages involved and the relationships between them. I created a flowchart to provide a visual representation of the steps that a user need to follow in order to achieve a particular goal, such as navigating through the application.

![Flowchart](assets/flowchart.png "Flowchart")

### Modules

- The [os](https://docs.python.org/3/library/os.html) module was used to create the clear_screen function to enhance user experience and reduce clutter on screen.

- The [random](https://docs.python.org/3/library/random.html) module was used place the ships randomly across the board game.

- The [time](https://docs.python.org/3/library/time.html) module was used for sleep() to create timers to get a smooth transition.

- The [sys](https://docs.python.org/3/library/sys.html) module was used to create a typing effect when presenting the information on the console.

### Features

- Introduction screen

    - When the app loads the user is presented with a menu that allows a better and easy navigation

    - The menu options are 2 play modes, information about the person who develop the app and exit option from the app

![Introduction Screen](assets/introductionscreen.PNG "Introduction Screen") 

- Introduction History Mode

    - When the user selects the "History Mode" is presented with an introduction to the game in this mode. The text is presented with a typing effect to simulate a message is being receive in the console.
    - In the introduction it makes clear the details of the computer ships

![Introduction History Mode](assets/historymodeintroduction.PNG "Introduction History Mode")


## Credits

### Concept

- Concept for History Mode is based on historical data better explained [here.](https://www.youtube.com/watch?v=G_QhTdzWBJk)

### Code

- Starting idea for functionality and design from [Parzibyte.](https://github.com/parzibyte) [here.](https://www.youtube.com/watch?v=43Vt9O_t4uY)
- Reviewed material for History Mode development [Michael Carberry.](https://github.com/cmikedev) [Here.](https://github.com/cmikedev/battleship)

### Design

- Tech Stack Icons [github.com/Marwin1991](https://github.com/marwin1991/profile-technology-icons)

## Acknowledgement

**[Harry Dhillon](https://github.com/Harry-Leepz)** for being my mentor on this project and provide excellent feedback from real work experience.