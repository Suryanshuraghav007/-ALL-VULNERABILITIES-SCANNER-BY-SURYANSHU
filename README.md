## -ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV

**ALL VULNERABILITIES SCANNER BY SURYANSHU RAGHAV** is a powerful Bash script for automating security testing in bug bounty hunting. It simplifies reconnaissance, port scanning, vulnerability scanning, and more, aiding security researchers and bug bounty hunters in efficiently finding potential security issues in target domains.


## Prerequisites

Before running the script, ensure that you have the following tools installed on your system:

- Nmap
- Dirb
- DNSenum
- Whois
- WhatWeb
- Wappalyzer
- Nikto
- Sublist3r
- Xsser
- SQLMap
- Nuclei
- Amass

Refer to the respective tool documentation for installation instructions.


## Features

- Automates various security testing tasks, including DNS enumeration, whois lookup, HTTP fingerprinting, and technology stack detection.
- Performs comprehensive port scanning using Nmap to identify open ports and gather information about the target system.
- Conducts thorough web server scanning with Nikto, uncovering potential vulnerabilities in the target's web applications.
- Scans for subdomains using Sublist3r, enabling the discovery of additional attack vectors.
- Performs directory enumeration with Dirb to identify hidden directories and files on the target's web server.
- Checks for XSS vulnerabilities using Xsser, a powerful cross-site scripting (XSS) scanner.
- Detects SQL injection vulnerabilities using SQLMap, a popular tool for automated SQL injection detection and exploitation.
- Conducts vulnerability scanning with Nuclei, a highly extensible and fast scanner for detecting potential vulnerabilities.
- Performs automated reconnaissance with Amass, a versatile and comprehensive tool for discovering subdomains, domain names, and associated IP addresses.

## Options

    -h or --help: Display the usage instructions.
    -l <file> or --list <file>: Specify a file containing target domain(s) to scan.
    -d <domain> or --domain <domain>: Specify a single target domain to scan.
    -o <directory> or --output <directory>: Specify the output directory path.
    -nt <threads> or --nmap-threads <threads>: Specify the number of threads for Nmap (default: 100).
    -dt <threads> or --dirb-threads <threads>: Specify the number of threads for Dirb (default: 10).

## Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/Suryanshuraghav007/-ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU.git
   
   ```
   ```
   cd -ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU
    ```
    ```
   chmod +x ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV.sh
    
    ```
   
    
    To scan multiple target domains listed in a file:
    ```
   ./ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV.sh -l domains.txt
   ```
   To scan a single target domain and specify the output directory:
   ```
   ./ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV.sh -d example.com -o output_directory
   ```
   To scan a single target domain and specify the output directory:
   ```
   ./ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV.sh -d example.com -o output_directory

 
  To adjust the number of threads for Nmap and Dirb:
  ```
   ./ALL-VULNERABILITIES-SCANNER-BY-SURYANSHU-RAGHAV.sh -nt 50 -dt 5
 ```
   

## Contribution

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## Maintainers :

`This Repo is maintained by : `

- [Suryanshu Raghav](https://github.com/Suryanshuraghav007)

### Author :

**Suryanshu Raghav**

* [Github]([https://www.github.com/shubham-rooter](https://github.com/Suryanshuraghav007))
* [Twitter]([https://www.twitter.com/shubhamtiwari_r](https://x.com/SURYANSHURAGHA2))
* [Linkdin]([https://www.linkedin.com/in/shubham-tiwari09/](https://www.linkedin.com/in/suryanshu-raghav-14273a228/))  


***Be consisent and hardworking in life***
***Enjoy Bug Hunting..***
