# clean-code
My viewepoint on clean code architecture

- Functions should be small, descriptive
- All lines in functions should be at same abstract level
- If / else should be broken into seperate functions
- 3 / 4 lines of code can be seperated/refactored into functions
  with giving those functions an descriptive name and adding JSDoc
- Refactored functions should be doing one thing or grouping similar things together.

- Summary: Functions should be small.
- How To: extract, extract, extract and extract and extract, until you can`t
- Strategy: First, make it work, then make it clean.

<!-- Command and Query Seperation -->
sideEffect: change some state
Functon that return nothing, must have some side-effect
So, if a function returns something, should not have side-effect


<!-- Unit tests -->
Tests are integral part of system itself.
If changing a helper file breaks a function, that is bad design.
So, think of test as integral part of system, so if changing a line in function
breaks your test ( Fragile tests ), you should design better tests.
If changing some line in tests, break your functions, you should write
better fucntions and better design.
Think of tests first and then functions, then again tests, then again the functions.
Keep this loop manageable (avoid very small or very large loops)

