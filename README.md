# SIEM-Sentinel-Lab


## Description

I set up a Microsoft Sentinel SIEM and a virtual machine in Microsoft Azure configured as a honeypot to collect failed RDP logon attempts from attackers. I then mapped the attackers' geolocations in Microsoft Sentinel using data from a third-party IP geolocation service.

![Screenshot 2024-12-27 at 5 26 36 PM](https://github.com/user-attachments/assets/f192b601-b652-467d-91b2-eadcf4c9893f)

## Languages Used

- PowerShell
  - Used for gathering failed RDP logon information from Windows Event Viewer

## Utilities Used

- ip2location.io
  - Used IP address from failed RDP log to find geolocation.
  - Queries capped at ~500.
 
## PowerShell script running

![Screenshot 2024-12-27 at 6 14 03 PM](https://github.com/user-attachments/assets/05b27571-c1d5-468a-a413-627598420478)

## Attacks Mapped

![Screenshot 2024-12-27 at 3 18 17 PM](https://github.com/user-attachments/assets/34023505-034c-45d3-ab2b-4a9b548210e8)
