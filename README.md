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

this project is not to be confused with
```
$ pip install openpy
```
we didnt even know it existed before release

download version 0.0.1

[download openpy0.0.1.zip](https://github.com/WuFdev/openpyweb/files/7618894/openpy0.0.1.zip)
