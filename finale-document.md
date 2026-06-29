# Beginner Developer Workstation Setup and Troubleshouting Guide 

## Final Reflection

Before starting this one-week program, my knowledge was limited to just opening VS Code and writing basic Python code. However, this week completely changed how I look at technology. I now understand the deep relationship between software and hardware, and how they interact when a program runs.

More importantly, I learned how to troubleshoot systematically and actually find where a problem originates instead of guessing. I also gained practical skills in using the Command Prompt (CMD) to navigate my system and write professional documentation using Markdown (`.md`) files. This bootcamp gave me the solid foundations I needed to move forward as a developer.

---

## Troubleshooting Checklist

### 1. Problem: PC is slow
* **What to check:**
  * **CPU/RAM/Disk usage:** Open the Task Manager (`Ctrl + Shift + Esc`) and check the performance percentages. If any resource is close to 100%, a frozen background process might be consuming your system.
  * **Startup apps:** Check the Startup tab in Task Manager. Too many enabled apps during boot will drain your RAM and slow down the PC setup.
  * **Free storage:** Ensure your system drive (SSD/HDD) has enough free space; a full disk prevents the operating system from managing temporary files efficiently.
  * **Background updates:** Verify if Windows Update or other software updates are downloading silently in the background, which temporarily spikes resource usage.

### 2. Problem: Command not recognized
* **What to check:**
  * **Command spelling:** Double-check the exact syntax. Computer terminals require perfect spelling (e.g., `ipconfig`, not `ipconfeeg`).
  * **Software installed:** Ensure that the specific tool or language (like Python or Git) is actually installed on the machine.
  * **Terminal restarted:** If you just installed a new tool, restart your Command Prompt or Terminal session so it can register the changes.
  * **PATH configured:** Verify that the software's installation folder path is correctly added to your system's Environment Variables (the PATH variable). If it is missing, CMD will not know where the executable file lives.

### 3. Problem: Internet not working
* **What to check:**
  * **Wi-Fi/Ethernet:** Inspect the physical connection or Wi-Fi status to ensure the device is properly connected to the local network hardware.
  * **IP address:** Run the `ipconfig` command in CMD to verify if your machine is successfully receiving a valid IP address from the router.
  * **DNS:** Check if your Domain Name System is resolving website names into IP addresses. You can test this by running `ping 8.8.8.8` to see if external servers are reachable.
  * **Router and Network Adapter:** Ensure the local router is functioning properly and that your computer's network adapter drivers are active and not disabled.
  * 
