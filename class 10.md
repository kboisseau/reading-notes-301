What is a ‘call’?
The call stack is primarily used for function invocation. Since the call stack is single, function execution is done one at a time. It means the call stack is synchronous.
How many ‘calls’ can happen at once?
One at a time.
What does LIFO mean?
It means last In, First Out. meaning that the last function that gets pushed into the stack is the first to be out when the function returns. 
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function(a function that calls itself) without an exit point.




What is a ‘reference error’?
Reference error is a s simple as when you try to use a variable that is not yet declared you get this type of os errors. 
console.log(foo) // Uncaught ReferenceError: foo is not defined
What is a ‘syntax error’?
Syntax error occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an ivalid object using JSON.parse.
What is a ‘range error’?
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
What is a ‘type error’?
 types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
What is a breakpoint?
breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
What does the word ‘debugger’ do in your code?
It helps debug huge cycles for specific values.
