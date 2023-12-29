# source-code-transpiler
Transpile or translate source code between different programming languages.  
***Not yet complete.***

## Long description/plan
The following text may not represent the future state of the project (perfectly). Think of it as ideas.

Transpile or translate source code between different programming languages. It does so by  
1. breaking down the source code into bits and pieces (let's call these "words") and of course tries to understand the relationships between these "words"  
2. then it tries to find the closest matches for these bits and pieces and some similar (or the same, if possible) syntax (or something else that should achieve a similar or the same result). (Not every programming language can be easily transpiled. If you want a real language example, think about languages from different language families, like English-Japanese.)
How close the approximation is between languages can be set in the transpiler. (A more "literal" translation may produce worse code in the other language, but more similar results as well.)
