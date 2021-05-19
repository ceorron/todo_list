# todo list for ceorron projects

High level project plan
 - c++ compiler                                            [ ]
 - aether standard library                                 [ ]
 - aether compiler                                         [ ]
 - aether code port                                        [ ]
 - hot swapping aether code                                [ ]

Low level project plan, this week todos
 - make lexer/parser                                       [ ]
 - do ir code converter                                    [ ]
   - do system functions                                   [ ]
   - do module/module function lookup                      [ ]
   - do import function code generation                    [ ]
 - do initial end to end code generation testing           [ ]

Add progress TODO list
 - tick off as we go - after this print should work
 - test get function calls/generation working              []
    - make resolve match generate
    - For both resolve & generate
    - make "string!" constant
    - call print with "string!" parameter
    - do loop within print function
    - do pointer operations =, ++, *, ==, !=
    - do const_static_list operations "begin", "end"
    - call function from import "fn_putchar(int)"
    - do return of int, do return of void (finish function)

    - do create allocator
    - do destroy allocator
    - do create module global + destroy module global
    - do create module local + destroy module global
 
 - test get modules/import working				                     []
 - test get ir code generation working			                  []
 - test get internal code generation working	              []
 - test start adding features					                         []
- get value/get reference for structure (get reference to value)
- stack_top function
- tomorrow resolve all call/operators
- windows LoadLibrary/GetProcAddress
- [ later ]
- resolve globals before main function
- does log and/log or need push_frame/pop_frame?
- load system_functions (like main function)
- variable + destructor
- function casts / function/operator call determination
- add const/volatile correctness
- global/local correctness
- get constants as values
- finish of templates
