# lurching-towards-dragon
An immensely incomplete Pascal-lite compiler front-end.
Uses lex & yacc (scanner & parser) along with simple syntax tree
and symbol table ("stack" of "hash tables") written in unoptimized C.
Caveat: memory leaks abound.
Source: based on excerpts from Dragon (1ed) book by Aho, Sethi and Ullman.
