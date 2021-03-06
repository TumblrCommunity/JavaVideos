> Video Time 1:45

Welcome to our second video to prepare you on the journey to Java! We are going to quickly cover what a compiler is, a bit more about the JVM, and why this is an important concept to grasp.
> Compiler appears alongside the JVM and a thought bubble surrounding a codeventurer. 

First off, a compiler transforms code between languages. Think of it like google translate. 
> Google translate turning code into another language 

You want your code to be able to be read by any machine, but not all machines support your language.  
> Puzzled computer

This is why we need compilers. 
> Computer gets a lightbulb above its head, smiles

They turn specific code into a broad language such as C or assembly, which most devices can read and carry out instructions for. 

A compiler has several important parts within it:
> show the respective parts popping up and carrying their functions. tokens can be bitcoins. generator can have claws that assemble code.

- The Lexer which scans the code and separates it into different parts, or *tokens*.
- The Parser identifies the syntax, often separating tokens into a *tree*.
- The Generator takes the tokens and builds machine code off of them.

Some languages might have a compiler with a few more features or steps, but this is the basic overview. Now the need for the JVM arose when engineers discovered that different operating systems had different *APIS* or ways that their code could communicate with the OS. 
>Shows 3-4 OS's with the API visualization

They created a standarized layer above the *APIs* called the *JVM* that would be able to work with those operating systems from Java code. This meant that you could write a code to create a Java applet for pac-man on your Windows machine, and it would still work on your friends Linux machine. 
> Shows JVM above the APIs and Java in the center, linking to all the JVMs

