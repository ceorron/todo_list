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
    - call print with "string!" parameter (check)                      - fail (do import call)
    - do loop within print function (check)                            - good
    - do pointer operations =, ++, *, ==, != (check)                   - good
    - do const_static_list operations "begin", "end" (check)           - good
    - call function from import "fn_putchar(int)" (check)              - fail
    - do return of int, do return of void (finish function) (check)    - good
    - do resolve/generate functions calls correctly (check)            - fail

    - do types, including construct/destruct                           - fail

    - do create allocator                                              - fail
    - do destroy allocator                                             - fail
    - do create module global + destroy module global                  - fail
    - do create module local + destroy module global                   - fail

    - get_stack_top() + other inbuilt functions                        - fail
    - allocator_for<:T:>                                               - fail (the compiler)
    - is_trivially_destruct<:T:>()                                     - fail
    - is_trivially_copy_construct<:T:>()                               - fail
    - is_trivially_move_construct<:T:>()                               - fail
    - is_trivially_construct<:T:>()                                    - fail

    - do module generation                                             - fail
    - do code generation                                               - fail

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
