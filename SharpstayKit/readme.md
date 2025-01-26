I'm excited to share that I have completed the development of a new launch for an innovative havoc tool "Sharpstaykit/Clean"! This tool focuses on user and system persistence using a variety of methods. Compared to the cobalt Strike version, this tool has better Red Team Opsec practices, along with a handful of feature enhancements; below is a gif of the menu! My Red Team content will only benefit the Red Team. The blue team has a bad habit of creating rules and signatures for tools, and not the technique, I won't contribute to that culture!
Scenario: In the demo, I'm establishing system-level persistence by creating a service grant that the target user has the "Log on as service"

Demo:

A Closer look the menu

![SharpStay](https://github.com/bushidokarat3/Havoc/blob/main/SharpstayKit/SharpStay_menu.gif?raw=true)

Scenario: 

In the demo, I'm establishing system-level persistence by creating a service grant that the target user has the "Log on as service"

![SharpStay1](https://kevonsecurityllc.com/wp-content/uploads/2025/01/SharpkitFinal.gif)




















Credits
WMI Event Subscription - WQL Query from Empire Project and Matt Graeber's research
Scheduled Task COM Handler Hijack - idea from enigma0x3's research
Junction Folder - code and idea comes from matterpreter's OffensiveCSharp project
Backdoor LNK - comes from harmj0y's LNKBackdoor script
