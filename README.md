Download Link: https://assignmentchef.com/product/solved-solved-lab6
<br>
learning goalsIn this lab you will practice tracing and implementing recursive functions where the input is a non-list or a possibly-nested list, as presented in lecture. You may want to review lecture materials. You should work on these on your own before Thursday, and you are encouraged to then go to your lab where you can get guidance and feedback from your TA . There will be a short quiz during the last 15 minutes of the lab, based on these exercises. reading recursion Work through the recursion exercises to practice tracing and understanding a recursive function. Remember to work from the simplest to more complex arguments and do not trace recursive calls that you have already understood, just replace them by the value they produce. Notice the structure of the code. There are three if…, elif…, else… blocks. The if and elif are for arguments that don’t decompose into parts that can be dealt with recursively, so they directly return a value without any recursive subcall. The else is for the general case: combines and returns the results of several recursive subcalls. writing recursion Open le nested list.py and save it under a new sub-directory called lab06. This le provides you headers and docstrings for the functions you will implement, as well as a helper function we think you’ll nd useful: gather lists: There will be cases where you have a list whose elements are sub-lists, and what you’d really like is to concatenate them into a single list. That’s what gather lists does. Now implement the following functions. implement list all Read over the header and docstring for this function, but don’t write any implementation until you ll in the steps below: 1. One of the examples in our docstring is simple enough not to require recursion. Write out an if condition that checks for such cases, and then returns the correct thing. Include an else… for when the argument is not so easy to deal with. 2. Now suppose the function works correctly and does what the docstring claims: returns a list of the non-list values from the list or non-list it is given. If you call the function on each element in a list and it returns such a list, how will you combine the resulting list of lists into the correct output? Go over these parts with your TA. After that, ll in the implementation and see whether it works. 1 implement max length Read over the docstring but again, don’t write the implementation before working through the steps below. 1. In the docstring there is an example where the argument can’t be broken into smaller, similar parts. Write an if condition that detects such cases, and then returns the right thing. Add an else to deal with lists that can be broken into parts that can be dealt with recursively. 2. Now assume the function works properly when it is called on the elements of a list: for a list, it returns the maximum length of the list and all its sublists, or for a non-list it returns 0. If you call the function and get a correct result for each element of a list, how can you correctly combine them so the function gives the right result for the entire list? (Don’t forget the length of the entire list gures into your result). Go over these parts with your TA. After that, ll in the implementation, and see whether it works. implement list over Read over the docstrings, then complete the steps below: 1. There are some arguments that cannot be decomposed into parts that can be solved by this same function. Write if and elif conditions to detect these cases, and then return the correct values. Put an else in place for the remaining cases, where the argument can be decomposed into recursive subcases. 2. Assume that the function now satises the docstring for all the elements of a list: if the element is string of length over n, it produces a list containing that number; it the element is another string, it produces an empty list, and if it is a list of strings, it produces a list of those over length n. If the function produced the correct result for each element of a list, how would you combine all those results into the correct overall result? Go over these parts with your TA, then implement the function and try it out on the given examples and any others you think of. additional exercises Here are some additional exercises to try out if you nish the lab above. As usual, the last 15 minutes of the lab will consist of a 15-minute quiz.