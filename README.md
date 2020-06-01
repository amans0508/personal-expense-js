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

add event listener for click - after click pass it to counterIncrement function , options field is false//MDN Docs - **READ ABOUT IT FROM MDN**

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
*parseInt

-> *Console.log({ loggedThing }) -> to see it in the form of Key/Value Pair

//add to total totalexpense = totalexpense+expense;

## Stage Four - Writing to DOM

We don't want output on console, we either want it on top or bottom.

We add it to top using h1 tag and show 0

Flex CSS -> https://css-tricks.com/snippets/css/a-guide-to-flexbox/

flex direction column we gave to put heading element on top of input element

// We need to get heading element 
*querySelector

//We need to set heading element to totalExpense - After initial 0 value
GettingValuefromHeading.textContent = value to set to


//We need to set the heading expense to totalExpense - After adding

*textContent - **READ ABOUT IT FROM MDN**

## Stage Five - Arrays & Objects

Moving Towards creating the application.
We need to learn how to store data using Array and Objects

Need a new text type input element - Description
Get Description element as well

On click read description as well

Improve function remove references out of it and read its *value* 

//Get both Description and Amount

Now we need to store both these values somewhere?
-> JavaScript Object **READ ABOUT IT FROM MDN** *how to read by dot notation and [] notation

We create an expense object
{desc:"" , amount: xxx}

-> JavaScript Array **READ ABOUT IT FROM MDN**
To add in Array -> *arr.push* 

## Stage Six - Processing Data on User Action

We need to have an array outside function having all data, at one place.

*var Vs let Vs const* **READ ABOUT IT FROM MDN**

Once we have the description and the number :
We put in the Object .. key value pair .. .desc and .amount 

push it in array 

//Now we put the Object inside the Array

*console.table* after the push **READ ABOUT IT FROM MDN**
*console.clear*









