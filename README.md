# Information Security in Healthcare Organizations using Honeypot Intrusion Detection System
## About
Healthcare Organizations have seen an alarming rise in cyber-attacks in the recent years. One way a hacker could get control was by breaking into a medical network
to gain access over the active medical devices that patients rely on for their survival. Protecting the security of data in health research is important because healthcare organization requires the collection, storage, and use of large amounts of personally identifiable health information, much of which may be sensitive and potentially embarrassing. Our network model proposes a low-interaction and a medium-interaction honeypot based intrusion detection system using Dionaea and Kippo SSH to secure our internal network and study the activities of the intruders. We also look at a possible Metasploit attack and Brute force attack
logged by Dionaea and Kippo SSH which prepares the Malware Analysis report of the suspicious file downloaded.

## Setup

1. Setup your VM Ubuntu 14.04 on VMware
2. Create an Amazon Web Services (AWS) ec2 instance of Dionaea and Kippo SSH with the provided configurations.
3. Setup your honeypots.
4. Perform the attack using Metasploit and observe the logs.
5. Look at the VirusTotal results of the files spitted out.

## Findings

The work concludes that Dionaea and Kippo SSH honeypot system act as an effective security mechanism placed in the DMZ to trap malware 
and to perform reports of malware ananlysis on logged binaries. They can also be used to log all activities of an attacker on the shell. 
This system can also be used to send emails to the administrative department in the healthcare organization so that they may be notified 
of the intruder’s activities. Cybersecurity knowledge for healthcare orgainizations is important for the hospital staff.
They have to be trained to understand the aspects of it. A secure and safe environment for patients is the goal of cybersecurity.

## Honeypots as security solution
![imghealth](https://user-images.githubusercontent.com/15608430/33223498-fcd2908a-d12d-11e7-897f-dc99d6dd515e.PNG)

