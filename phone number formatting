// Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

// Example:
// createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"
// The returned format must be correct in order to complete this challenge.
// Don't forget the space after the closing parentheses!
function createPhoneNumber(numbers){
  var format = "(xxx) xxx-xxxx";  //creates our format needed
  
  for(var i = 0; i < numbers.length; i++)  //iterates through our numbers
  {
    format = format.replace('x', numbers[i]);  //format replaces char X for each character iteration
  }
  console.log(format);   
  return format;
  
}

createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]);
