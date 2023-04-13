# app-fault-1
It's very simple, just send an input to break the loop and display the flag! Where does this happen? Let's examine the code.

![bug finded!](find-bug.png)

At first glance, we can see that this challenge can have **Integer Overflow**! So let's test. You can use this [article](https://www.geeksforgeeks.org/check-for-integer-overflow/) to read more.

![integer overflow](integer-overflow.png)

***Solved (:*** It was very simple, wasn't it?

flag is: queraCTF{ZERO_DIVIDE_BY_ANYTHING}
