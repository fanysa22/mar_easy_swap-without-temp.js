# mar_easy_swap-without-temp.js
Javascript test

/**
 * Direction:
 * Swap these numbers without using temporary variable
 *
 * Expected Result:
 * {
 *  a: 4,
 *  b: 2
 * }
 */
 
let numbers = {
  a: 2,
  b: 4
 };

function result(numbers) {

[numbers['a'], numbers['b']] = [numbers['b'], numbers['a']];

}
 
console.log(result(numbers));
console.log(numbers);
 
mar_easy_swap-without-temp.js
Displaying mar_easy_swap-without-temp.js.
