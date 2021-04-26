
## Part 1a

**part1a-question1:**

values added:  20

**part1a-question2:**

final result:  20

**part1a-question3:**

values added:  20

**part1a-question4:**

error, because If we used let instead of var, then the variable would only be visible inside if.


**part1a-question5:**

error, because we are trying to do assignment to constant variable "result".

**part1a-question6:**

error, because we are trying to do assignment to constant variable "result".

## Part 1b

**part1b-question1:**

It would print: 3. Because console.log function will print the thing inside and in this case i is 3 after for 
loop iterating 3 times.

**part1b-question2:**

It would print: 150. Because console.log function will print the thing inside and in this case the variable inside 
which is discountedPrice is computed as "prices[2]*(1-0.5) = 300*0.5 = 150" at the end of for loop.

**part1b-question3:**

It would print: 150. Because console.log function will print the thing inside and in this case the variable inside 
which is finalPrice is computed as "Math.round(discountedprice*100)/100 = 150*100/100 = 150" at the end of for loop.

**part1b-question4:**

It would return an array whih is "[ 50, 100, 150 ]", because the variable we return is discounted and we created it as an
empty array at the beginning and after each iteration of the for loop, we first do some calculation based on 
input array and some other variable append an calculated element in to this array. Finally, we return this array with 3 elements.

**part1b-question5:**

error, because if we used let instead of var, then the variable i would only be visible inside for loop.

**part1b-question6:**

error, because if we used let instead of var, then the variable discountedPrice would only be visible inside for loop.

**part1b-question7:**

It would print: 150. Because here variable finalPrice is vbisible inside the whole function, console.log function will print the thing inside and in this case the variable inside which is finalPrice is computed as "Math.round(discountedprice*100)/100 = 150*100/100 = 150" at the end of for loop.

**part1b-question8:**

It would return an array whih is "[ 50, 100, 150 ]", because here variable discounted is vbisible inside the whole function(visible when we return it), the variable we return is discounted and we created it as an empty array at the beginning and after each iteration of the for loop, we first do some calculation based on input array and some other variable append an calculated element in to this array. Finally, we return this array with 3 elements.

**part1b-question9:**

error, because if we used let instead of var, then the variable i would only be visible inside for loop.

**part1b-question10:**

It would print: 3. Because console.log function will print the thing inside and in this case length is 3 after we assign prices.length which is 3 to it.

**part1b-question11:**

It would return an array whih is "[ 50, 100, 150 ]", because the values inside the const array can be change, it can add new items to const arrays, the variable we return is discounted and we created it as an empty array at the beginning and after each iteration of the for loop, we first do some calculation based on input array and some other variable append an calculated element in to this array. Finally, we return this array with 3 elements.

**part1b-question12-A:**

student.name;

**part1b-question12-B:**

student["Grad Year"];

**part1b-question12-C:**

student.greeting();

**part1b-question12-D:**

student["Favorite Teacher"].name;

**part1b-question12-E:**

student.courseLoad[0];

**part1b-question13-A:**

Output is string: '32', since integer 2 map to its exact string representation which is '2'.

**part1b-question13-B:**

Output is integer: 1, since string '3' map to its exact integer representation which is 3.

**part1b-question13-C:**

Output is integer: 3, since null map to its exact integer representation which is 0.

**part1b-question13-D:**

Output is string: '3null', since null map to its exact string representation which is 'null'.

**part1b-question13-E:**

Output is integer: 4, since true maps to 1.

**part1b-question13-F:**

Output is integer: 0, since false maps to 0 and null also maps to 0.

**part1b-question13-G:**

Output is string: '3undefined', since undefined map to its exact string representation which is 'undefined'.

**part1b-question13-H:**

Output is NaN, since it's not valid operation.

**part1b-question14-A:**

Output is true, since '2' maps to integer 2.

**part1b-question14-B:**

Output is false, since When comparing two strings, "2" will be greater than "12", because (alphabetically) 1 is less than 2.

**part1b-question14-C:**

Output is true, since '2' maps to integer 2.

**part1b-question14-D:**

Output is false, since the strict equality operator "===" always considers operands of different types to be different and 2 is integer but '2' is string.

**part1b-question14-E:**

Output is false, since true maps to integer 1.

**part1b-question14-F:**

Output is true, since true maps to integer 1 and Boolean(2) function returns 1.

**part1b-question15:**

When using triple equals "===" in JavaScript, we are testing for strict equality. This means both the type and the value we are comparing have to be the same. However, When using double equals "==" in JavaScript we are testing for loose equality. Double equals also performs type coercion. Type coercion means that two values are compared only after attempting to convert them into a common type.

**part1b-question16:**

part1b-question16.js

**part1b-question17:**

It would return an array which is "[ 2, 4, 6 ]". At the beginning of modifyArray function, we create an empty array called newArr. Then we use an for loop iterate for 3 time which is the length of input "array". At each iteration, we push one element which is calculated by callback(array[i]) in to newArr. The callback function would a double of its input parameter, therefore, our return array just double the value of our original input array "[1,2,3]".

**part1b-question18:**

part1b-question18.js

**part1b-question19:**

1
4
3
2












