# Understanding the JavaScript Call Stack

1. What is a ‘call’?
```
At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
Source: https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/
```

2. How many ‘calls’ can happen at once?
Only one

3. What does LIFO mean?
Last In First Out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
```
Top   ----------------------------------------  Bottom
      | f(1) | f(2) | ... | ... | ... | f(6) |
      ----------------------------------------
```

5. What causes a Stack Overflow?
A stack overflow is caused when a recursive function calls itself repeatedly with no exit point.

# JavaScript error messages

1. What is a ‘refrence error’?
A reference error is when you try to use a variable that isn't declared.

2. What is a ‘syntax error’?
This occurs when the compiler is unable to parse something.

3. What is a ‘range error’?
A range error occurs if you try to manipulate an object with a length and give it an invalid length.

4. What is a ‘type error’?
This type of error shows up when the types of data you are trying to access are incompatible.

5. What is a breakpoint?
A breakpoint is a way to stop processing code, usually for debugging.

6. What does the word ‘debugger’ do in your code?
The word debugger creates a breakpoint in your code for debugging purposes.