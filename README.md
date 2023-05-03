Download Link: https://assignmentchef.com/product/solved-cs341-lab10-servo-motor
<br>
A servomotor motor is a motor that can be set to a specific position. In manufacturing, a servomotor may control a robot arm to hold a tool in position for the required work. In a petroleum or chemical plant, a servomotor may open or close a valve controlling flow in a pipe. An artist used a bunch of servo motors to create a <a href="https://www.youtube.com/watch?v=BZysu9QcceM">wooden mirror</a>.

We will use an analog input to control the position of the servo. In this lab we will use a <a href="https://en.wikipedia.org/wiki/Potentiometer">potentiometer</a> (a “pot”) across +5 volts and ground (0 volts) and connect the center tap wire to the analog pin A0 which our code will read from. The center tap is controlled by the position of a knob/shaft and in each position it presents a voltage value that varies between 0 and +5 volts on the wire to the input pin. As we have seen previously, the analogRead function lets us read an int value between 0 and 1023 that corresponds to the voltage.




The Code

This lab won’t require you to modify the <a href="https://github.com/jack17davis/cs341">starter code</a>.







Setting Up the Hardware

Lab Report

Please answer the following questions in your report:

<ol>

 <li>With the code <em>y = map(x, 0, 1023, 0, 180);</em>

  <ol>

   <li>If x is 0 what will y be?</li>

   <li>If x is 512 what will y be?</li>

   <li>If x is 768 what will y be?</li>

  </ol></li>

</ol>