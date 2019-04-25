In the casino game Blackjack, a player can gain an advantage over the house by keeping track of the relative number of high and low cards remaining in the deck. This is called card counting.

Having more high cards remaining in the deck favors the player. Each card is assigned a value according to the table below. When the count is positive, the player should bet high. When the count is zero or negative, the player should bet low.

Value	Cards
+1	2, 3, 4, 5, 6
0	7, 8, 9
-1	10, ‘J’, ‘Q’, ‘K’,‘A’
You will write a card counting function. It will receive a card parameter and increment or decrement the global count variable according to the card’s value (see table). The function will then return a string with the current count and the string Bet if the count is positive, or Hold if the count is zero or negative. The current count and the player’s decision (Bet or Hold) should be separated by a single space.

Change the code below // Only change code below this line and up to // Only change code above this line
Ensure that you are editing the inside of the cc function.
Use what you’ve learned to check the value of each card parameter passed into the function.
Keep a running count of that number.
If the final count is 1 or greater, return # Hold.
If the final count is 0 or less, return # Bet.
Example Output:

-3 Hold
5 Bet
:speech_balloon: Hint: 1
Use a switch (or else if) statement to count the value of each card.

try to solve the problem now
:speech_balloon: Hint: 2
Add/subtract the value of each card to variable count. If the card is worth 0, don’t do anything.

try to solve the problem now
:speech_balloon: Hint: 3
After you’ve counted the cards, use an if statement to check the value of count. Also, make sure your return has a space between the number and the string.

try to solve the problem now