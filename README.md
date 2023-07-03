# Realtime-Visualization-of-Aerial-Trajectory
The project aims to develop a user friendly and efficient web-based application for the clients.
![image](https://github.com/ProjnaSadhukhan/Realtime-Visualization-of-Aerial-Trajectory/assets/137986611/c4ddb5a5-38ba-43e6-8d85-62078e52b3f6)

<h2> Functional Requirements:</h2>
<ol>
  <li>The application should continuously receive data from the 
server. The server sends the data through a UDP packet every 
100ms.</li>
  <li>Two modes of operation: 
      a. Unicast 
      b. Multicast
  </li>
  <li>The application receives data from two servers. The second server 
is provided as a failsafe in case Server 1 fails. </li>
  <li>Server 1 and Server 2 are manually synchronized. On the 
basis of the Chain Selection by the user, there are three modes: 
c) Chain 1 (Forced Server 1 mode) 
d) Chain 2 (Forced Server 2 mode) 
e) Auto (Switches to Server 2 if Server 1 fails) </li>
  <li>GUI for the clients which provides ‘Views’ to the clients 
based on their requirements. </li>
  <li>Plotting the data sent and displaying in the form of a graph. The 
graph must meet the following minimal functionalities: 
f) Auto scaling for the axis based on the received data 
g) Manually setting the range for each axis 
h) Zoom in and zoom out option 
i) Control to hide or show grid lines, title for each plot, ticks 
and their labels along each axis 
j) Changing the color of the plots based on 
user input </li>
  <li>Ability to switch between different graphs or 
views.</li>
  <li>Displaying the data received every one second, thus enhancing 
user readability.</li>
  <li>Update and keep track of the number of sensors and Aerial 
Vehicle participating in the 
mission. 
</li>
  <li>Selecting/ deselecting the active sensors to be displayed 
on the graph. 
</li>
  <li>A text view for displaying the data without any delay. </li>
  <li>Keeping track of the activity of the sensors with 
respect to time. 
</li>
  <li>Displaying information on mouse hover over the 
graph. 
</li>
  <li>Drawing annotations like circles, lines, points and text based on 
user input, to mark certain important locations on the plot. </li>
  <li>Screenshot at any instant of time: 
a) Screenshot of each individual sensor active for the mission 
b) Screenshot of the plot for all sensors active at the same time. 
</li>
  <li>Dynamic settings for the font size based on the number of Aerial 
Vehicle participating in the mission.</li>
  <li>Designing the appearance and color for the data displayed to the user. 
</li>
</ol>
