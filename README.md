# Network Security Test 

## Objective 

This lab aimed to identify three targets in the network using Metasploit. In addition, Metasploit will be utilized to exploit the targets through a Universal Naming Convention (UNC) link. It is expected that by performing this lab, it will deepen my understanding of network security and vulnerabilities.

### Acquired Skills

- Learned to perform Nmap scan from within MSF Console.
- Ability to configure and launch Metasploit framework in kali Linux.
- Acquired knowledge of scanning and identifying live hosts, services and open ports within a network.
- Understand the process of initializing and managing Metasploit's database to store scan results.
- Knowledge of importing Nmap scan results into the Metasploit database.
- proficiency in execution of exploit on identified targets with the use of Metasploit to open Meterpreter.
- Enhancement of critical thinking and problem-solving skills.

### Tools Utilized

- Kali Linux for conducting penetration testing and network security assessment.
- Metasploit for developing and executing exploit code against a remote target machine.
- Windows, the target operating system for identifying vulnerabilities.

## Steps
1. Update and Setup:

    - Kali Linux was first updated as a root user.
    - Installation of Metasploit framework using the -y parameter for confirmation.
    - Metasploit database was initialized and the MSF Console launched.

    ![20240615_230710 Step_1](https://github.com/SunnyJose/Network-Security-Test/assets/170783401/cfdfcbb1-8349-41b7-840d-ca2f3bb96e30)

2. Conducting Nmap Scan:
   - Nmap scan was performed from within the MSF Console.
   - Three targets were identified from the Nmap scan.
   - The target output files from Nmap were imported into the Metasploit database.

   ![20240615_231142 Step_2](https://github.com/SunnyJose/Network-Security-Test/assets/170783401/6cc8cd0f-af32-4ebc-bc0d-383895c78238)
3. Exploit Configured and Executed:
   - The exploit was configured to use windows/meterpreter/reverse_tcp.
   - Exploit was executed.
   - Confirmed that a Meterpreter session was opened, indicating a successful exploit.



 

