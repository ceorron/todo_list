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
    - call print with "string!" parameter (check)                      - fail (do import call) (7)
    - do loop within print function (check)                            - good (0)
    - do pointer operations =, ++, *, ==, != (check)                   - good (0)
    - do const_static_list operations "begin", "end" (check)           - good (0)
    - call function from import "fn_putchar(int)" (check)              - fail (8)
    - do return of int, do return of void (finish function) (check)    - fail (15)
    - do resolve/generate functions calls correctly (check)            - fail (9)

    - do types, including construct/destruct                           - fail (6)

    - do create allocator                                              - fail (10)
    - do destroy allocator                                             - fail (11)
    - do create module global + destroy module global                  - fail (12)
    - do create module local + destroy module global                   - fail (13)

    - get_stack_top() + other inbuilt functions                        - fail (14)
    - allocator_for<:T:>                                               - fail (the compiler) (5)
    - is_trivially_destruct<:T:>()                                     - fail (1)
    - is_trivially_copy_construct<:T:>()                               - fail (2)
    - is_trivially_move_construct<:T:>()                               - fail (3)
    - is_trivially_construct<:T:>()                                    - fail (4)

    - do module generation                                             - fail (16)
    - do code generation                                               - fail (17)

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


# Top Level Plan - Project plan

- compiler/virtual machine (all implementable features)
- remake all of the libraries (everyone except dionysus and opengui)
- make new streaming libraries (other new libraries/improvements)
- make opengui (concurrent with below)
  - make each of the gui editors (keep adding)
    - aether text editor
    - game engine editor
    - 3D modelling
    - 2D modelling
    - 3D design
    - 2D design
    - 3D animation
    - 2D animation
    - video editor
    - music editor
    - sound effect editor
    - terrain generator
    - automation tools
    - math tools
    - AI library (rule based programming)
- do self hosting compiler/virtual machine (aether compiles itself)
- hot swappable code (plugins)
- other compiler improvements
- remove c++ code base (move everything else across)
