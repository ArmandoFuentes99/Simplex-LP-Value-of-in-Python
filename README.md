# Simplex-LP-Value-of-in-Python
Use Python for solving a Linear Programming porblem with the objective being a Value of: x  

Hello people of internet

I'm having trouble with a process I'm trying to automatize in Python it´s a LP problem  

I found Simplex LP method in Solver from Excel very useful to solve one problem at the time but I need to do it for 1000 or more problems so I really want to save me some time

PuLP is very good doing Solver stuff but only if you want to maximize or minimize th objective function and I need to equalize it to a VALUE OF:  

So the problem is this one:

I need to divide the payment into 3 debts, but I cannot make partial payments

I figured I can multiply the debts times a boolean (1 or 0) in a way that the objective (a sum product) equalizes the payment

So the money from the payment would go only to the debts I can completely cover

Solver works like this

![image](https://user-images.githubusercontent.com/89933909/172643923-720ada49-70fe-4cc2-92ef-054d60ea5bd8.png)

And it gives the correct way to divide the payments

![image](https://user-images.githubusercontent.com/89933909/172644161-cda852b7-40c7-4e96-a4da-830cfd8b48f9.png)


So I need to do the same thing for Python
Maybe there's a secret function PuLP has that can help me solve this or maybe Sympy or another library, idk
I'd really appreciate your help

So far I've done this hahaha

![image](https://user-images.githubusercontent.com/89933909/172646295-d2a6e2d0-2e97-4e38-805a-2f9eb373581f.png)


