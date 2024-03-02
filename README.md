# Burp-Suite-Pro

# Burp Prodessional Installation for Windows
  1. Copy the downloaded files to C:\Burp.
       Make new directory "Burp" in C Drive for faster access.
  2. Open Powershell and execute below command to set Script Execution Policy.
	    Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process
  3. Now Execute Windows_Setup.ps1 file in Powershell to Complete Installation.
	    ./Windows_Setup.ps1
  4. Change the icon of **Burp-Suite-Pro.vbs** to the given icon 
	    Create a shortcut to Desktop. Right Click over **Burp-Suite-Pro.vbs** Go to Shortcut tab, and below there is **Change Icon** tab.
	    Click there and choose the burp-suite.ico from C:\Burp\ 
  5. For Start Menu Entry, copy **Burp-Suite-Pro.vbs** file to 
    	C:\ProgramData\Microsoft\Windows\Start Menu\Programs\

# Burp Suite Professional Installation steps for Kali-Linux
--> Execute Kali_Linux_Setup.sh file as root user

# Burp Suite Pro Activation Steps
  1. Modify License String like "license to xxxxxxxx"
  2. Copy License key from loader.jar(Keygenerator) and paste in Burp Suite Pro and click Next.
  3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
  4. Copy License Request from BurpSuite_Pro and paste in Keygenerator.
  5. Copy license response from Keygenerator and paste in Burp Suite Pro, then next and Done.

# Executing Burp Suite Profession after Activation
  --> Windows :-: You can start Burp Suite Professional from Start Menu.
  --> Kali Linux :-: You can start Burp Suite Professional by writing **burpsuite** in terminal.
