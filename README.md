# ReverseShellExample
A Reverse Shell kit that is solely for educational purposes (like courses or lessons), I do NOT condemn any exploiative usage and I do NOT accept any liability.
Because of this, this project does NOT use any exploits to bypass any Antivirus Software. It only contains a way to Set Execution Policy of the Powershell for newer machines (I.E: Windows 11).

This project uses a fork of the NCat called [NCat Portable](https://github.com/cyberisltd/NcatPortable) - Check the Original Nmap license: https://svn.nmap.org/nmap/COPYING

# Instructions
- **Step 1:** Disable any Antivirus Softwares on the machine you want to try this in.
- **Step 2:** First, we should edit the Powershell script. Do a right-click/edit on the **shell.ps1**
- **Step 3:** Change the IP address to **your** Local IPv4 Address *(you can change your port now if you want/need to)*. Close the editing.
- **Step 4:** Open CMD at the folder that the **ncat.exe** is in by shift+right-click/Open this folder in CMD.
- **Step 5:** Type **"ncat.exe -lvnp 4440"** *(4440 is the default port, change this if you changed the port while editing Powershell script)*
- **Step 6:** After this, start the batch file called **"shell.bat"**.
- **Step 7:** You now should see your IP *(or the IP of the other machine)* at the CMD window that you launched Ncat.
- **Step 8:** And voila! You now got shell access in the computer! Try it by typing **"ls"** or **"cd"**
