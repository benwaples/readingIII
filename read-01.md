# Summary Of Engineering Topics

## Quantity Trumps Quality


## Clean Code
* code is really the language in which we ultimately express the requirements.

quote from the writer of `C++` :
> I like my code to be elegant and efficient. The
logic should be straightforward to make it hard
for bugs to hide, the dependencies minimal to
ease maintenance, error handling complete
according to an articulated strategy, and performance close to optimal so as not to tempt
people to make the code messy with unprincipled optimizations. Clean code does one thing
well.

This chapter also talks about how clean code is art. I agree with that. I goes along with the book Linchpin, art comes in many forms.

another really good quote is from Michael Feathers: 

> Clean code always looks like it was written by someone who cares.

I like that

### in conclusion
This chapter is a great preface for the book as a whole. They mention how they will bring up what they think is good code, however just because they say so doesn't mean it is. I do think it is a good starting point though.

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

