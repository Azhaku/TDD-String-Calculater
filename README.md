# Assesment

Incubyte TDD Assessment
Careers Software Craftsmanship TDD
Hello there and welcome to the Incubyte TDD Kata!

This assessment is the first step in our recruiting process and will be followed by two pair programming/discussion sessions.

What We’re Looking For
A Software Craftsperson at Incubyte is a person who has a strong commitment to the craft of software development. Someone who is passionate about software, knows her/his tools well and is able to use them effectively to create carefully crafted software. Ultimately, a person who has a strong sense of what it is they are doing and is self-motivated to learn and grow.

TDD is a core practice for all of us at Incubyte. We strongly believe that well written software, is a lot more valuable for the business and end users, as compared to software that is hacked together (but works!).

Through this assessment, we want to evaluate how readable and testable your code is. We want see the Software Craftsperson in you.

As software developers, searching the internet is something of a necessity and is vital tool for being effective problem solvers. We encourage you to Google away! You can also visit our inspiration page to find some useful talks and references that will help you sail through this assessment.

With that, let’s jump right in! Follow the instructions below, take your time to do it well and send us your kata once you’re happy with what you’ve done.

Things To Keep In Mind
Host your solution on a public GitHub/GitLab repository
Follow best practices for TDD. Watch this video to understand TDD better
Commit your changes frequently to show how your code evolves with every step of TDD
We encourage you to use the programming language and tools you feel most comfortable with
Do not rush, take your time, we want to see your best work!
Send us the link to your repo once you’re happy with what you’ve done
String Calculator TDD Kata
Create a simple String calculator with a method signature:

int Add(string numbers)
The method can take up to two numbers, separated by commas, and will return their sum.

For example "" or "1" or "1,2" as inputs. (for an empty string it will return 0)

Hints:

Start with the simplest test case of an empty string and move to one and two numbers
Remember to solve things as simply as possible so that you force yourself to write tests you did not think about
Remember to refactor after each passing test
Allow the Add method to handle an unknown amount of numbers

Allow the Add method to handle new lines between numbers (instead of commas).

The following input is ok: "1\n2,3" (will equal 6)
The following input is NOT ok: "1,\n" (not need to prove it - just clarifying)
Support different delimiters

To change a delimiter, the beginning of the string will contain a separate line that looks like this: "//[delimiter]\n[numbers…]" for example "//;\n1;2" should return three where the default delimiter is ";"
The first line is optional. all existing scenarios should still be supported
Calling Add with a negative number will throw an exception "negatives not allowed" - and the negative that was passed.

If there are multiple negatives, show all of them in the exception message.

Want more? Check out TDD Kata 1 for the full version. Extra points for completing all the steps!
