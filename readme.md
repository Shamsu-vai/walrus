# Walrus Programming language
A tiny simple programming language made for simplicity. It borrows syntax from 'go', 'rust' and 'typescript'

- [x] Lexer
- [x] Parser
    - [x] Variable declare
    - [x] Variable assign
    - [x] Expressions
        - [x] Unary (int, float, bool) `- !`
        - [x] Additive `+ -`
        - [x] Multiplicative `* / % ^`
        - [x] Grouping `( )`
    - [x] Array
        - [x] Array indexing
    - [x] User defined types
        - [x] Struct
            - [x] Property access
            - [x] Property assignment
            - [x] Private property deny access
        - [x] Builtins
    - [x] Conditionals
        - [x] if
        - [x] else
        - [x] else if
    - [x] Functions
        - [x] Function declaration
        - [x] Function call
        - [x] Function return
        - [x] Optional parameters
    - [x] Closure
    - [x] User defined types
        - [x] Struct
            - [x] Property access
            - [x] Property assignment
            - [x] Private property deny access
        - [x] Builtins (int, float, bool, string)
        - [x] Function
    - [x] Increment/Decrement
        - [x] Prefix
        - [x] Postfix
    - [x] Assignment operators
        - [x] +=
        - [x] -=
        - [x] *=
        - [x] /=
        - [x] %=
    - [ ] For loop
        - [x] for [condition]
        - [ ] for [start] [condition] [end]
        - [ ] for [start] in [range] 
    - [x] Struct embedding
    - [x] Traits
    - [x] Implement
    - [ ] Generics
- [x] Analyzer
    - [x] Everything in parser except - 
        - [ ] For loop
        - [ ] Traits
        - [ ] Implement
- [ ] Codegen