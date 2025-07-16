# Help Desk Simulation: No Internet Access (windows 10)
#This project was meant to simulate a common Tier 1  Help Desk scenerio: user reports being connected to wifi but unable to access the internet. The issue was reproduced, documented, and resolved using basic troubleshooting tools in Windows.

--

## Problem Description
>'user reports'
>"I'm connected to Wi-Fi but it says 'No Internet, Secured.' I can't load anything in my browser

--

## The Enviorment
-OS. Windows 10 Home
-Tools used. Command Prompt, Device Manager
-Simulated scenario. Network adapter was manually disabled to simulate the issue

--

## Troubleshooting Steps

### Step 1: Verified the issue
-Ran 'ipconfig' and found no valid ipv4 address
-Ran 'ping 8.8.8.8' - failed to reach the server [click here to view the image](ipconfig_after_fix)
