import turtle

def polygon(sekil, ku, ks):
    aci = 360 / ks

    for _ in range(ks):
        sekil.forward(ku)
        sekil.left(aci)


ekran = turtle.Screen()


poligon_turtle = turtle.Turtle()
poligon_turtle.color("yellow")
turtle.bgcolor("black")

polygon(poligon_turtle, 100, 4)


ekran.mainloop()
