# Fetching Ball Vex Exp Robot
## Desciption: 
This is a Vex Exp robot which can search for a red object (the ball), and when it has found the object, it will grab it and return to the original position. Here is the demonstration/presentation video: https://youtube.com/shorts/gLiFjTAw0eY?feature=share 

## The tasks:
1. Turn left for 45 degrees, and move forward 150 mm to search for the red object. Record to the movement log.
2. When the red object (ball) is detected by the vision sensor, it will move 50 mm forward. Record to the movement log.
3. When within the range of 10-20 on the distance sensor it will spin the claw 90 degrees and grab the object. Record to the movement log.
4. Wait 0.3 seconds.
5. It will lift up to 300 degrees using the arm. Record to the movement log.
6. Wait 0.2 seconds.
7. Use the movement log to reverse the movement and retrace to the start position.
8. Use the movement log to move the claw down and open.
9. The end.

## How to build:
We used the EXP Clawbot Build Instructions (1) to create the robots hardware, with a small adjustment of a 4 x 16 flate plate at the front to not have the arm hang low and get trapped. Alongside this we attached a vision sensor (optical) and distance sensor devices which where used to detect the object and determine when to grab it. For the software we used VEXcode exp using python, which we would download as a program to the exp brain, and used the devices mentioned earlier alongside the motors to code the movement. 

## References
### Hardware:
(1) EXP Clawbot Build Instructions 280-7735-752. (n.d.). https://content.vexrobotics.com/vexexp/pdf/builds/exp-clawbot-rev4.pdf
### Software: 
(2) Education Public. (2023, May 15). Vex EXP: Optical Sensor Coding. YouTube. https://www.youtube.com/watch?v=OWVnr9mia78

(3) Education Public. (2023a, May 1). Vex EXP: Distance Sensor Coding. YouTube. https://www.youtube.com/watch?v=l3Lyyp6aVtU
