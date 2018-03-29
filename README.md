# week9-honeypot
# Project 9 - Honeypot

Time spent: **3** hours spent in total

1. Which Honeypot(s) you deployed
  - Ubuntu - Dionaea with HTTP
2. Any issues you encountered
3. A summary of the data collected: number of attacks, number of malware examples, etc.
  - Ubuntu - Dionaea with HTTP
    - Over 1000 IPs accessing different ports.
	- Location of the IPs are from all around the world.
    - CINS Found some Active Thereat Inteillegence Poor Reputation IPs
	- SCAN Sipvicious User-Agent Detected (friendly-scanner)
	- DROP Dshield block listed source group
	- VOIP Modified Sipvicious Asterisk PBX User-Agent
	- POLCY suspicious inbound to MSSQL port 1433
4. Any unresolved questions raised by the data collected
  - How to get more information on what they are trying to do besides scanning?
5. JSON
  - [a link](https://github.com/et1n/Honeypot/blob/master/session.json)
6. GIF
  - GIF Walkthrough: <img src='week9.1.gif' />
