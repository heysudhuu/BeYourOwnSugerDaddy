# BeYourOwnSugerDaddy
Just For a Fun.
## How to Install This File 
1. Download the Shutdown File in Your PC/Laptop.
2. Click Win+R 
3. Write shell:startup Press Enter
4. Copy the shutdown file and paste it into the startup folder. 
5. Restart Your PC/Laptop 
















   **This content is intended solely for educational purposes. It should not harm your PC, but may potentially harm your friend's laptop or college computer...............................**


  ## Fixing Accidental Shutdown Command in Startup

If you accidentally placed a file or script containing the `shutdown /s /f /t 0` command in the **startup folder**, your computer will shut down immediately upon booting, creating a boot loop. Follow these steps to fix the issue.

### Locating the Startup Folder

The startup folder is usually located at:
C:\Users<YourUsername>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup



## **Method 1: Boot into Safe Mode**

1.Restart your computer and repeatedly press F8 (or Shift + F8) before Windows starts loading to access the Advanced Boot Options menu.

2.Select Safe Mode or Safe Mode with Command Prompt.

3.Once in Safe Mode:

    Press Win + R, type shell:startup, and press Enter to open the Startup folder.

    Delete the file or script containing the shutdown command.

4.Restart your computer normally.


##  **Method 2: Use Windows Recovery Environment**

1. Restart your computer and boot from a Windows installation USB or DVD.

2. Choose Repair your computer > Troubleshoot > Advanced options > Command Prompt.

3.In the Command Prompt, navigate to the startup folder:

   The startup folder is usually located at:

         C:\Users\<YourUsername>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
   Use the del command to delete the problematic file:
   
        del <filename>
4.Restart your computer.




