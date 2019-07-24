# Assessment1Review


## Closures 

### 1. 

let numb3rs = ["1", "2", "chair", "5", "seventeen", "89"] 

Apple, in an effort to do its part in keeping jobs in America has removed the map function from the library.
Write a simple clone of the map function. It should take as its two parameters: an array of String and a closure of type (String)->Int?, the goal of the closure is to take a string and try to turn it into an Int if possible. The entire function should return an array of optional Int

Call your function with a suitable closure to transform the elements in the constant numb3rs to either an Int or nil as appropriate. eg [1, 2, nil, 5, nil, 89] is the output 

### 2. 

let someNumbers = [21, 5, 42, 8, 29, 16, 3, 34]

write a function that takes an array of Int like above and a closure of type (Int) -> Bool that returns an array of all the numbers of the input less than 10. 

eg. output: [5, 8, 3]

## Dictionaries


### 1
let someCapitals = ["Alabama" : "Montgomery",
"Alaska" : "Juneau",
"Arizona" : "Phoenix",
"Arkansas" : "Little Rock",
"California" : "Sacramento",
"Colorado" : "Denver"]

Use the someCapitals dictionary to write code that prints the capital of Arkansas using best practices.


### 2 

You're in Denver and have forgotten what state you're in. Use the someCapitals dictionary to find and print the state.

## Structs/Classes 
a) Create a class PursuitStaff with the following properties:

name: String
id: Int
favoriteColor: String

b) Make an instance of PursuitStaff from each line of data below (4 total), and put them in an array named allPursuitStaff.

David, 3217, green

Istishna, 3236, purple 

Olimpia, 3214, blue

Iram, 3222, red


c) Use higher order functions to create a new array named nameSortedStaff of allPursuitStaff sorted by name

d) Use higher order functions to create a new array named idSortedStaff sorted by id

e) Iterate through allPursuitStaff and change everyone's favorite color to green
