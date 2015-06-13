#Description

Extension to: http://www.cs.columbia.edu/~zeph/software/JavaCFG/
which adds a CFG for simple C# assignment expressions.

#Usage

##Validate expression
*java CFGParse grammars/{grammar_file}.cfg '{expression}'*

##Draw expression tree
Validating expression generates a .tex file which then can be drawn as a tree by pdflatex command:

*pdflatex {expression}.tex*

