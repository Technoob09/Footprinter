# Footprinter
Information gathering plays a crucial part in preparation for any professional social engineering engagement. Information gathering is the most time-consuming and laborious phase of the attack cycle but is often a major determinant of the success or failure of the engagement. 

Objective of Footprinter:
- Collect Network Information
- Collect System Information
- Collect Organizations Information
 
Usage of Footprinter:

Specify API_Key in "info_gathering.py" for Shodan

Tool consist of "info_gathering.py" file simply install python in your machine run this file with following utilities:

- Run "python3 info_gathering.py -h" for help menu
- Use "python3 info_gathering.py -d DOMAIN_NAME" for Domain information
- The Script provide us the Whois info, DNS info, Geolocation info etc for specified domain
- Use "python3 info_gathering.py -s IP_ADDRESS" for IP information using Shodan
