import turtle
turtle.hideturtle()
turtle.speed(0)
turtle.getscreen()
turtle.begin_fill()
turtle.color("gold","cyan")
for i in range(12):
    turtle.circle(30)
    turtle.right(360 / 12)
turtle.end_fill()
turtle.mainloop()
