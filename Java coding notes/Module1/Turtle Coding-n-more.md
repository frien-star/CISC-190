# Turtle Notes
```Java
World w = new World();
Turtle t = new Turtle(w);
```
*Note: t isn't explicitly part of these functions. A variable is required to use in conjunction.
``` Java
t.forward(); // Specify amount
t.backward(); // Specify amount
t.turnRight();
t.turnLeft();
t.turn(); // Specfify amount
t.hide();
t.show();
t.moveTo(); // specify (x,y) coordinates
t.penDown();
t.penUp();
t.setPenWidth(); //Specified width in pixels
```
## Adding color:
Add at the top after the header:
``` Java
import java.awt.*;
```
To create your color, make a color object: Color();
```Java
Color C = new Color(); // Use a RGB value (x,y,z)
```
To Designate a turtle a color: setColor();
```Java
YourTurtlesName.setColor(c);
```
