In general, the interpreter is responsible for reading bytecodes from file and subsequently using other helper classes,
Java abstraction and reflection, it creates bytecode classes, resolve symbolic addresses, initialize parameters
and execute bytecodes. The degubber extends the behavior of some bytecodes and operatates in debug mode 
given the -d switch. The -d switch gives the user a "limited" number of debug commands such as set breakpoints,
clear breakpoints, continue, etc. The interpreter can run in either mode; "normal" or debug mode. To run this 
program in debug mode use the following command. 
  java -jar interpreter.jar -d <base source file name> e.g.,
  java -jar interpreter.jar -d factorial

Ro run this program in interpreter mode mode use the following comnand:
  java -jar interpreter.jar factorial.x.cod
