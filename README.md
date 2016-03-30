# Turtle 
You need : 
  - python shell 2.7.11
# Quick Start
  - Click on DOWNLOAD ZIP 
  - Open mindstorms.py 
```sh
Code Lines 
```

```sh
import turtle
def draw_square () :
    window = turtle.Screen ()
    window.bgcolor ("red")
    x = 10
    y = 50
    brad = turtle.Turtle ()
    brad.speed (0.2)
    while x<500 :
        
        
        
        brad.forward (y)
        brad.right (90)
        brad.forward (x)
        brad.right (90)
        brad.forward (y)
        x = x + 10
        y = y + 5

    window.exitonclick ()


draw_square ()
```

