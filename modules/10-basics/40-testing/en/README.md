Our website automatically checks your solutions. How does it work?

In the simplest case, the system just runs your code and looks at what is displayed on the screen. And then checks it against what we “expected” from the assignment.

In the next, more complex lessons, you will write methods - some kind of mini-programs that receive information from the outside world and perform some operations. Checking your decisions in such cases looks a bit more complicated: the system runs your decision and passes some information. The system also knows - “expects” - exactly what answer the correct method should return given that input.

For example, if your task is to write a code to add two numbers, the verification system will pass it different combinations of numbers and check the answer of your code against the real sums. If the answers coincide in all cases, the solution is considered correct.

Here is a simple example: in one of the future lessons you will have to write a code that performs calculations and gives an answer. Suppose you make a small mistake and the method produces an incorrect number. The system will respond like this:

<pre class='hexlet-basics-output'>expected: “35” but was: “10”</pre>

The most important part starts after the colon: “expected: “35” but was: “10”“”. That is, the correct code should have produced 35, but the current solution is not working correctly and produces 10.

Besides our tests, it will be extremely useful to use the [repl.it](https://repl.it/languages/java) service.

---

Sometimes during the solution process it will seem that you have done everything correctly, but the system is “capricious” and does not make a decision. Such behavior is practically excluded. Non-working tests simply cannot get to the site, they are automatically launched after each change. In the vast majority of such cases (and all our projects in total have run millions of tests over many years), the error is contained in the solution code. It can be very unnoticeable, you may have accidentally entered a Russian letter instead of an English one, used a lower case instead of upper case or forgot to print a comma. Other cases are more complicated. Your solution may work for one set of input data but not for another. That's why you should always read the problem condition and test output carefully. There is almost certainly an error indication there.

However, if you are sure of an error or find some inaccuracy, you can always point it out. At the end of each theory there is a link to the lesson content on the github (this project is completely open source!). Once there, you can write an issue, see the contents of the tests (there you can see how your code is called) and even submit a pullrequest. If it's still a dark forest for you, join our community [Hexlet Community in Telegram](https://t.me/hexletcommunity/12), we always help you there in the Volunteers channel.