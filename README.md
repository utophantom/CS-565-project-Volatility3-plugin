# CS-565-project-Volatility3-plugin
## Introduction
This final1.py file is a plugin for volatility3 framework. The code is based on `windows.pslist.PsList` plugin that reads all processes off of a memory dump, then filters out the list to show suspicious processes.
## How to use
1. Make sure you can run volatility3 successfully. Here is the link to their GitHub page: https://github.com/volatilityfoundation/volatility3
2. Copy final1.py to windows plugin folder in your volatility3 (eg. "volatility3/volatility3/plugins/windows")
3. Run the plugin. For example: `python3 vol.py -f $YOUR_RAM_DUMP_DIRECTORY windows.final1.CheckSusProcess`
## Note
*By default, my code can only filter out "cmd.exe" and "powershell.exe". You can manually edit/add other process names as annotated in my code.
