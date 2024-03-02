# Python-import-turtle-Advance-Art-108
Create python use import turtle graphics code
from turtle import*
import colorsys
title("Satyam Shorrf")

speed(0)
h=0.10
bgcolor("black")

for i in range(73):
    c = colorsys.hsv_to_rgb(h,1,1)
    color(c)
    h+=0.2
    pencolor(c)
    begin_fill()
    forward(100)
    left(30)
    forward(50)
    left(30)
    end_fill()
    circle(20)
    forward(50)
    begin_fill()
    circle(10)
    end_fill()
    up()
    home()
    down()
    left(5*i)
done()    
