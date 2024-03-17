# todo list for ceorron projects

High level project plan (compiler)
 - aether compiler                                         [o]
 - aether standard library                                 [ ]
 - aether code port                                        [ ]
 - aether compiler v 2.0                                   [ ]
 - hot swapping aether code                                [ ]

# TODO on the compiler

 - return value optimisation (RVO)                         [x]
 - with block + testing                                    [x]
 - lambda + testing                                        [o]
 - local vector<::> + testing                              [o]
 - global vector<::> + testing                             [ ]
 - coroutines/yield + testing                              [x]
 - try/catch/default/throw + testing                       [x]
 - goto/label blocks + testing                             [o]
 - local/global modules                                    [ ]
 - constant propagation                                    [o] - here

 - basic_shared_pointer									                              [x]  #0

 - heavy_code_review										                                []	#1
 - fptrs, lambda fptrs, coroutine						                     [x]  #1.2
 - auto/typeof on types								                            	[x]  #1.3
 - rvo, tvo, yvo on return, throw or yeild			              	[x]  #1.4
 - operator()/{}/[] like function call					                 []  #1.5
 - types												                                       	[x]  #1.6
 - code review st_variable						                          		[x]  #1.6.1
 - array begin/end test							                            		[x]  #1.7
 - function_data needs to be present						                  []  #1.8 ???
 - struct virtual functions							                         	[x]  #1.10

 - constants												                                    [o]	#2 - here
 - structure initialisation							                          []

 - line numbers + errors							                           		[]  #1.11
 - full code review										                               []  #1.12 - just complete everything (go through all of the features again, fix up missing parts)

 - variable init											                                 []  #1.13
 - crashing bug											                                  []  #1.14 ???
 - ternary needs to handle destruction correctly			         []  #1.15
 - template spec tests 									                            []  #1.16
 - generated functions (reference first parameter)		        []  #1.9

 - types													                                         []	#3
 - initialisation											                                  []	#4
 - globals												                                       	[]	#5
 - low level concerns										                               []  #6 - select, reverse stack, with-call on destructors, fptrs/lmbdaptrs takes pointer to structure
 - first parameter is a reference then pass by reference	     [o]  #7
 - this/self destructor									                              []  #8
 - line numbers											                                    []  #9
 - error(s) messages										                                []  #10
 - incomplete operators									                              []  #11
 - missing inbuilt functions								                          []  #12
 - foreach break continue, foreach begin/end				              []  #13
 - stack needs to grow in the correct direction		         	   []  #14

 - include_					     []
 - link_						       []
 - import_						     []
 - as_ 						        []
 - friend_ 				     	[]
 - namespace_ 					  []
 - using_ 						     []
 - direct_ 				     	[]
 - true_ 						      []
 - false_ 						     []
 - result_ 					     []
 - self_	 					      []
 - if_ 						        []
 - else_ 						      []
 - switch_ 					     []
 - case_ 						      []
 - default_ 					    []
 - try_ 						       []
 - catch_ 						     []
 - for_ 						       []
 - for_base_ 					   []
 - in_ 						        []
 - while_ 						     []
 - do_ 						        []
 - when_ 						      []
 - with_ 						      []
 - label_ 						     []
 - break_						      []
 - continue_					    []
 - goto_ 						      []
 - return_ 					     []
 - yield_						      []
 - yield_return_				 []
 - throw_ 						     []
 - mutable_					     []
 - immutable_					   []
 - extern_						     []
 - link_extern_				  []
 - inline_						     []
 - def_ 						       []
 - alias_ 						     []
 - proxy_ 						     []
 - operator_ 					   []
 - final_						      []
 - delete_						     []
 - explicit_					    []
 - virtual_ 					    []
 - system_function_ 	[]
 - class_						      []
 - struct_						     []
 - enum_ 						      []
 - build_type_ 	     []
 - sizeof_ 					     []
 - typeof_ 					     []
 - spec_						       []
 - expr_ 						      []
 - except_						     []
 - defer_						      []
 - global_						     []
 - local_						      []
 - static_						     []
 - host_						       []
 - const_						      []
 - volatile_				     []
 - hidden_						     []
 - no_alias_				     []
 - capture_					     []
 - init_set_				     []
 - no_init_					     []
 - auto_						       []
 - this_						       []
 - void_						       []
 - signed_						     []
 - unsigned_				     []
 - bool_						       []
 - char_						       []
 - short_						      []
 - int_						        []
 - long_						       []
 - float_						      []
 - double_						     []
 - int8_						       []
 - int16_						      []
 - int32_						      []
 - int64_						      []
 - int128_						     []
 - uint8_						      []
 - uint16_						     []
 - uint32_						     []
 - uint64_						     []
 - uint128_					     []
 - float32_					     []
 - float64_					     []

 - yield_no_lex				   []
 - except_no_lex				  []
 - mutable_no_lex				 []
 - global_no_lex				  []
 - local_no_lex				   []
 - host_no_lex					   []
 - const_no_lex				   []
 - volatile_no_lex				[]
 - no_alias_no_lex				[]

 - mem_loc						   []
 - mem_loc_no_lex		[]

 - identifier					 [x]
 - name						      [x]

<> NOTE these end as soon as we find a value that isn't a valid hex number
 - HEX_VALUE 					    [x]
 - UNICODE_UTF32_CHAR	[x]
 - UNICODE_UTF16_CHAR [x]
 - HEX_CHAR 					     [x]
 - BIT_CHAR 					     [x]

<> constants
 - STRING						       [x]

 - HEX_DIGIT 					    [x]
 - DEC_DIGIT 					    [x]
 - NO_DEC_DIGIT_1 				[x]
 - NO_DEC_DIGIT_2 				[x]
 - BIT_DIGIT 				    	[x]

<> integer constants
 - INT_CONSTANT_HEX			[x]
 - INT_CONSTANT_BIN			[]
 - INT_CONSTANT_DEC			[x]
 - CHAR_CONSTANT				  [x]

 - INT_CONSTANT				   [o]

<> float constants
<> 12345[eE][+-]123[lLfF]?
 - FLOAT_CONSTANT_1		[x]

<> .123([[eE][+-]123)?[lLfF]?
 - FLOAT_CONSTANT_2		[x]

<> 12345.([[eE][+-]123)?[lLfF]?
 - FLOAT_CONSTANT_3		[x]

 - FLOAT_CONSTANT				[x]

 - BOOLEAN 					     [x]

 - numberconstant			[]
 - strcnst						    []
 - tokenconstant				[]
 - constant					    []

 - cdecl:- 					[]
 - include 					[]
 - import 						[]

 - compilerdirective 		[]

 - defer_spec					     []
 - defer_spec_no_init		[]
 - params						        []
 - initializer 				    []

 - templatespecifier			[]
 - namelist 					      [x]
 - names 						        []

<> (1, only those without initializers, 2 those where init_set is specified + those without initializers, 3 all except no_init with initializers, 4 all)
<> no_init member = default, default no_init is to uninitialized
 - init_desc					      []
 - qualifiers					     []
 - qualifiers_no_lex			[]

 - funct_qlfrs_no_lex			    []
 - shrt_funct_qlfrs_no_lex		[]
 - funct_qlfrs					         []
 - shrt_funct_qlfrs	        []

 - stct						      []
 - arr							      []
 - dl							       []
 - star						      []
 - ref							      []
 - dref						      []
 - cref						      []
 - fptr						      []
 - nt							       []
 - sbknd						     []
 - subkind						   []
 - subtype						   []
 - basictype					  []
 - structuretype			[]
 - lmbdatype					  []
 - fptrtype					   []
 - autotype 					  []
 - typeoftype 					[]

<> cannot have reference to reference
 - subarraylen			[]
 - arraysize					[]
 - rf							     []
 - ptrarraydec			[]

 - innertype					   []
 - type						       []
 - membertype 					 []
 - member						     []
 - basemember					  []
 - structuremember		[]

 - if 							   [x]
 - elseif 						[x]
 - else 						  [x]

 - switch 						[x]
 - case 						  [x]
 - default 					[x]

 - try 						  [x]
 - catch 						[x]

 - foreach 					[]
 - forbaseeach 	[]
 - for 						   [x]
 - while						  [x]
 - dowhen						 [x]

 - dot							   []
 - arw							   []
 - index						  []
 - dotmem					 	[]
 - baseaccess			[]
 - memaccess				[]

 - funccall					          []
 - constructcall				      []
 - refconstructcall			    []
 - listconstructcall			   []
 - reflistconstructcall		 []

 - bracketexpression			   [x]

 - cast					   	[]
 - szeof						  [x]
 - variable					[]

 - preops 						[]
 - postops 					[]

 - scopeblock				 	[]
 - withblock					  []
 - labelblock 					[]
 - lambdafunc 					[]
 - constexpression	[]
 - fptrgen 					   []

 - atom:- 						   [x]

<> TODO select on || and &&
 - op11 					[x]
 - op10 					[x]
 - op9 						[x]
 - op8 						[x]
 - op7 						[x]
 - op6 						[x]
 - op5 						[x]
 - op4 						[x]
 - op3 						[x]
 - op2 						[x]
 - op1 						[x]

<> operator precendence hierarchy
 - op11g 						      [x]
 - op10g 						      [x]
 - op9g 						       [x]
 - op8g 						       [x]
 - op7g 						       [x]
 - op6g 						       [x]
 - op5g 						       [x]
 - op4g 						       [x]
 - op3g 						       [x]
 - op2g 						       [x]
 - op1g					       	 [x]

 - ternary 				     	[]

 - expr						        [x]

 - valexpression				 [x]

 - rtn 						        []
 - yld 					        	[]
 - thrw 						       []
 - loopctlr					     []
 - goto						        []
 - basiclabel					   []
 - expression 					  []

 - exprend 					     [x]
 - block						       [x]
 - expr_block					   []
 - func_expr_block			[]


<> classes/structs (first is match value, second is value, third is match type, fourth is type)
 - templateparam			 	[]
 - templateparams				[]

 - basedef						     [x]
 - vardef						      [x]

 - virtualfuncdec 			[x]
 - destructor 					  []
 - proxy 						      []

 - clsmember					    []
 - class						       []

<> functions and operators
 - prps						        [o]
 - genops						      [o]

 - funcdef 				     	[]
 - genoperator 			  	[]
 - preoperator 				  []
 - castoperator 				 []

<> global variable
 - globalvar 					   []

<> build a type, needed for template classes
 - buildtype 					   []

<> def/alias
 - aliastype 					   []

<> enum type
 - enumname:- 					  [x]
 - enum 						       [x]

<> declare friend of module / namespace
 - friend 						     []

<> declare using module / namespace (mean you don't need the "name." of the namespace or module)
 - using 						      [x]

<> declare namespace
 - namespace 					   [x]

 - decl:- 					     	[x]
 - declaration:- 				[x]

 - decls 						      [x]

 - main						        []


# Top Level Plan - Project plan

- compiler/virtual machine (all implementable features, X86-64 only) [here]
- remake all of the libraries (everything except dionysus and opengui)
- make new libraries
  - copy
  - deep copy
  - comparison
  - streaming (in, out)
  - string printing
  - cycle scan
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


(KEY: X is complete, O is partial, empty is not started yet)
