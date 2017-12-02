# PDG
<p>
	<b>PDG - Peck Drilling Gcode</b> creator generates a drilling cycle program. 
	The output program uses standard gCodes. In theory it should 
	work on any CNC milling type machine that uses standard gCodes. 
	I've used it on my Xcarve. <br />
	<br />
	You enter the drilling parameters such as drill diameter, 
	hole depth, peck depth, start height, retract height, Inch/Metric etc. 
	From the entered parameters the peck drilling cycle is created. 
	The gCode program file can then be saved/downloaded to your computer<br> 
	<br>
	There are two flavors of PDG. <b>dxfPDG</b> and <b>ezpzPDG</b>.
	<hr style="text-align:left; margin-left:0; width:460px; height:2px; 
	      background-color:black; border: 0 none;" />
	<h2><a href="https://popsshebang.github.io/PDG/dxfPDG">dxfPDG</a></h2>
	dxfPDG reads the hole locations from a 2D dxf file. The locations are 
	processed and the gCode generated. 
	<h2><a href="https://popsshebang.github.io/PDG/ezpzPDG.html">ezpzPDG</a></h2>
	Use ezpzPDG when you need just a few holes and already know the hole locations. 
	ezpzPDG lets you enter up to 10 XY pair hole locations to process.<br>
	<br>
	(More locations could be added by running ezpzPDG twice. Saving as two different 
	files. Then cut and paste to append one program to the bottom of the other.)<br>
  </p>
