---
layout: post_page
title: Programming Jigs
---

Project Goal:

Designed and prototyped programming jigs for hackathon PCB badges

Project Details:

BOILERMAKE is a student run organization at Purdue University that puts on a hackathon every year in October. In 2014, they wanted to add a little something extra to their hackathon and decided to make badges for their hackers that doubled as development boards (much like a mini Arduino). The source of the challenge was the time frame in which the development and manufacturing of the boards took place. Over 600 boards needed to be assembled and programmed within 48 hours so we had to streamline the process as much as possible. I worked on designing programming jigs to expedite the programming step.
For programming, there were six pins that needed to keep in contact with the board for about forty-five seconds. To ensure a good connection between the board and the pins I decided that pogo pins were optimal. These were soldered into perfboards to keep the pins aligned and connect the programmer adapter to the pogo pins. In order to minimize programming error, I wanted a design that would allow the user to attach the board to the pogo pins without having to hold it in place so contact was kept throughout the programming. I went with a simple design would rotate an arm under the board to hold it in place. 
The jig was 3D printed in two pieces so the exact sizing could be done during assembly so the boards would fit snugly in the jig. Also, this meant that the shrinking of the plastic while it cooled from the print didn’t need to be taken into account. The bridge design across the board was originally meant to help align the pins, however, when it came time to assemble the jigs it was difficult to align the pins with both sides of the board. Since the time window for designing the jigs was so small, I decided to throw out half of the jig and only keep the half that clamped around the board. This meant the jig still held the pins and helped align the pins, but the alignment was a little less snug. 
Overall, the jigs allowed users to expedite the programming process by programming multiple boards at once because they did not need to hold the pins in place. 

![alt text](/img/jig.jpg "rough sketch of final jig design")

![alt text](/img/badge.jpg "hackathon badge")
