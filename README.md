# TDD & Pairing Workshop
Galvanize Instructors: Rob Wing & Kay Hudson  

## Instructions
Work as a pair to implement the following stories in a file called com.galvanize.library.MyLibrary.java using TDD.  No code should exist without a test! Switch pairing role after each problem. 

### Pair Programing Tips
* Drivers (How): 
    * Install tools
    * Organize app file structure
    * Check imports/exports
    * Check naming conventions (files, variables, classes, etc)
    * Lint/maintain style and proper syntax
    * Code commenting
    * Tracking duplication for refactoring later
* Navigators (Why):
    * Use documentation to guide
    * Goal tracking and planning
    * Track errors encountered and research them.
    * Prioritize and course correct
    * Keep a checklist of tasks to perform next
    * Create visualizations (whiteboard)
    * Keep track of time

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
  
### Larger Problem (use this repo)
Story: As a programmer, I need an api that will calculate the area of shapes, and the volume of a sphere.
#### Acceptance Criteria:
* Create a new sphere with radius value
* Calculate the volume of a sphere
* Create a new rectangle with the length of a length and width.
* Create a new Square with just one side
* Create a new Circle with just the diameter
* Shape should tell me if it’s a square.  Ie: if two sides are equal.
* Given any shape, calculate the area with a single method call.


