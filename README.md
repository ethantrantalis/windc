# Wind

Wind is a hobbyist language designed to give the user control of a language (such as C) while still implementing many of the features of modern languages like Java and Python.

## Design Idea

### Features
As a functional language, the goal of this language is to introduce many of the modern features such as closures, array appending, string manipulation, etc. These features are designed to be as optimized as possible in order to leave little memory footprint and require minimal processing time.

### Safety
Wind combines generational copying  with mark and sweep (similar to Python) to effectively manage memory. Unlike C (the inspiration for this PL), there is no user allocation or de allocation of memory. While this does sacrifice some speed of the language, a need for secure programs is necessary for modern programs. This language is also *Strictly Typed* to reduce the amount of uncaught errors at runtime. 

### Speed vs. Features
While the introduction of garbage collection as well as "useful user features" may slow the language as a whole, programmers should be given the ability to use them when appropriate. As a "semi-solution" to the problem of speed, the compiler will be optimized to allow for certain features that are more "bare bones" to run faster. What this means is that the programmer can be given the choice to use features which may slow the program or use faster features when they are more necessary. These features will be noted in documentation and installation instructions for the language. 

### Assembler and Linker
This compiler will use the GNU Binutils as (Assembler) and ld (linker). These tools are well optimized for a fast, lightweight language like Wind. 

**(Development in Progress)**




  


