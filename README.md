# openpyweb
openpy is a full open source python graphics library written in 814 lines of code!

some examaple code:
```
from openpy import *

def main():
    win = GraphWin("My Circle", 100, 100)
    c = Circle(Point(50,50), 10)
    c.draw(win)
    win.getMouse() # Pause to view result
    win.close()    # Close window when done

main()
```
