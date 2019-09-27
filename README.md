# TDD & Pairing Workshop
Galvanize Instructors: Rob Wing & Kay Hudson  

## Instructions
Work as a pair to implement the following stories in a file called com.galvanize.library.MyLibrary.java using TDD.  No code should exist without a test! Switch pairing role after each problem. 

### Pairing Roles
* Navigator
  * Keeps big picture in mind
  * Knows where you are going
  * Gives high or mid-level instructions to the driver
  * NOT describing syntax

* Driver
  * Writes the code
  * proving/disproving theories by testing (breakpoints, logging, manual)
  * Asking questions

## Stories
### Strings
* A method that will reverse the characters of a string
  * Given: "ABC 1234 DEFGH" 
  * Returns: "HGFED 4321 CBA"
* A method that will convert a string to all caps
  * Given: "abCd eFgh IJKLMNO"
  * Returns: "ABCD EFGH IJKLMNO"
* A method that will convert a string to all lower case
  * Given: "abCD efG h IJKlmno"
  * Returns:  "abcd efg h ijklmno"
  
* A method that will reverse a string but keep the spaces in the same position
  * Given: "The quick brown fox jumps over the lazy dog"
  * Returns:  "god yzale threv osp mujxo fnwo rbk ciuq ehT"
  
* A method that will reverse the words of a string
  * Given: "The quick brown fox jumps over the lazy dog"
  * Returns: “dog lazy the over jumps fox brown quick the”

* A method that will break a string into an array of individual strings
  * Given: "The quick brown fox jumps over the lazy dog"
  * Returns `{ "The", "quick", "brown", "fox", "jumps", "over", "the", "lazy", "dog" }`
  
### Math
* A method that will return the square root of a given number to two decimals of percision
  * Given 9, returns 3
  * Given 13, returns 3.46
* A method to convert celcius to farenheit `(0°C × 9/5) + 32 = 32°F` to two digits of percision
* A method to convert farenheit to celcius `(100°F − 32) × 5/9 = 37.778°C` to two digits of percision
* A method to convert decimal to english string (round to 1/16)
  * Given 2.25 Returns  "2 1/4"
  * Give 5.75835

