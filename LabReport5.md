# Part 1

## Student:
![image](studentWrongOutput)
Upon running my code, I am getting just 1 , 2 but I need to return the indices of the integers that add up to the target number. I want the output to be in square brackets but I am just getting the numbers. I think my error may be in initializing my `result` array and I believe I may not be returning the array correctly.

## TA:
Upon reviewing the code you provided, it appears that a potential solution to the issue might involve modifying your `System.out.println` statement. Take a closer look at how the output is currently being printed and consider how you can incorporate square brackets around it. Reflect on the mechanics of the `System.out.println` command and explore ways to manipulate its output format. Feel free to reach out to me if you require additional assistance with this matter.

## Student:
![image](studentSuccess)
I have resolved the issue! While I was looking within the method I gave no thought to how I could get my desired output from manipulating the `system.out.println`. I added brackets before the result at index zero and after the result at index 1. This made it so my output looked like [1, 2] rather than just 1 , 2. Thank you so much for your help!

## My file and directory Structure:
![image](directory)

## Contents of file before fixing bug:
![image](studentWrongOutput)

## Contents of my test.sh file before and after fixing bugs:
![image](bashContents)

## Full Command line of me running my code:
![image](fullCommandLine)

When I run bash `test.sh` it runs the contents that are in the test.sh file.

## What was needed to fix the bug:
I had to change up line number 7 in my file that had the error to include the brackets. Before it was `System.out.println("Indices: " + result[0] + ", " + result[1]);` and after adding the brackets after the expected result I just put, `System.out.println("Indices: " + "[" + result[0] + ", " + result[1] + "]");`

# Part 2

In the latter part of the quarter, I discovered some fascinating concepts that have significantly enhanced my coding experience. One standout discovery was Vim, a powerful text editor with lots of functionality accessible through its various key commands. Learning to navigate, edit, and search through code swiftly using Vim has been incredibly valuable. Additionally, I found it remarkable to utilize test.sh and bash scripts to automate the compilation and execution of my code, replacing the repetitive process of manually running javac and java commands. These shortcuts promise to save me considerable time and effort in the future, and they stand out as SOME of the most beneficial takeaways from this class!




