# First program
> **Note** I'm assuming you already have java installed in your computer, including the JDK, I highly recommend you to follow a guide on youtube or google for it to intall the Java JDK in your computer, also is important that you are able to execute the `javac` command in yout command line, in this chapter I'll use the command line to compile and run your first program, the use of IDEs or special tools to make this easy will be used later.

Ok, enough talk, let's create our first java program. First, let's create your first java file, you can use Notepad, commandline or any Text editor or IDE which allows you tu edit files. ([here](https://www.g2.com/categories/java-integrated-development-environments-ide) is an useful java IDEs)

Create a file and named: `FirstJava.java`
And type the following code:
```java
public class FirstJava {
}
```

This is how you start writing a **class** in Java (A receipt), not sure if you can see it in your text editor, but notice that the word **class** is highlighted in a different color then the word `FirstJava`, also a block of code was opened (Remember the concepts? the [Blocks](https://github.com/alejandro-devop/java-notes/blob/main/1-chapter/notes.md#blocks)), inside the curly braces (The block), it's where we must write our receipt specification (The **Attributes** and **Methods**). the code we just wrote is known as a **Class declaration**. Save your file and let's continue adding our fist method for this class and our fist java program.

Now inside our block add the following code: 
```java
public class FirstJava {

    public static void main(String args[]) {
        System.out.println("Hello world from Java!");
    }

}

```

Now let's run our code and see the magic, first execute:
```bash
javac FirstJava.java
```

If everything is ok you should see nothing, but besides your file you should see a new file created, a `FirstJava.class`, don't try to open it, if you manage to opened you wouldn't be able to understand it's content because is a binary file (We'll talk about this in a moment)

Now run the following command:
```bash
java FirstJava
```

you should see the following output:

```bash
Hello world from Java!
```

That's it! you just created your first java application! it only prints the text "Hello world from Java!" but hey! all bigger applications started small.

---

There should be a lot of things that probably you won't understand right now from the code we wrote: 
```java
public class FirstJava {

    public static void main(String args[]) {
        System.out.println("Hello world from Java!");
    }

}

```

let's try to break it down: 

```java
public class FirstJava {
}
```

This part indicates java that we want to create a receipt (Class) named `FirstJava`, the word `public` indicates java that this receipt is visible for anyone who can execute this receipt (We will discuse more about **access modifiers** which is how this `public` word is known)

Now comes the more difficult part:
```java
public static void main(String args[]) {
}
```

This is how we tell java that the recept `FirstJava` have a method, also, we are telling that this method is `public`, (We well talk more about this later), also the word `static` tells java that the method can be called without need to create an object from this class (We will talk more about this special modifier later), and the word `void` indicates java that this method does not return a value. the word `main` is the name of the action (**method**), is how java will indentify this action. Last but not least the `String args[]` as you can see this is inside a pair of parentesis, this means is a **method argument**, but don't worry, we will talk more about this later. Almost forgot, the braces open a new block, and everything inside this new block is considered the actions that this method does.

> **Note** In this particular example the method name `main` is taking a important role, as it's name says, it's the main method of this class, and this method will be executed everything we execute the command `java FirstJava`, which means all the instructions ([senteces](https://github.com/alejandro-devop/java-notes/blob/main/1-chapter/notes.md#sentences)) inside this method will be executed one afther the other.

For the last:
```java
System.out.println("Hello world from Java!");
```

This [sentence](https://github.com/alejandro-devop/java-notes/blob/main/1-chapter/notes.md#sentences) is telling java to print the text inside quotes `"` to the console, sentences as we mentioned are instructions which tells the computer to do something.

---

> **Note** The command `javac FirstJava.java` is used to compile our file. What is a compilation you wonder? If you search for it you'll find is the process of translating a human readable peace of code to a machine code (binary) our computer cannot understand instructions writen in english and humans can barely understand binary, that's why compiling our code is so important (at least with Java). If you're curious about this you can search more about this compilation process, but is not entirly required to learn how to program, as I mentioned, there are tools which does this for us once we save our code files.

