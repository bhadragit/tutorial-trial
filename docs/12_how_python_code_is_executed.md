# Chapter 12 - How Python code is executed
time duration: 26:59 - 29:45  
1. Computers only understand machine level instructions, so high level languages like C, Java and python need to be translated before execution.  
2. In C, this translation is done by a compiler that produces machine code tailored to a specific operating system and hardware.  
3. This means a C program built for windows wont work on a Mac due to differences in system architecture.  
4. Java handles this by converting its source code into a universal format called bytecode.  
5. This buytecode is executed by the Java Virtual Machine (JVM), which adapts it to the host system's machine code on the fly.  
6. Python works in a similar way - its default implementation (CPython) converts code into bytecode, which the Python runtime executes.  
7. Jython, a variant of Python, translates Python code into Java bytecode instead of Python bytecode.  
8. Because of this, Jython programs can run on the JVM and even use Java libraries within Python scripts.  
9. This allows smooth integration between python and Java code under the same runtime.  
10. Using virtual machines and bytecode makes language like Java, Python and C# more flexible and portable across platforms. 