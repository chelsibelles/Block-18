Unit Tests:
  1. A function called "multiplication" that returns the product of the two input numbers.
      - Identify two input numbers
      - Multiply two input numbers together
      - Function should return the product of the two numbers
      - The product should be a number
      - Should work with negative numbers
      - Will return an error or undefined if an array of strings is passed instead of numbers
      - We would expect multiply([2,3]) to return the number 6
  2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
      - Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) --> should result in [-1, 1, 3, 9, 15]
      - If you receive an unexpected input, such as a negative number, if it is odd it should be included in the output array
      - If you receive multiple inputs of the same number, the number 1 in this case, it should only be included once in the output array
      - Expect two arrays with even numbers to result in an undefined result

Functional Tests:
  1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
     - If the cart is empty, expect the checkout button to not function or return error
     - User should have an option to log in or create account or to proceed as a guest
     - User should be able to see what is in their cart
     - User should have an option for either pick-up or delivery
         - If delivery option is chosen, delivery cost choices should be presented i.e. express delivery or standard delivery 
     - There should be text boxes to input shipping and billing information
     - Checkout should display all accepted forms of payment
