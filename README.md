## msfpython

msfpython is a wrapper for msfvenom commands written in python. 
Currently there are only three features:
  1. Autoremoval of the %COMPSEC% portion of a psh-cmd payload.
  2. Autosave to a preconfigured location. The current preconfigured location is /home/kali/Desktop/payloads but this can be changed by editing the save_directory variable in the source code.
  3. Creation of a secondary text file that is named the time of creation and the output file. This secondary file contains the variables used to create the payload.

To use this tool,
1. Download the file and place it in the desired directory and modify the file permissions so it can execute.
2. Run the command: alias msfpython='python3 /path/to/file'
3. Use msfpython to create payloads!

