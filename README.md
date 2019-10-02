# freebird
An attempt
import java.awt.Graphics;

import java.awt.Color;


{
private String name;
private int x,y;
private Color color;// color is a datatype of color, color could be X

public Frog( String n, int px, int py, Color c )

{
   name = n;
   x= px;
   y= py;
   color = c;
   

}//end constructor

public void draw (Graphics g)

{
g.drawOval(x, y, 50, 40);
g.drawString( name, x, y);

}//end draw

}//end Frog
