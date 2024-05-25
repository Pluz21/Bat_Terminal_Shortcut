# Windows Terminal Starter

This simple batch script starts the Windows Terminal application.

## Usage

1. Head to the root of your terminal folder at `%USERPROFILE%\AppData\Local\Microsoft\WindowsApps`.
2. Right-click `wt.exe`,  and click "copy as path", or CTRL+SHIFT+.
3. Paste the copied path into the `_path` variable in `start_windows_terminal.bat`.
4. Right click on the .bat file and copy the path.
5. Use PowerToys Keyboard Manager to add a new shortcut mapping:
   - Choose "Run" in the actions.
   - Paste the path to `Launch_Terminal.bat`.
   - Add the desired shortcut key.

## Requirements

- [Microsoft PowerToys Keyboard Manager](https://learn.microsoft.com/en-us/windows/powertoys/)

## Script Explanation

- `Launch_Terminal.bat`: The batch script that starts Windows Terminal.
  - Sets the path to the Windows Terminal executable.
  - Delays execution for a short period.
  - Starts Windows Terminal.
  - Waits for a brief period before exiting.

## Additional Resources

- [Watch this script in action on YouTube](https://youtu.be/8wza5hcStHM)


