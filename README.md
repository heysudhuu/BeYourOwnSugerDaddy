# BeYourOwnSugerDaddy
Just For a Fun.

1. Download the SugerBae File in Your PC/Laptop.
2. Start This File As a Startup App.















   **This Contain Only for EduCation Purpose Dn't Harm Your only Harm your friends Laptop or Clg..............................**


  ## Fixing Accidental Shutdown Command in Startup

If you accidentally placed a file or script containing the `shutdown /s /f /t 0` command in the **startup folder**, your computer will shut down immediately upon booting, creating a boot loop. Follow these steps to fix the issue.

### Locating the Startup Folder

The startup folder is usually located at:
C:\Users<YourUsername>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup



**Method 1: Boot into Safe Mode**
1.Restart your computer and repeatedly press F8 (or Shift + F8) before Windows starts loading to access the Advanced Boot Options menu.

2.Select Safe Mode or Safe Mode with Command Prompt.

3.Once in Safe Mode:

    Press Win + R, type shell:startup, and press Enter to open the Startup folder.

    Delete the file or script containing the shutdown command.

4.Restart your computer normally.


**Method 2: Use Windows Recovery Environment**
1. Restart your computer and boot from a Windows installation USB or DVD.

2. Choose Repair your computer > Troubleshoot > Advanced options > Command Prompt.

3.In the Command Prompt, navigate to the startup folder:

4.The startup folder is usually located at:

