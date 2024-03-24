# SentinelScan-Dynamic-Network-Analysis-Suite

## Features

* Basic Scan: Scans TCP and UDP services, performs service version detection, and checks for common vulnerabilities and weak credentials.
* Full Scan: Includes all features of the Basic Scan and extends it by incorporating the Nmap Scripting Engine (NSE) for in-depth vulnerability analysis.
* Customization: Allows users to specify the network to scan and choose the scanning type (Basic or Full).

## Usage

Clone the repository :

  ``` git clone https://github.com/your_username/network-scanner.git ```

Navigate to the project directory:

 ``` cd network-scanner ```

Execute the script:

 ``` bash network_scanner.sh ```
 
Follow the on-screen instructions to input the network to scan and select the scan type.

## Requirements

* Bash (Tested on Bash version 4.4)
* Nmap (Tested on Nmap version 7.80)
* Hydra (Tested on Hydra version 9.1)

## License
This project is licensed under the MIT License

## Author

Thunder

## Acknowledgments

* This script was inspired by the need for efficient network scanning tools in cybersecurity operations.
* Special thanks to Anatoly for guidance and support during the development process.
