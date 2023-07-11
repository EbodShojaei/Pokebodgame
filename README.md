# Pokémon Card Matching Game
### COMP2537_Assignment4

This is a single-page web application that fetches and displays information about Pokemon from the PokeAPI into a card-matching game that includes features such as card flipping, click validation, match validation, a winning event, header information display, start and reset buttons, different difficulty levels, customizable themes, and power-up mechanics integration.
<br>
##### Hosted (**[Link](https://pokebodgame.netlify.app)**)
##### Video (**[Link](https://www.youtube.com/watch?v=6cJT8tTSC0Y)**)

<br>

	 Author: Ebod Shojaei
	 Version: 1.0

<br>
    
## Features
- **Fetching Pokemon**: 
    > - The app fetches a list of Pokemon objects from the PokeAPI, caching the IDs and image URLs of the Pokemon into an array before DOMContentLoaded to reduce number of repeat API requests to just a single call.
- **Responsive Design**: 
    > - The app is designed to be responsive and work well on different devices and screen sizes.
- **Card Flipping**: 
    > - When a card is clicked, it flips over.
- **Click Validation**:
    > - If a card is clicked twice, nothing happens.
- **Match Validation**:
    > - If a clicked card is already matched, nothing happens.
- **Maximum Flipped Cards**:
    > - If two cards are already flipped, clicking another card does nothing.
- **Winning Event**:
    > - Display a winning message when all cards are clicked.
- **Header Information**:
    > - Show the number of clicks made by the user, the number of pairs remaining, the number of pairs matched, the total number of pairs, and the game timer.
- **Start and Reset Buttons**:
    > - Add buttons to start or reset the game.
- **Difficulty Levels**:
    > - Include different difficulty levels in the game.
- **Themes**:
    > - Provide various themes to customize the game's appearance.
- **Power-up Logic**:
    > - Integrate power-up mechanics into the game.

<br>

## Requirements
- The app requires the following dependencies:
    > - **axios**: A promise-based HTTP client for making API requests.
    > - **jquery**: A JavaScript library for DOM manipulation and event handling.
    > - **bootstrap**: A popular CSS framework for styling the app.
    > - **popper.js**: A library required by Bootstrap for handling dropdowns, tooltips, and popovers.

- The app also uses custom CSS and HTML files for styling and structure.

<br>

## Usage
To use the app on your local machine, follow these steps:
- **Clone** the repository to your local machine.
- **Open** the index.html file with a live server.
	> - The app will automatically fetch the Pokemon data from the PokeAPI and display the Pokemon cards.
- **Use** the game buttons to navigate through the game.
- **Click** the flipped over cards to reveal who's that Pokemon.
- **Click** the "Power Up" button to temporarily view all the hidden Pokemon to help find matches.

**Note**: Internet access is required to fetch data from the PokeAPI.

<br>

Enjoy playing in the world of Pokemon!

<br>

## Resources
- **[ChatGPT-4](https://chat.openai.com/)** by OpenAI
	- Used for debugging

<br>
