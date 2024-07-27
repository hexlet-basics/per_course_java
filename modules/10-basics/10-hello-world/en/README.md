Learning a programming language traditionally starts with the program “Hello, World!”, which displays this text on the screen.
<pre class='hexlet-basics-output'>
  Hello, World!
</pre>

In Java, this program will look like this:

```java
class App {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

https://replit.com/@hexlet/java-basics-hello-world

The text *Hello, World!* will appear on the screen thanks to the `System.out.println()` command, where `println()` is an abbreviation for *print line*. It prints the value specified in brackets `(“Hello, World!”)`, in this case a string. The string itself is framed by double quotes `“”`. If this is not done, the compiler will indicate a syntax error:
```bash
# Like this, for example
App.java:5: error: unclosed character literal
System.out.println('Hello, World!');
```

The command itself is inside several constructs that are necessary for even the simplest Java programs to work.
In this case, it is the `App` class and the `main()` method.

We won't dwell on them now, as you need to know a bit of programming to understand them. That's why in many tasks they are given “as is”, i.e. you won't have to set them yourself. When the time comes, we will analyze them.

## JShell

Moving through the lessons, you will constantly encounter code samples and descriptions of how it works. To understand them better and to be able to use the language, you should constantly practice and experiment.

That's why, if possible, run all the examples from the theory and experiment with unclear points.

The easiest way to get started with Java is at [onecompiler](https://onecompiler.com/jshell), which allows you to run line-by-line code right in your browser. Try going there right now and type this code:
```
System.out.println(85 * 3);
```
