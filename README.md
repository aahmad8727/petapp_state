
Explanation of the Code:
1.	State Variables:
•	petName, happinessLevel, and hungerLevel represent the current state of the digital pet.
2.	Methods:
•	_playWithPet and _feedPet methods update the state variables using setState.
•	_updateHappiness and _updateHunger methods modify happiness and hunger based on certain conditions.
3.	UI Elements:
•	The UI displays the pet's name, happiness level, and hunger level.
•	Two buttons, "Play with Your Pet" and "Feed Your Pet," trigger state changes.

Additional Features for the Team to Implement:
2.	Dynamic Pet Color Change (To-Do Task):
o	Based on the pet’s happiness level, change the pet’s color dynamically:
	Happiness Level > 70: Green (Happy)
	Happiness Level 30–70: Yellow (Neutral)
	Happiness Level < 30: Red (Unhappy)
o	Use setState to update the color of the pet dynamically in the UI, making the pet’s emotional state more visually clear to the user.
3.	Pet Mood Indicator :
o	Introduce a text-based mood indicator next to the pet:
	Happy, Neutral, or Unhappy based on the happiness level.
o	Display a corresponding emoji or mood icon to visually represent the pet’s mood.
4.	Pet Name Customization:
o	Allow users to set a custom name for their pet at the start of the app.
o	Include a text input field and a button to confirm the name, which will then display in the UI.
5.	Automatic Hunger Increase Over Time:
o	Use Timer from dart:async to automatically increase the pet’s hunger level every 30 seconds, even when the user is not interacting with the pet.
o	This simulates a real-time experience, where the pet needs to be fed periodically to stay happy.
6.	Win/Loss Conditions:
o	Implement a win condition where the player "wins" if the happiness level remains above 80 for a certain duration (e.g., 3 minutes).
o	Implement a loss condition if the hunger level reaches 100 and the happiness level drops to 10, displaying a "Game Over" message.
Additional Features: You must complete any three of the four features in order to gain full credit

Add Energy Bar Widget - Introduce a new widget to represent the energy bar. This widget can be a LinearProgressIndicator or a custom-designed widget.

•	Place the energy bar below the existing UI elements in the Column of the CounterWidget class.

Implement Energy Level Logic-
•	Define a new state variable _energyLevel in the _CounterWidgetState class to store the pet's energy level.

Implement Activity Selection:
•	Introduce a new UI element, such as a dropdown menu or list, to allow the user to select an activity for the pet.
•	Create a mechanism for the user to confirm their selection and trigger the chosen activity.

Update Pet State:
•	Implement logic to update the pet's happiness level and energy based on the selected activity.
•	Ensure that engaging in activities increases the pet's happiness and energy, while neglecting the pet may result in decreased well-being.


