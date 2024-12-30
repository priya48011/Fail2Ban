<h1>Fail2Ban SSH Protection</h1>


<h2>Problem Statement</h2>
a) SSH servers are a common target for brute-force attacks, where malicious actors repeatedly attempt to guess valid login credentials. <br />
b) Without proper protections, these attacks can compromise server security and lead to unauthorized access.
<br />


<h2>Objective</h2>
a) To implement a robust, automated security solution using Fail2Ban to detect and block suspicious SSH login attempts. <br />
b) Provide a straightforward method for others to replicate the setup to secure their systems.
<br />


<h2>Why Fail2Ban?</h2>
<b/>Automation:</b> Fail2Ban automatically monitors logs for specific patterns and acts based on predefined rules.<br />
<b/>Flexibility:</b> Highly configurable, allowing customization of ban times, retry limits, and monitored services.<br />
<b/>Lightweight:</b>It doesn’t require significant system resources, making it suitable for a wide range of servers.<br />


<h2>Project Scope:</h2>

- Installation and configuration of Fail2Ban to monitor and protect SSH (sshd service).<br />
- Fine-tuning Fail2Ban's jail.local and fail2ban.local files for optimal performance. <br />
- Testing the setup to ensure it bans IPs after multiple failed login attempts. <br />



<h2>Program walk-through:</h2>

<p align="center">
Fail2Ban Insatllation <br/>  <br/>
<img src="https://imgur.com/aGMbqKe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Copy of Conf file to Local file<br/><br/>
<img src="https://imgur.com/oFpQ6wD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding Settings to SSHD  <br/><br/>
<img src="https://imgur.com/lbVB98x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Fail2Ban Enable and Start<br/> <br/>
<img src="https://imgur.com/CHYo8OA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
