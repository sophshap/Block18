<!-- Unit Tests:
A function called "multiplication" that returns the product of the two input numbers.

Expect multiplication(2, 3) to be a number
Expect multiplication(2, 3) to be equal to 6
Expect multiplication("a", 3) to be an error




A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

Expect concatOddsconcatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be two arrays of numbers
Expect concatOddsconcatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be only odds in ascending order with no repeats
Expect concatOddsconcatOdds(["a", 2, 1], ["b", 1, 1, 1, 4, 15, -1]) to be an error








Functional Tests:
A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.


When a user clicks checkout they should be asked to login or checkout as guest
When a user checks out as guest they should be asked if they want to create an account
When a user's cart is empty, they should not have a checkout option
When a user clicks check out they should be given a list of the items in their cart with prices
When a user reviews their cart they should be able to continue to payment
When a user continues after reviewing their cart, they should be prompted to enter credit card and contact info
When a user submits their payment/contact info, they should get a confirmation that their order went through


-->
