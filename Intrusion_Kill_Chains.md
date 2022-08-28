**Homework-1**

**1-Summarize Article 3.2 & 3.3**


The existence of computer networks also gave rise to their vulnerability since users were keen on exploiting them from the very beginning. In fact, the threat went beyond exploiting household users to the point that the economies and militaries must prepare for threats called Advanced Persistent Threats (APTs). It has been described as an attack campaign in which an intruder establishes an illegal, long-term connection on a network in order to mine highly sensitive data. The conventional methods of defense such as antiviruses and the conventional patches were simply not enough since those attacks were socially engineered and solely targeted the end users via emails to launch malicious activities. In a kill chain model, just one mitigation breaks the chain and could simply baffle the adversary, therefore any repetition by intruders is just a liability that defenders must recognize and leverage on it. The analysts just need to study the indicators to find any useful piece of information which will lead to the purpose of an intrusion and using those indicators to design tools to detect such intrusions. 

This paper also introduced new kill chain model designed specifically by keeping intrusions in mind. The intrusion kill chain consists of reconnaissance, weaponization, delivery, exploitation, installation, command and control (C2), and actions on objectives. This includes gathering of information, designing and delivering malicious payloads, infiltrating and executing operations silently to achieve certain objectives. Defenders can study intrusion kill chains and measure their defensive capabilities or plan investment road maps to mitigate threats by by having keen understanding of the adversary. Defenders must gather as much information as possible about the mitigated intrusions so that they can reconstruct what would have happened if future intrusions circumvent the currently effective protections and detections. On a strategic level, the campaign analysis can help determine the intent of intruders by examining the multiple kill chains over time which would uncover commonalities and overlapping indicators. A campaign analysis is fundamentally about identifying the tactics, techniques, and procedures (TTP) of the intruders. In this way the intruder’s persistence becomes a liability which defenders can leverage by further strengthening the system.

The intrusion kill chain enables the analysis of intrusions, the extraction of indicators, and the deployment of defensive measures. The kill chain represents an asymmetry between aggressor and defender, with any repeating component by the aggressor seen as a liability.

**2-Command-line Basics Re-visited**

Rehearsed all basic commands 

**3-Install Debian Virtual Machine**

- Installed Virtual Box
- Spun up Debian VM using recommended Image: ```debian-live-11.4.0-amd64-xfce+nonfree.iso```
- Installed recommended packages and upgrades

```$ sudo apt-get update```

```$ sudo apt-get -y dist-upgrade```

```$ sudo apt-get -y install ufw; sudo systemctl status ufw; sudo systemctl start ufw ```

- Snapshot of machine state in VB

```$ sudo apt-get -y install openjdk-17-jre wget bash-completion```

- Download and kickstarted webgoat

```$ wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar```

```$ java -jar webgoat-server-8.0.0.M26.jar```

- Register http://localhost:8080/WebGoat/

**4-OverTheWire:Bandit Screenshots** 

![bandit0](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit0.png)
![bandit1](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit1.png)
![bandit2](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit2.png)
![bandit3](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit3.png)
![bandit4](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit4.png)
![bandit5](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/bandit5.png)

**5-Webgoat exercises**

![Webgoat](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/http_basics.png)
![Webgoat](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/developer_tools1.png)
![Webgoat](https://github.com/ahmad-zeeshan/DataSecurityHW/blob/main/screenshots/developer_tools2.png)
