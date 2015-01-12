---
layout: post_page
title: Printrbot Simple
---

Project Goal:

Built and improved upon the design of the Printrbot Simple 3D printer 

Project Details:

Since my interests are focused in rapid prototyping, I jumped at the opportunity of purchasing one of the first 3D printers on the market for hobbyists. However, a 3D printer made out of zip ties and laser cut wood can only get you so far. Soon after finishing the assembly and getting the printer up and running I started modifying it to improve printing performance. 

The first step I took in modifying the printer was to add end-stop switches to the X Y and Z axis. I did this by designing mounts out of wood and screwing them onto the frame of the printer. This allowed the Repetier-Host software that runs the printer to auto-indicate. I also noticed some separation in the layers of the print that made the printed pieces brittle and flimsy. This was due to uneven/rapid cooling of the PLA after it leaves the extruder. My simple fix was to use a sheet of glass as the printing bed instead of the wood. The glass held more heat and distributed it more evenly than the wood so the prints were more uniform. I also installed a heating bed as well to ensure that flat pieces would cool at a consistent rate to prevent curling around the edges. This was done with an off-the-shelf resistive heating bed that I placed below the glass bed. With these modifications, the printer resolution improved greatly. 

![alt text](/img/printer.jpg "Fully assembled printer before glass bed modification")
<br />
![alt text](/img/printerbottom.jpg "printing bed assembly")
<br />
![alt text](/img/print.jpg "first print")
<br />
![alt text](/img/printtest.jpg "first successful print")