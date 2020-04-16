This folder contains code  from the "Getting Started" portion of the UDEMY Course (in the repository description).

The purpose of the files in this folder is to give motivation for why TypeScript can be more useful than vanilla Javascript. 

In only-js.js, we are given a scenario where the code is getting values from an HTML document and passing them into an addition function. The problem is that, for a var object, object.value will always return a string, and Javascript will concatinate two strings, rather than performing arithematic operations on the numerical value of the string.

This can be avoided using TS, which will throw errors when it notices this type of ambiguity or logical errors. using-ts.ts is the TypeScript file, which is compiled using the tsc command on the Windows Command Prompt to produve the using-ts.js Javascript file. 

Comparing the two files, you can see the optimizations the TypeScript compiler made in order to get a working Javascript file, which can then be used in the browser. 

