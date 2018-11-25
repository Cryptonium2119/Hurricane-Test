# Hurricane-Test
This is a project from 2018 Science Fair, it attempts to find the path of the hurricane
======================================================================================
V.0.0.1:
https://py3.codeskulptor.org/#user302_n4NOnHk3DHvejWX.py

If the Link Does Not work, Then Paste This Code Into py3.codeskulptor.org

Script:

import simplegui

message = "Hello World"

def click():
    global message
    message = ""
    A = raw_input("Enter A Value")
    B = raw_input("Enter B Value")
    frame.start()
def draw(canvas):    
    canvas.draw_text('Hurricane Harvey', (300, 300), 72, 'Red')
    canvas.draw_circle((A, B), 0.5, 0.1, 'Blue', 'White')
    
frame = simplegui.create_frame("Hurricane", 1000, 900)
frame.add_button("Harvey", click)
frame.set_draw_handler(draw)

====================================================================================
