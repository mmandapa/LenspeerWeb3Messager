# LenspeerWeb3Messager
Project Overview
This project automates the process of logging into LensPeer using MetaMask, navigating through the "Who to Follow" section, and sending personalized messages to profiles using Selenium WebDriver. The goal is to streamline user interaction by automating routine tasks like signing in, connecting wallets, and direct messaging multiple profiles.

Project Workflow:
Open LensPeer Homepage (https://lenspeer.com/home).
Automate Login via MetaMask:
Click the "Sign In" button.
Click the "Connect Wallet" button.
Select "Connect with MetaMask".
Pause for manual MetaMask wallet authentication.
Send Messages to Profiles:
Navigate to the "Who to Follow" section.
Open each profile in a new tab.
Click the messaging icon and send a custom message to each profile.
Log and Report Progress.
Keep Browser Open Until Manual Closure.

WHAT PROJECT CURRENTLY DOES:
- OPENS CHROME TAB
- GOES TO LENSPEER
- CLICKS ON CONNECT WALLET
- HAS FUNCTIONALITY TO AUTOMATE MESSAGE
- JUST NEEDS A WAY TO DISPLAY IT ON CHROME

WHAT NEEDS TO BE FIXED:
- NEED A WAY USING COOKIES/INSPECT ELEMENT TO BE ABLE TO AUTOMATE AN EXISTING TAB TO SEND THE MESSAGES
- FIX CHROME PATH/CHROME DRIVER SO THAT MESSAGES CAN BE AUTOMATED FROM AN ALREADY OPEN TAB
