<h1>Traffic Light Simulation </h1><br>
<img src ="https://github.com/MohitPaudel05/TrafficLIghtMImic/blob/main/TrafficLight.jpg" width =50% height=50%>
This is a simple Traffic Light Simulation Program written in C that mimics the behavior of a real-world traffic light system. The program cycles through Yellow, Red, and Green lights<br>
<h2>Objective<br>
The primary goal is to simulate a traffic light system that cycles through the three standard states: Red, Green, and Yellow..


<h3>Approach</h3>
<ul>
<li><p>Using a straightforward loop and state transitions. </p></li>
<li>  Using #include<unistd.h>header file for sleep() function to control the duration of each light state.</li>
<li>ANSI color code for better visualization</li>
 By implementing this approach, the program effectively models a basic traffic light system using simple programming constructs.

</ul>

  <b><h2> State Transistion</h2></b>
  <ul>	
  <p> For the state transition we use :</p>  
state = (state+1) % 4;<br>
Uses modulus (%) operator to loop through states (0 → 1 → 2 → 3 → 0 ...). <br>
<li>If state ==0 ;</li>
Yellow light is displayed<br>
<li>If state ==1;</li>
Red light is displayed<br>
<li>If state ==2;</li>
Again Yellow light is displayed with message ' Start your Engine!'<br>
<li>If state ==3;</li>
Green Light is displayed<br>
  </ul>

<h1> For Future</h1>

  



