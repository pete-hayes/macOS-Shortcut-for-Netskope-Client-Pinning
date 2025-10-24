# macOS-Shortcut-for-Netskope-Client-Pinning
A macOS Shortcut that provides a simple menu-driven interface to pin, unpin, or review which Netskope Data Center or region the Netskope Client is connected to, without needing to open Terminal.

## Requirements
- macOS **Sequoia** (not tested in earlier versions)
- Netskope Client **R137** or higher
- Data Center Pinning enabled for Netskope Client *(currently in beta and not enabled by default)*

See https://docs.netskope.com/en/data-center-pinning-in-netskope-client for more details.

## Usage
1. Clone or download this repository.
2. Open the file `Netskope Data Center Selection.shortcut` and click **Add Shortcut**.
3. A menu will appear offering multiple options for changing or reviewing the current Netskope Data Center or region selection.

**Note:**
The first time you select an option, macOS may prompt for permission to run scripts or access certain folders.  
- The Data Center region list is stored and updated in a file located at `~/Documents/nsdiag_countries.txt`.  
- Operations that modify the Netskope Client configuration are executed through shell scripts.  
- Each permission must be granted for the corresponding menu option to function properly.

### Invoking the Shortcut

You can run the Shortcut directly from the macOS Shortcuts app, but it’s often more convenient to trigger it using one of the following methods:
- **Menu Bar:** Enable “Pin Netskope Data Center” in the Shortcuts section of the macOS menu bar for quick access without opening the app.  
- **Keyboard Shortcut:** Assign a hotkey to open the Shortcut.
- **Macro Key/Stream Deck:** Map the Shortcut to a macro key or Stream Deck button.  
- **Spotlight/Siri:** Run it by typing or saying the Shortcut name, e.g., “Run Netskope Data Center Selection.”

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk. 
