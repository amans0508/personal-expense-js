# personal-expense-js
 personal-expense-js


## Stage one
created index.html - personal expense app
Create an Add button (+), see weather you're able to listen to its event on clicking.
button in center - by Flex , justify-content , align items , height: 100vh
Add number everytime button clicked 

get the button element - document and query selector - store in const 
listen to click event 
lTake a number which starts from 0 - store in let
increment the number on every click

## Stage Two - Event Listener

listen to click event using ID 

add event listener for click - after click pass it to counterIncrement function , options field is false//MDN Docs

//function to increment a number
counterIncrement -> This will do counter and increment

**Make sure not to put () after function call in event listener

Add an input element type text

## Stage Three - Reading from Input

input element has an ID now

counter element is not needed as we're adding from button now , so button id needed for query selection
// init value of expense at 0
-> totalExpense

//onbuttonclick add input amount to totalexpense
-> function addExpenseToTotal

//we need to read value from input amount
-> We use query selector to get button
-> get value() from button


//convert input to number from text

//add to total totalexpense



