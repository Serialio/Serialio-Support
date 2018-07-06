# iScanBrowser for iOS

## Introduction
iScanBrowser is a powerful tool used to scan data into web applications on an iOS device. You can setup Web Form Rules to automatically select a field to import data, allowing you to avoid the need to tap the field as the focal point for the cursor. This is useful when you need to scan data quickly without using the iOS device’s interface. 

## Navigating the Web
- Set your homepage
- Set the start page
- Manage bookmarks and browsing history
## The Serial Device Manager (SDM)
- Pair with a Bluetooth device
- Device settings
  - idChamp 1128 example ***
    - Merge tags data
      - Merge tags data separator
![](https://i.imgur.com/igVcJ9k.png)
    - Show on connect
    - Constant read mode
    - EPC post
    - TID post
      - TID length
    - User Data post
      - User Data length
    - Adjust power
    - Set scanner auto-off time (keep idChamp 1128 ON)
  ![](https://i.imgur.com/3F6seV7.png)
- SDM settings
  - Enable auto-reconnecting to last device(s)
  - Enable the device filter
    - Adjust the device filter
  - Keep iOS awake
  - Reset device history
  
## Web Form Rules (WFR)
- About Web Form Rules
- Edit Web From Rules
  - Scanned value is URL
  - Limit by device type
  - Limit by scan values
  - Setup a scan value delimiter
  - Select target input
    - Focused input
    - Find by ID
    - Find by name
    - JavaScript function
  - Additional options
    - Only if empty
    - Simulate a call Form.Submit()
    - Append data
    - Execute custom JavaScript 
- Create a Web Form Rule
  - Create a new WFR using the dialog
  - Create a new WFR using the wizard
- Manage Web Form Rules
<!--   - Use your Cloud-In-Hand account with Web Form Rules -->
  - Prioritize Web Form Rules
  - Remove a Web Form Rule
  - Disable a Web Form Rule
- Web Form Rule settings
  - Setup a no-match sound
  - Restore the default WFRs (warning)
## Settings
### Appearance Settings
- Enable full screen mode
- Lock the orientation
### Security Settings
- Enable the Account Manager
- Clear private data
### Scanner Settings
- Define virtual data
- Enable saving scans to file
- Enable showing NDEF data in a popup
- Open NDEF data URLs
- Enable Scanfob compatibility
- 
### Triggers
- About triggers
- Trigger locations
- Trigger constant read mode
### Filter Settings
- Enable filtering
- Drop leading zeros
- Set a post scan suffix
- Filter duplicates
- See duplicates as new after predefined time
- Enable dropping non-printable characters
### Logging
- Submit a log



