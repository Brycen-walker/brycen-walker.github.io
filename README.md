# State Round Tips, Tricks, and Strategies
Facing the challenge of the upcoming state round can be daunting for many CyberPatriot competitors. In this brief guide, I'll share some readily applicable tips and others that require a bit of preparation for future rounds.
<br>
<br>

## What to expect
State Round comes with a large jump in difficulty compared to Round 2 and Round 1 in all aspects. While I can't tell you exactly what to expect due to CyberPatriot's strict rules, I can give you some strategies you can try and implement yourself. 

### Critical Services
In terms of critical services, you will want to come prepared with premade configuration files. You may not be able to expect what these critical services will be but you can still try and mess around with common critical services in real world infrastructure like web servers and FTP servers. An important aspect of learning and competing is adapting.
<br>
In CyberPatriot terms, adapting is actively researching and learning during the competition. Look up the settings in critical service configuration files and implement secure settings. 
<br>
<br>
Overall, focus on secure implementations of configuration files, both in preparation and during competition. 
<br>

### Dealing with Harder Vulnerabilities

It is natural to get to a point where all the easy stuff is gone and you're stuck. My tip with dealing with harder vulnerabilities is to.... NOT DO THEM!
<br>
Now I don't mean that you should stop competing and go eat some pizza when you're stuck. Definitely not.
<br>
My point is, even though you "finished" the easy stuff, you did not finish the easy stuff. There is always stuff you are missing or security controls you put in place wrong.
<br>
Always go make and ENSURE you did everything PERFECTLY. 
<br>
<br>
Now the real tips for dealing with harder vulnerabilities is to just take your time. Try and find some clues that lead to the fact that something is vulnerable. Once you follow the trail, execute and eliminate the vulnerability. 
<br>
Also don't worry about perfection, take your time and you will succeed.
<br>

### Future-Proofing Your Competition Strategy

This guides purpose is to teach you how to fish, not give you fish, so I want to leave out as many specific examples as possible. 
<br>
<br>
In this portion, I want to focus on things you can do to better yourself in the competition, both for state and semis as well as your future years competing. 
<br>
A set of important documents that set out secure settings for many operating systems are the CIS Benchmarks. You can find a CIS Benchmark that pertains to your OS of choice and read through it. They cover secure options for important settings on that OS. This includes password policy, bootloader configurations, and much more. 
<br>
Read through and practice implementing these security settings on a fresh VM for invaluable practice. 
<br>
<br>
Another important concept in CyberPatriot is baselining. Baselining is the idea of comparing clean or secured configurations and environments to the ones in the challenge image.<br>
For example, if I compare a secure implementation of the ssh configuration file to the one on my home machine that I left vulnerable, I will notice that they differ in key areas. Then I can change the insecure setting. 
<br>
In a competition where so many things are insecure or vulnerable, the skill and ability to baseline becomes invaluable. 


## Closing Remarks and Overview

I do not wish to overwhelm you with information so I want to end it short. 
<br>
The main takeaway from this should be, take time and ensure security. 
<br>
Ensure security through secure configurations, retracing your steps, taking your time, baselining, and learning secure defaults before competition. 
<br>
Overall, don't stress and make sure to have fun.
<br>
<br>

### GOOD LUCK!
