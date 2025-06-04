This is a simple web-based game launcher that lets you quickly browse and launch your collection of HTML5 games from one page. It includes a search box to filter games by name and opens each game in a new window inside an iframe for a clean, fullscreen experience.

Features
Game List: Displays all your games as buttons.

Search Functionality: Quickly find games by typing part of their name.

Clean UI: Dark-themed and responsive layout.

Launch Games: Opens the selected game in a new browser window with fullscreen iframe.

How It Works
The list of games is stored in a JavaScript array with each game having a name and url.

The page dynamically creates buttons for each game.

When you type in the search box, the buttons filter in real-time to show only matching games.

Clicking a game button opens a new window that loads the game via an iframe.

Code Overview
HTML: Contains a search input and a container div where buttons are dynamically added.

CSS: Styles the page with a dark background, styles buttons and input for a modern look.

JavaScript:

games array holds the game info.

renderButtons() creates buttons based on the current search filter.

launchGame(url) opens the selected game in a new window with fullscreen iframe.

Event listener on the search input updates the displayed buttons as you type.

How to Use
Add or update games in the games array in the script section.

Open the HTML file in a modern browser.

Use the search bar to find a game.

Click the button to launch the game in a new window.
