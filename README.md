# ps1-steering-wheel-to-pc

This will be used as a place to document my progress on trying to convert an old PlayStation one Lotus steering wheel I found in my loft into working with my computer as a controller for games etc.

![[Pasted image 20250917194903.png]]
![[Pasted image 20250917194927.png]]

I had previously worked on this wheel a couple years ago to achieve a similar goal, but I had only managed to tap into the potentiometer of the wheel and the two connected pedals with an arduino, and then map the values to a virtual xbox 360 controller.
This was good enough for a college project, but it was super janky having a bulky wheel and having to reach my keyboard and mouse to navigate menus in games. 

I have returned now to upgrade it to get full controller support with the front facing buttons and paddles.

Taking apart the wheel previously, I firstly discovered a small pcb that took a bunch of wires from within the wheel, along with the data from the potentiometers, then puts it into the old playstation 9 pin connector. 

![[Pasted image 20250917195945.png]]

To get my college level project working (with a pretty weak idea of what I was doing), I soldered some jumper wires from an Arduino nano to the pcb's pads for the three potentiometers (The wheel's angle, the accelerator, and break pedals).

![[Pasted image 20250917200306.png]]

As you

17th September 2025:


![[Pasted image 20250917193450.png]]