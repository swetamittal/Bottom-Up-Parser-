# Bottom-Up-Parser

Bottom-up parsing can be defined as an attempt to reduce the input string w to the start symbol of grammar by tracing out the rightmost derivations of w in reverse. Bottom-up parsing starts from the leaf nodes of a tree and works in upward direction till it reaches the root node. Here, we start from a sentence and then apply production rules in reverse manner in order to reach the start symbol.

I have designed a Shift-Reduce parser in python which is a type of bottom up parser. As the parser performs both the shift and reduce operations by examining the input tokens and either performing shift operation on the stack or reducing the element at the top of stack, replacing the right hand side by the left hand side.
