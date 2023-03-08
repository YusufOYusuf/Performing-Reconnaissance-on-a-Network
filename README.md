<h1>Performing Reconnaissance on a Network</h1>


<h2>Description</h2>
In this lab, I learned to perform reconnaissance on a network. Network reconnaissance is used to test potential vulnerabilities in a computer network. Information gathered during footprinting exercises is typically used to provide the targets for active reconnaissance.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux Rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the Desktop double click the Terminal icon <br>
Then type in the command "nmap" to discover the hosts and services <br>
<img src="https://i.postimg.cc/XYLKrbfF/Screen-Shot-2023-03-07-at-4-51-45-PM.png" height="80%" width="80%" alt=""/>
<br />

  
  
  
  
<br />
Now type in the "man nmap" command to display the complete manual for the tools <br>
<img src="https://i.postimg.cc/wM14VBkS/Screen-Shot-2023-03-07-at-4-54-49-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Now type the "nmap -sn 10.0.0.1/24" command <br>
This command tells nmap to stop port scan after host discovery and only print out the available hosts that respond to the scan <br>
<img src="https://i.postimg.cc/15s1SGJt/Screen-Shot-2023-03-07-at-5-01-11-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Now type the "nmap -O -v 10.0.0.1" command <br>
This command runs an operating systems discovery scan against the server and router <br>
<img src="https://i.postimg.cc/mZM1Js54/Screen-Shot-2023-03-07-at-5-05-43-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






