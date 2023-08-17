# Java

#### Java is a popular and widely used programming language known for its portability, reliability, and versatility. It was developed by James Gosling and his team at Sun Microsystems (now owned by Oracle Corporation) and was first released in 1995. 


![imagename](https://www.agilesparks.com/wp-content/uploads/2022/08/Java_logo_icon.png)

  ### Java Compiler :
* Java compiler converts the source code into byte code which have the extension .class
* This byte code not directly run on system
* We need JVM to run this
* Reason why java is platform independent

  ### Java Interpreter :
  * Copnverts byte code to machine code i.e 0's and 1's
  * it translate the byte code line by line to machine code
 
# JDK

#### The Java Development Kit (JDK) is a software package provided by Oracle Corporation (and other vendors) that includes tools and utilities for developing, compiling, and running Java applications. The JDK is essential for anyone who wants to write, compile, and run Java programs.
#### It is a package that includes :
1. Development tools : To provide an environment to run program
2. JRE : To execute your program .
3. A compiler : javac
4. Archiver : jar
5. Docs Generator : javadoc
6. Interpreter/Loader

# JRE
* It is installation package that provides environment to only run program
* it consist of :
  1. Deployment technology
  2. user interface toolkit
  3. Intergration libraries
  4. Base libraries
  5. JVM : Java virtual Machine
 
     ## Compile Time :

   |.java file|.class file|
   |----------|-----------|

* After we get the .class file the next thing happen at runtime .
  1. Class loader loads all classes needed to execute the program
  2. JVM sends code to bytecode verifier to check the formet of code

    
# JVM Exection :
* Interpreter
  * line by line execution
  * when one method is called many times it will interpret again and again
* JIT
  * Those method that are repreated, JIT provides direct machine code so that interpretation is not required
  * makes execution faster
  * Garbage collector


# Work of Java Architecture :

![imagename](https://static.javatpoint.com/core/images/java-architecture.png)
