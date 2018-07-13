# iScanBrowser for Android

## Introduction
iScanBrowser is a powerful tool used to scan data into web applications on an Android device. You can setup Web Form Rules to automatically select a field to import data, which allows you to avoid the need to tap the field as the focal point for the cursor. This is useful when you need to scan data quickly without using the Android device’s interface. 

## Navigating the Web
- Set your homepage
- Set the start page
- Manage bookmarks and browsing history
- Enable always showing the address bar
## The Serial Device Manager (SDM)
- Pair with a Bluetooth device
- SDM actions
  - Wait for connection
  - BlueSnap setup
  - Set NFC chip connect address
  - Connect BLE via QR code
  - Connect BLE via NFC chip
  - 
- Device settings
- SDM settings
  - URI app launch
  - Show battery in notifications
  - Auto reconnect
  - Vibrate on scan
  - Out of range alert
  - Sound on scan
    - Custom sound file
  - Sound on scan present
    - Custom sound file
  - Scan filter settings
    - Toggle filter notice
    - Never post duplicates
    - Post duplicates after a pre-defined time
    - Change the tag filters mode
      - Disabled
      - Mode: Ignore
      - Mode: Allow start with
    - Setup the tag filters table ***
      - Switch filter mode (ignore/allow)
      - Add tag value
        - Add tag sound
      - Add tags read to the tag filters table automatically
  - Scan modification settings
    - Clip scan data
      - Clip at start
      - Clip at end
## Settings
### Appearance Settings
- Enable full screen mode
- Lock the orientation
- Hide the toolbar/actionbar from the main view
- Show zoom control
### Security Settings
- Lock iScanBrowser settings with a password
- Clear private data
  - Clear cache
  - Clear history
### Scanner Settings
- Define virtual data
- Enable saving scans to file
- Enable showing NDEF data in a popup
#### Unimag Support
- About ID tech Unimag Support
- Enable Unimag support
- Enable showing the connect dialog
- Change the Unimag reader type
#### Scanfob 2006 Support
- Optimize HID input
- Enable detection of Scanfob brand barcode scanners
<!-- - Detect MSR tracks
- Define start and end sentinels
- Remove MSR sentinels
- Set a tracks timeout  -->
### Triggers
- About triggers
- Types of triggers
  - Trigger scan
  - Trigger camera
  - Trigger custom commands
- Add a key or button as a trigger option
- Set up trigger long-press mode
### Scan Settings
- Drop leading zeros
- Append scan data to current field value
- Enable enter after scan
- Filter duplicates
- See duplicates as new after predefined time
- Enable dropping non-printable characters
### Logging
- Submit a log
## Web Form Rules (WFR)
- About Web Form Rules
  - Types of Web Form Rules
    - Scan
    - Prompt
    - PDF 417
  - Capabilities of Web Form Rules
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



