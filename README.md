# js-weird-parts

syntax parsers: read code char by char to determine if syntax is valid and translatable into machine instructions

lexical environment: where code is physically located, and what surrounds it, matters. 

execution contexts: the things that manage which lexical environment is executing 

names and values
object: a collection of name/value pairs

global execution context
  global object
  'this': special variable

hoisting

execution context phases
  creation phase
    hoisting: setting up memory space for variables and functions
      undefined: I don't know what this value is yet
  execution phase

relying on hoisting is dangerous