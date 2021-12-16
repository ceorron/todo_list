# todo list for ceorron projects

High level project plan (compiler)
 - aether compiler                                         [ ]
 - aether standard library                                 [ ]
 - aether compiler                                         [ ]
 - aether code port                                        [ ]
 - hot swapping aether code                                [ ]

Low level project plan, this week todos
 - refine lexer/parser                                     [ ]
   - do system functions                                   [ ]
   - do module/module function lookup                      [ ]
   - do import function code generation                    [ ]

# Top Level Plan - Project plan

- compiler/virtual machine (all implementable features, X86-64 only) [here]
- remake all of the libraries (everything except dionysus and opengui)
- make new streaming libraries (other new libraries/improvements)
- make opengui (concurrent with below)
  - make each of the gui editors (keep adding)
    - aether text editor
    - make dionysus (concurrent with below)
      - IDE (complete text editor to have other features)
      - game engine editor
      - 3D modelling editor
      - 2D modelling editor
      - 3D animation editor
      - 2D animation editor
      - terrain generator editor
      - automation tools editor
      - image editor
      - sound editor
      - video editor
      - font editor
      - business tools
      - math tools
    - flow chart programming (FSM)
    - flow chart programming (flow diagram)
    - 3D design editor
    - 2D design editor
    - video editor
    - music editor
    - sound effect editor
    - math tools editor
    - AI library (rule based programming)
      - AI assistant
      - AI designer
      - AI driver
      - AI oracle
      - AI task library
- do self hosting compiler/virtual machine (aether compiles itself)
  - compile to other targets (arm, gpu, wasm, etc.) 
- hot swappable code (plugins)
- other compiler improvements
- remove c++ code base (move everything else across)
- download code/release code/online shop facilities


Do everything to get the hello world example working first
(KEY: X is complete, O is partial, empty is not started yet)

resolve + generate:

- variable []
- namelist []
- constructcall []
- listconstructcall []
- constant []
- result_ []
- try []
- foreach []
- forbaseeach []
- withblock []
- labelblock []
- lambdafunc []
- cast []
- dotmem []
- memaccess []
- baseaccess []
- constructcall []
- funccall []
- index []
- preops []
- postops []
- atom []
- logand []
- logor []
- refequal []
- ternary []
- yld []
- thrw []
- goto []
- compilerdirective []
- basiclabel []

