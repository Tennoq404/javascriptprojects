JAVASCRIPT BEHIND THE SCENCES
 javascript is a high level object-oriented , multi-patradign prigramming language
 javascript is a high level prototype based object-oriennted multi-paradigm,interpreted or just-in-time compiled dynamic single threaded, garbage collected programming language with first-class functions and a non-blocking evenyt loop concurrency model
 javascript can exist outside of browser in a javascript runtime for example in node js
 
 Garbage-collection : bascially a tool in javascript with removes old and unused objects from the memnory in order not to clog it up with unneccessary stuff
 paradigm : an approach and mindset 0f structing code, which will direct your coding style and technique
javascript engine is aprogram the executes code
there are many javascript engines but the most popular is the google v8
 the v8 engine powers ggogle chrome but also node js
 any javascript engine always divide into a call stack and heap( which stores objects)
 The callstack is where programs are executed using the executed context and the heap is where objects used my the programs are kept
differnce between complilation or intrepretation\
  in compilation  the javascript code is converted into machine code at once, and written to A BINARY
  file that can be executed my the computer
    source code _ portable file- program running
interpretation : there is an interpreter the runs through the computer source code and interpres it line by line
javascript used to be a purely intrepreted language
modern javascipt does not run on any of this anymore modern js runs on the just in time compilation
the execution happens immediately after the compilation
as a piece of code enters is ran.. the code is first parsed and converted to AST syntax
the AST reads the code and checks for errors 
the next step is compilation with takes the AST and converts it to machine code 
the machine code is then executed right away
modern javascript has some very clever optimzation stratigies
they create very unoptimized machine code in the beginning so that it can
start executing as fast as possible .. then in the background the code is being optimized an recomplied
during the already running program execution. this is done multiple time and after each time the unoptimixec it bcode is easily swept away
with stopping the execution of corurse. this is what makes modern engines just like v8
so fast
what is a javascript runtime?
we can imagine a javascript run time as a big box or big container that contaains 
everything we need for js.
the heart of every js runtime is the js engine
