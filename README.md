# 16502_FindHer

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![button](https://github.com/Choi-JaeHyeok-21500749/2670_ContinuousMaxMultiplication/blob/main/2670_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

At first , save the value of moving in the [4][4] array. 

The example graph will be saved like below.

    A   B   C    D

A       1   

B           0.3   0.7

C  0.6            0.4

D                 1

Then multiply 0.25(1/4) to each point because there is 4 option at first(A ,B , C , D) and multiply 100 to present in percent notation.

You should check by moving row ( not col).

After 10 minute , the possiblity of D will be (0.7(from B) +0.4(from C) + 1(from D)) * 0.25 * 100.

After that save in another array and after that multiply that percentage and possiblily array (size [4][4]).


## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
