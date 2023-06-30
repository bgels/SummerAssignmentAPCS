

# First Program

**PRO TIP**: Do not copy and paste code from online sources or earlier assignments. 

Even if you are copying an example to test: typing valid java code will help you remember the java constructs and will make later sections of the program easier.

# Required Reading

Please read the chapter (indicated sections) and assess your ability using the interactive questions for those sections.

[CSAwesome 1-2](https://runestone.academy/ns/books/published/csawesome/Unit1-Getting-Started/topic-1-2-java-intro.html#first-java-program)
(whole page and all included questions)




# Do it in the CLI now.
The internet is full of wonderous things including browser windows that can run code. This is not how you will be expected to run code in class however!

To prepare yourself try to do it a different way: Using the command line interface.

Create a file named **Hello.java** and save it in your APCS folder(remember the one you created in the BeforeYouCode section). Note that the **H** is upper case.
Please pay attention to the spelling including capitalization. Note that java is case-sensitive, so upper and lower case letters matter. If you spell a word with the wrong capitalization it will create a variety of problems for you. 
In that file, write and this program:

```java
public class Hello{
      public static void main(String[] args){
          System.out.println("Hello world!");
      }
}
```

# Compile and run (Required to be able to do this for classwork/homework)
Open your APCS folder with a terminal, you will need to use it here.

Now, from the terminal run the **ls** command (Linux, Mac, GitBash, Powershell) or **dir**
command (windows command prompt) after typing the command press enter. Note that your directory should have one file
named **Hello.java**. If you do not see the file, then you didn't open the same folder the file is located in.

To compile **Hello.java** into Java Byte Code that can be run by the Java
Virtual Machine, type **javac Hello.java** and press enter. If the prompt comes back
with no errors, everything worked. If you see any errors, they include a line number. 
Resolve the errors by looking at the example carefully and seeing if you can fix your program. 
Note that errors sometimes show a line number after your mistake.

After you compile with no errors, look at the files in the directory again (ls, dir) and you'll see an
additional file named **Hello.class** - this is the compiled Java Byte
Code that can be run. 

Now run your program by typing **java Hello** and pressing enter.

Here is a sample of what you would see if you did everything correctly:
```
C:\Users\K\Documents\APCS> ls
    Directory: C:\Users\K\Documents\APCS
Mode                 LastWriteTime         Length Name
-a----         7/14/2021   1:58 PM            125 Hello.java

C:\Users\K\Documents\APCS> javac Hello.java

C:\Users\K\Documents\APCS> ls
    Directory: C:\Users\K\Documents\APCS
Mode                 LastWriteTime         Length Name
-a----         7/14/2021   2:02 PM            416 Hello.class
-a----         7/14/2021   1:58 PM            125 Hello.java

C:\Users\K\Documents\APCS> java Hello
Hello world!

```

# What do errors look like?

Most of the time you will not type the commands correctly and it cannot compile. See what this looks like by putting an error in your program - remove a quote or a bracket and recompile using **javac Hello.java** - read the error. Fix it and try to
generate another error. Finally fix and text the program again so that
it works.


