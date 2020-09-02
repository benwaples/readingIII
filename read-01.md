# Summary Of Engineering Topics

## Quantity Trumps Quality


## Clean Code


## Red, Green, Refactor
* Red — think about what you want to develop
* Green — think about how to make your tests pass
* Refactor — think about how to improve your existing implementation

### Red
write a test that will only pass once its requirements are met perfectly!
### Green
focusing on getting the test to pass in anyway possible. Once it is passing, you know what the test needs to do and can begin refactoring.
### Refactor
refactor your code with the focus of it being either more concise, or more descriptive. Whichever way you decide you can most likely reduce unnecessary code.

## Cycles of TDD

### 3 laws of TDD
* You must write a failing test before you write any production code.
* You must not write more of a test than is sufficient to fail, or fail to compile.
* You must not write more production code than is sufficient to make the currently failing test pass.

### Read, Green, Refactor
* write a test that fails
* now write production code that makes that test pass
* now clean up the production code you just wrote

### Specific/ Generic
* Programmers make specific cases work by writing code that makes the general case work.

### Boundaries
* start working on where your test are vulnerable and figure out ways to make them better.

