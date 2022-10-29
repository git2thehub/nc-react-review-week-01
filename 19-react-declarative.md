# React is declarative
DOM manipulation is performed under the hood by the React library
you don't manipulate the DOM by yourself when you use React, it gets transpiled for you
you tell react what you want (you declare what you want --- hence declarative) and react does all the heavy lifting to give you the end result of what you want)
React creates a Virtual DOM based on your code
React uses a process called "reconciliation to diff" (compares the differences) the matches the actual DOM with the virtual DOM
React does this very efficiently and only updates what changes (not everything)
That is why we need a virtual dom