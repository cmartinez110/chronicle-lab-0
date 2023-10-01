<h1>Introduction to Google Chronicle</h1>


<h2>Description</h2>
In this project, I investigated a domain using Google's Chronicle security information and event management tool (SIEM). I was able to answer basic questsions at the end of the lab, such as the IP address that the domain resolves to, the number of POST requests, and the threat classifications (a drop site for logs or stolen credentials).
<br />


<h2>Languages and Utilities Used</h2>

- <b>Chronicle</b> 

<h2>Environments Used </h2>

<h2>Project walk-through:</h2>

<p align="center">
Start by searching for a target filter. Here I used "signin.office365x24.com" and selected domains option: <br/>
<img src="https://i.imgur.com/dCh8vUb.png" height="80%" width="80%" alt="chronicle0"/>
<br />
<br />
The dahboard offers lots of tools to analyze events. In the left panel, we can filter  by "asset" or "timeline". In this example the timeline is selected and expanded to show all GET and POST requests. We can also see the virustotal profile ("VT" top of window), resolved IPs, sibling domains, and ET intelligence rep list. The ET intel rep list catagorizes as a drop site for logs or stolen credentials:  <br/>
<img src="https://i.imgur.com/6S1oXYn.png" height="80%" width="80%" alt="chronicle0"/>
<br />
<br />
VirusTotal data. Unable to see more without navigating to VirusTotal or logging in to achronicle account: <br/>
<img src="https://i.imgur.com/cXbL5Pi.png" height="80%" width="80%" alt="chronicle0"/>
<br />
<br />
This graphic displays the ET intelligence rep list classification: <br/>
<img src="https://i.imgur.com/Glwmb03.png" height="80%" width="80%" alt="chronicle0"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
