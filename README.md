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