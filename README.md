## This is boilerplate I use when implementing C++ code into a Node.js project
The reason why I have the two separate folders for "node" and "native" is because in Visual Studio I can add the include directory to the c++ solution for intellisense. I tried putting a cpp folder in the node folder outside of a c++ solution, but VS only let me add headers for each individual .cpp or .h file which would be a pain to configure upon creating each new module/class

I'm new to VS so this may not be the best approach :P
#### Note: this isn't strictly for VS but I did my best to include good VS support

#### Also note: The CMakeLists.txt is not used for building the project because I use node-gyp to build. Rather, it is included in this project because I use CLion which requires a CMakeLists.txt for proper intellisense support
