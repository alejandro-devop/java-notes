# First program
> **Note** I'm assuming you already have java installed in your computer, including the JDK, I highly recommend you to follow a guide on youtube or google for it to intall the Java JDK in your computer, also is important that you are able to execute the `javac` command in yout command line, in this chapter I'll use the command line to compile and run your first program, the use of IDEs or special tools to make this easy will be used later.

Ok, enough talk, let's create our first java program. First, let's create your first java file, you can use Notepad, commandline or any Text editor or IDE which allows you tu edit files. ([here](https://www.g2.com/categories/java-integrated-development-environments-ide) is an useful java IDEs)

Create a file and named: `FirstJava.java`
And type the following code:
```java
class FirstJava {
}
```

This is how you start writing a **class** in Java (A receipt), not sure if you can see it in your text editor, but notice that the word **class** is highlighted in a different color then the word `FirstJava`, also a block of code was opened (Remember the concepts? the [Blocks](https://github.com/alejandro-devop/java-notes/blob/main/1-chapter/notes.md#blocks)), inside the curly braces (The block), it's where we must write our receipt specification (The **Attributes** and **Methods**). the code we just wrote is known as a **Class declaration**. Save your file and let's continue adding our fist method for this class and our fist java program.

Now inside our block add the following code: 
```java
class FirtsJava {

    public static void main(String args[]) {
        System.out.println("Hello world from Java!");
    }

}

```






