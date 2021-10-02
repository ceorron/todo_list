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
 - tick off as we go
 - test get function calls/generation working              []
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
# later
- release for a monthly fee


Do everything to get the hello world example working first
(KEY: X is complete, O is partial, empty is not started yet)

resolve:

variable []
namelist []
bracketexpression []
constructcall []
listconstructcall []
constant []
result_ []
if []
switch []
try []
foreach []
forbaseeach []
for []
while []
dowhen []
scopeblock []
withblock []
labelblock []
szeof []
lambdafunc []
pre_minusminus []
pre_plusplus []
pre_plus []
pre_minus []
pre_not []
pre_compl []
pre_address []
pre_question []
pre_dref []
cast []
post_minusminus []
post_plusplus []
dotmem []
memaccess []
baseaccess []
constructcall []
funccall []
index []
preops []
postops []
atom []
multi []
div []
mod []
op11g []
add []
sub []
lshft []
rshft []
and []
xor []
or []
less_equal []
less []
greater_equal []
greater []
equals []
not_equals []
equal []
refequal []
add_equal []
sub_equal []
multi_equal []
div_equal []
mod_equal []
lshft_equal []
rshft_equal []
and_equal []
xor_equal []
or_equal []
op1g []
ternary []
expr []
rtn []
yld []
thrw []
valexpression []
loopctlr []
goto []
compilerdirective []
basiclabel []
expression []
block []
funcdef []

generate:

variable []
namelist []
bracketexpression []
constructcall []
listconstructcall []
constant []
result_ []
if []
switch []
try []
foreach []
forbaseeach []
for []
while []
dowhen []
scopeblock []
withblock []
labelblock []
szeof []
lambdafunc []
pre_minusminus []
pre_plusplus []
pre_plus []
pre_minus []
pre_not []
pre_compl []
pre_address []
pre_question []
pre_dref []
cast []
post_minusminus []
post_plusplus []
dotmem []
memaccess []
baseaccess []
constructcall []
funccall []
index []
preops []
postops []
atom []
multi []
div []
mod []
op11g []
add []
sub []
lshft []
rshft []
and []
xor []
or []
less_equal []
less []
greater_equal []
greater []
equals []
not_equals []
equal []
refequal []
add_equal []
sub_equal []
multi_equal []
div_equal []
mod_equal []
lshft_equal []
rshft_equal []
and_equal []
xor_equal []
or_equal []
op1g []
ternary []
expr []
rtn []
yld []
thrw []
valexpression []
loopctlr []
goto []
compilerdirective []
basiclabel []
expression []
block []
funcdef []



