# Mystery Number Challenge

## Group Information:
- Likhona Ngwenya -> ST10446272

## Application Details
- App Description 
-- Mystery Number Challenge is a fun and interactive React Native app where players try to guess a randomly generated number between 1 and 100. The game provides real-time feedback by telling the player whether their guess is too high, too low, or correct, making the experience engaging and intuitive. Each guess is counted, allowing players to track the number of attempts they’ve made. When the correct number is guessed, the app displays a congratulatory alert and automatically starts a new game. There’s also a Restart Game button that lets users manually reset the game at any time. Through simple inputs, alerts, and feedback, the app demonstrates effective use of state management in React Native while offering an enjoyable and user-friendly gameplay experience.

## Game Features 
1. Random Number Generation: The game must generate a number between 1 and 100.
2. Guessing Mechanism: Users input their guesses using a `TextInput` component.
3. Feedback: The app must provide feedback for each guess, indicating if it is "too high," "too low," or "correct."
4. Guess Count: Track the number of guesses made by the user and display this count on the screen.
5. Restart Button: Include a button that resets the game, generating a new number and resetting the guess count. 

## Game Flow
1. App starts → Generates a random number.
2. User types a guess → Presses Submit Guess.
3. App:
	- Validates the input.
	- Updates guess counter.
	- Displays feedback.

4. When the user guesses correctly:
	-Shows a success alert.
	-Resets the game automatically.

5. At any time, the user can restart manually using the Restart Game button.


## Core Functionality
### Feature				      What It Does

Random number		--> 	Generates a number between 1 and 100
User input	-->		Allows entering a guess
Submit button		-->	Checks the guess and updates feedback
Feedback system		-->	Guides the player by saying too low/high/correct
Guess counter	-->		Tracks number of attempts
Restart button	-->		Starts a new game manually
Alerts	-->			Handles invalid inputs & congratulates winners

# Screenshot
- <img width="454" height="759" alt="Mystery Number Challenge" src="https://github.com/user-attachments/assets/477069b1-988e-4ec3-87d2-bc14d1473afc" />

