# Finnish-School-Robotics
## What is robotics?
**Robotics** is the field of designing, building and programming robots to do different tasks.
## What is an RGB LED?
An RGB LED is a light that can make different colors by *mixing* three colors.
- R stands for red.
- G stands for green.
- B stands for blue.
## How do we change the LED colors with Python?
We give CyberPi three numbers in this order: red, green and blue. In this example, 255 turns red to full brightness, and 0 keeps green and blue off.
~~~python
import cyberpi

cyberpi.led.on(255,0,0)
~~~
## What happens when we turn off all the RGB LEDs?
When we turn off all the RGB LEDs, they stop giving off light.
~~~python
cyberpi.led.off()
~~~
## Robots in everyday life
1. Robot vacuums clean floors at home.
2. Robotic lawn mowers cut grass in gardens.
3. Warehouse robots move packages so they can be prepared for delivery.
## Useful link
[mBlock](https://mblock.cc)
