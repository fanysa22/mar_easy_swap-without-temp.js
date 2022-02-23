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

    // Code to swap 'a' and 'b'
    
    // same as a = a + b become 6
        a = (a & b) + (a | b);

    // same as b = a - b become 2
        b = a + (~b) + 1;

    // same as a = a - b become 4
        a = a + (~b) + 1;

    document.write("After swapping: a = " + a + ", b = " + b);
}
 
console.log(result(numbers));
 
mar_easy_swap-without-temp.js
Displaying mar_easy_swap-without-temp.js.
