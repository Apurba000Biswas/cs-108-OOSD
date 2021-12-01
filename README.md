# cs-108-OOSD

## Object Oriented System Design :

    Foo x = new Foo(1);
    Foo y = new Foo(2);
    x = y;

There is also an old java object copying facility called "Cloneable", but it turned out to be a messy design
and has fallen out of favor. I recommend that you never use it.

## Running Java File From Command line:

    javac Demo.java

Above command compile the java file into the java class file here Demo.java is java file/class name

    java Demo

Above command runs the generated class file previously created.


## Decorator Pattern :
Decorator pattern allows a user to add new functionality to an existing object without altering
its structure. This type of design pattern comes under structural pattern as this pattern acts 
as a wrapper to existing class.

This pattern creates a decorator class which wraps the original class and provides additional
functionality keeping class method's signature intact.

We will learn about this later.

