# Lab1

What are primitive elements? 
Primitive Elements are the base elements that python functions with. These elements include Interger Numbers, Floating-Point Numbers and Complex Numbers. 
Intergers are whole numbers and do not include fractions or decimals.
Floating-Point Numbers are decimal numbers and you can tell the difference between these and intergers because these will have decimals.

How can we combine primitive elements?
We can combine primitive elements by writing them together in code and using strings.

What number is represented by 319e5?
319000005

Create a new file called sequence1.py. In sequence1.py, answer problem 1.30: Use the range function to create and output a sequence of the multiples of 5 up to 50.
for x in range(0, 55, 5):
    print(x)
    
Create a file called sequence2.py. In sequence2.py, answer problem 1.31: Use the range function to create and output a sequence of numbers from −10 to 10.
for x in range(-10, 11, 1):
    print(x)
    
Create a file called drawCircle.py. In drawCircle, use Listing 1.7 to draw three circles.
import turtle

myTurtle = turtle.Turtle(shape="turtle")
myTurtle.circle(50)

myTurtle.penup()
myTurtle.setposition(-50, 0)
myTurtle.pendown()
myTurtle.circle(20)

myTurtle.penup()
myTurtle.setposition(50, 50)
myTurtle.pendown()
myTurtle.circle(90)

turtle.getscreen()._root.mainloop()

Create a file called loops.py. In loops.py, output the following sequences: 1) 1-10 increment by 2) 20-15 decrement by 1, and 3) 0-100 increment by 2.
for x in range(0, 12, 2):
    print(x)

for x in range(20, 14, -1):
    print(x)

for x in range(0, 101, 2):
    print(x)



