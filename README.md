# PirateGame

First, we added pirate symbols to the symbols array and use these symbols to check the winning condition.

In the spin() function, random symbols are assigned to each reel, and then each reel is displayed.

We updated the if conditions to check the winning condition:

If all three symbols are 7 or if all three symbols are the same and not 7, the player wins. We make the corresponding messages visible by adding appropriate classes to the #sevenMessage or #winMessage elements.

Otherwise, we hide the winning messages.

In the CSS part, we added the necessary styles for the new messages and ensured that the messages are hidden by default.

With these changes, we created a slot game where the player can only win if three 7 symbols or three identical pirate symbols appear consecutively.
