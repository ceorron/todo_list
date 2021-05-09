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
- tomorrow casts
- cast/conversion
- alignment_of<:T:> other inbuilt functions
- construct call
- ternary
- ccall/stdcall/aethcall
- return
- tomorrow resolve all call/operators
- lambda function
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
