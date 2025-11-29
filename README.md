The language compiler implemented using ANTLR4 and Java in 4 phases.
Phase 1:Lexer and Parser. In this phase, all tokens of the language were described in Antlr, which has a regular expression approach, similar to what was mentioned in the course. 
Using these tokens, we developed the grammar of the language. It is an LL(K) parser.
Phase 2:AST and Name Analyzer. In this phase, we modified the grammar file also to generate the AST and populate the tree nodes.
Phase 3:Type Analyzer. This phase was a 2-hour exam. So not many features were implemented.
Phase4:Code Generation. In this phase, the compiler can generate a Java Bytecode.
