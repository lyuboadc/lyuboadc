import tirtle,math
egg * turtle.Pen()
egg.speed(0)
def oval(c,b,r):
    egg.up()
    for i in range(315):
        x = a*r*math.cos(i/100)
        y = b*r*math.sin(i/100)
        egg.goto(x,y)
        egg.down()
egg.fillcolor(0.5,0.25,0)
egg.begin_fill()
oval(1,-1,100)
egg.end_fill()
egg.fillcolor(1,1,0)
egg.begin_fill()
oval(1,1.5,100)
egg.end_fill()
egg.hideturtle()
turtle.done()



























