# Summary for Class 02 Reading 

## Clean Code Ch.2 
Reading this chapter on naming is really helpful, mostly because now I can come up with names quicker instead of thinking about what is important with naming my function/ variables/ classes.

1. distinguish names - `accountInfo` is just `account`, so make sure that if you name something be specific so its distinguishable.
1. Use pronounceable names - I feel like this is obvious but I don't do it all the time. I too say things how they are written (sort of as a joke and can get me in trouble), so making things pronounceable shouldn't be too hard.
1. Searchable names - if I am looking for an array of dogs, name is dogs and not animals
1. Avoid Mental mapping - instead of calling a variable x, call it dog.
1. classes and objects should be nouns or have nouns in them.
1. likewise, methods should be verbs or have a verb in the name.
1. don't make jokes as names, it can separate the reader from the writer if the reader doesn't get it.
1. stick to one word per concept and be consistent. For example, dont say fetch, get, and retrieve all in the same file.
1. names things in accordance to the problem and solution domain.
1. Don't be afraid to rename things. Just do rename if it can be better.

## [Array Methods](https://dev.to/frugencefidel/10-javascript-array-methods-you-should-know-4lk3)

``` js
arr.forEach()
```
* goes through each position in an array and executed a given code

``` js
arr.includes()
```
* returns `true` if an array contains the parameter given to includes

``` js
arr.filter()
```
* creates a new array containing all values that return true based on the filters conditional call back.

``` js
arr.map()
```
* returns a new array that has modified each position of the given array.

``` js
arr.reduce()
```
* applies a function to each element inside an array and adds it to the accumulator, reducing to a single value.

``` js
arr.some()
```
* checks to see if at least on item is truthy based on a conditional, if so it return true.

``` js
arr.sort()
```
* sorts an array by either ascending or descending order


## [Array Methods Cheat Sheet](https://jrsinclair.com/javascript-array-methods-cheat-sheet)
This website is really funny! I really like this one cause it starts with the problems that you may have and then help you work through which arr method would be best.

## [Class Syntax](https://javascript.info/class)
``` js
class Zombie {
  constructor(name) {
  this.name = name
  }
  method(){
    //function to be run when method is called
  }
}
```


## [MDN Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
classes behave like functions. It creates a default object with preset key value pairs. Each key value can be changed manually when being initialized. They also come with built in methods that you can call on the object!

## [MVC Architecture](https://www.tutorialspoint.com/mvc_framework/mvc_framework_introduction.htm#:~:text=The%20Model%2DView%2DController%20(,development%20aspects%20of%20an%20application.){:target=%E2%80%9D_blank%E2%80%9D%20rel=%E2%80%9Dnoopener)
model, view, controller
* Model - think data model. Everything that we are keeping track of for the user and how we store that data.
* View - the UI of the project.
* Controller - how the user manipulates the model through the view

MVC projects are highly scalable because it is easy to manipulate the state. It is also easily tested and utilizes a component based structure!

ASP.NET MVC sounds a lot like react apps.

## [MVC Video](https://www.youtube.com/watch?v=DUg2SWWK18I&ab_channel=WebDevSimplified)
That was a nice visualization of how the MVC works. M only interacts with the controller, and the view only interacts with the controller. That way the model and view are simple and the controller is the acting as a data proxy.