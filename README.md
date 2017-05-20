# python-sense-hat-animations
Raspberry Pi Sense Hat animation library 

Functions for animating; drawing lines, circles, triangles, and squares




# Demonstrate a bouncing ball
# It will draw the ball, erase it, and then draw another ball in a different position
# 


for x in range(0,7):
    ect.cell(image,[0,x],[randint(0,255), randint(0,255), randint(0,255)],0.1)
    ect.cell(image,[0,x],e,0.1)
for x in range(7,0, -1):
    ect.cell(image,[0,x],[randint(0,255), randint(0,255), randint(0,255)],0.1)
    ect.cell(image,[0,x],e,0.1)
