━━━━━━━━━━━━━━━━━━━━━━━━━━
#  OSK — On-Screen Keyboard
━━━━━━━━━━━━━━━━━━━━━━━━━━

REQUIREMENTS

────────────

• Windows 10 or 11 (64-bit)
• Internet connection (required during install)
• ~150 MB free disk space


INSTALLATION

────────────
1. Go to https://github.com/sms2anhadbir-dev/OnScreenKeyboard/releases and download the latest zip file

2. Decompress and run OSK_Setup.exe
   Right-click → "Run as administrator" if prompted by Windows.

3. Welcome screen — click Next.

4. Dependencies are downloaded automatically from GOATED APPZ servers.
   This includes all required packages bundled for offline install.

5. Choose keyboard language(s)
   Select one or more layouts from the list (e.g. English, French, Arabic).
   You can change this later from OSK Settings.

6. Choose install location
   Default: C:\Users\<you>\AppData\Local\Programs\OSK
   Click Browse to pick a different folder, then click Next.

7. Installation runs automatically:
   • Connects to servers and downloads OSK, OSK Settings, and the uninstaller
   • Creates desktop shortcuts for OSK and OSK Settings
   • Adds both apps to your Start Menu
   • Registers OSK in Apps & Features

8. Click Finish. OSK launches immediately and will
   start automatically every time you log in.

   NOTE: An internet connection is required during setup.
   If the installer says it cannot connect, check your
   connection and try again.


USING OSK

─────────

OPENING / CLOSING

  • OSK starts automatically on login.
  
  • Double-click the desktop shortcut, or find "OSK" in the Start Menu.
  
  • Click the X button on the keyboard to close it.
    (It will reopen on next login — see STARTUP below to disable.)

MOVING THE KEYBOARD

  • Click and drag anywhere on the keyboard frame to reposition it.
  
  • OSK remembers its position between sessions.

TYPING

  • Click any key to send that keystroke to whatever app is in focus.
  
  • Shift / Caps Lock work exactly like a physical keyboard.
  
  • Special keys (Enter, Backspace, Tab, arrows, etc.) are fully supported.

SWITCHING LANGUAGES

  • Language keyboards appear as extra tabs on the OSK title bar.
  
  • To add or remove languages: open OSK Settings (see below).

SETTINGS

  • Open OSK Settings from the desktop shortcut or Start Menu.
  
  • Or click the gear icon (⚙) on the keyboard title bar.

  • General tab: theme (dark/light), opacity, auto-show on text field focus.
  
  • Languages tab: enable or disable any of 80+ language keyboards.
    Use the search bar to filter, or use All / None to bulk-select.
    Changes take effect next time OSK is opened.

STARTUP BEHAVIOR

  • By default OSK launches with Windows.
  
  • To disable: open Settings → uncheck "Launch OSK on startup".
  
  • To re-enable: check it again, or re-run OSK_Setup.exe.


UNINSTALLING

────────────

Option A — Apps & Features (recommended):
  Settings → Apps → search "OSK" → Uninstall

Option B — Direct:
  Run OSK_Uninstall.exe inside your OSK install folder
  (default: C:\Users\<you>\AppData\Local\Programs\OSK\)

The uninstaller will:

  • Close any running OSK instances
  
  • Remove all installed files
  
  • Delete the desktop shortcuts and Start Menu entries
  
  • Remove the startup entry
  
  • Remove OSK from Apps & Features


TROUBLESHOOTING

───────────────

"Cannot reach servers" during install

  → Check your internet connection and try again.
  
  → Temporarily disable your firewall or antivirus and retry.

Keyboard not appearing on screen

  → Check the system tray (bottom-right) — OSK may be minimised.
  
  → Open Task Manager and end any existing OSK.exe processes, then relaunch.

Keys not registering in a specific app

  → Some apps (games, UAC prompts) block simulated input by design.
  
  → Try running OSK as administrator.

Windows Defender / antivirus flags the installer
  
  → This is a false positive common with PyInstaller-packaged apps.
  
  → Click "More info" → "Run anyway", or add an exception for OSK_Setup.exe.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
