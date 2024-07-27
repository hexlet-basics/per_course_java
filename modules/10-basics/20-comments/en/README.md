Almost all programming languages allow you to leave comments in code. They are not used by the code in any way and are needed only for people: for the programmer to leave notes for himself and for other programmers.

Comments in Java are of three types:

* **Single line comments** begin with `//`. Any text can follow these two characters, the whole string will not be analyzed and executed.
  A comment can take up an entire line:

    ```java
    // For Winterfell!
    ```

  Also, the comment can be on the line after some code:

    ```java
    System.out.println("I am the King"); // => For Lannisters!
    ```

* *Multiline comments* start with `/*` and end with `*/`. It is customary to start each line with `*`, although this is not technically necessary:
    ```java
    /*
    * The night is dark and
    * full of terrors.
    */
    System.out.println("I am the King"); // => I am the King
    ```

* **Documentary comments** start with `/**` and end with `*/`. It is already mandatory for them to start each line with `*`.

  Documenting comments are a subspecies of multiline comments. At the same time they have an additional function - they can be collected with the help of a special utility javadoc and given as documentation to your code. We will talk about them later - when we will analyze classes and methods.