# python-sense-hat-animations
Raspberry Pi Sense Hat animation library 

Functions for animating; drawing lines, circles, triangles, and squares



# Animate a ball moving on the screen 

 
```python
for x in range(0,7):
    ect.cell(image,[0,x],[randint(0,255), randint(0,255), randint(0,255)],0.1)
    ect.cell(image,[0,x],e,0.1)
    
for x in range(7,0, -1):
    ect.cell(image,[0,x],[randint(0,255), randint(0,255), randint(0,255)],0.1)
    ect.cell(image,[0,x],e,0.1)
```


# Colorful squares
```python
for x in range(5):
    ect.square(image, [0,0], [7,0], [7,7],[0,7],[randint(0,255),randint(0,255),randint(0,255)],.01)
    ect.square(image, [1,1], [6,1], [6,6],[1,6],[randint(0,255),randint(0,255),randint(0,255)],.01)
    ect.square(image, [2,2], [5,2], [5,5],[2,5],[randint(0,255),randint(0,255),randint(0,255)],.01)
```

# Checker board
```python
for y in range(0,7):
    if (y%2 == 0):
        ect.line(image,[0,y], [7,y], b, 1)


for x in range(0,7):
    if (x%2 == 0):
        ect.line(image,[x,0], [x,7], b, 1)
        
```






# It's easy and there's much more!
